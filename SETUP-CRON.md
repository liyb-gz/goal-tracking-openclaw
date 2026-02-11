# Setting Up Proactive Coaching Reminders

OpenClaw's built-in scheduler can send you coaching nudges at the right times. This guide shows how to set up automated reminders.

## Quick Setup

Run these commands in your terminal to set up morning and evening coaching nudges:

### Morning: Daily Targets Reminder

```bash
openclaw cron add \
  --name "Morning targets" \
  --cron "0 8 * * 1-5" \
  --tz "YOUR_TIMEZONE" \
  --session isolated \
  --message "Good morning! Ready to set today's targets? What are your 1-3 priorities for today?" \
  --deliver \
  --channel YOUR_CHANNEL
```

Replace `YOUR_TIMEZONE` (e.g., "America/New_York", "Europe/London", "Asia/Tokyo") and `YOUR_CHANNEL` (e.g., "whatsapp", "telegram", "discord").

### Evening: Daily Summary Reminder

```bash
openclaw cron add \
  --name "Evening summary" \
  --cron "0 20 * * 1-5" \
  --tz "YOUR_TIMEZONE" \
  --session isolated \
  --message "How did today go? Ready for a quick end-of-day reflection?" \
  --deliver \
  --channel YOUR_CHANNEL
```

### Friday: Weekly Summary Reminder

```bash
openclaw cron add \
  --name "Weekly summary" \
  --cron "0 17 * * 5" \
  --tz "YOUR_TIMEZONE" \
  --session isolated \
  --message "It's Friday — want to do a quick weekly reflection before the weekend?" \
  --deliver \
  --channel YOUR_CHANNEL
```

### End of Month: Monthly Review Reminder

```bash
openclaw cron add \
  --name "Monthly review" \
  --cron "0 10 28-31 * *" \
  --tz "YOUR_TIMEZONE" \
  --session isolated \
  --message "The month is wrapping up. Ready for a monthly reflection and to set next month's goals?" \
  --deliver \
  --channel YOUR_CHANNEL
```

## Using Heartbeat Instead

If you prefer context-aware nudges rather than fixed-time reminders, the workspace's HEARTBEAT.md already handles this. Configure your heartbeat interval and active hours in your OpenClaw gateway config:

```json5
{
  agents: {
    defaults: {
      heartbeat: {
        every: "30m",
        activeHours: {
          start: "08:00",
          end: "22:00",
          timezone: "YOUR_TIMEZONE",
        },
      },
    },
  },
}
```

The heartbeat approach is more context-aware — it checks whether you've already set targets or done a summary before nudging. Cron jobs are simpler but always fire at the set time regardless of context.

## Managing Cron Jobs

```bash
# List all jobs
openclaw cron list

# Pause a job
openclaw cron pause "Morning targets"

# Resume a job
openclaw cron resume "Morning targets"

# Delete a job
openclaw cron delete "Morning targets"
```

## Weekend Configuration

The examples above use `1-5` (Monday-Friday). To include weekends, change to `*`:

```bash
--cron "0 8 * * *"    # Every day
--cron "0 8 * * 1-5"  # Weekdays only
--cron "0 8 * * 6,0"  # Weekends only
```
