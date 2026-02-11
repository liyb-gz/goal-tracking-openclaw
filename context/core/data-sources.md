# Data Sources for Automatic Gathering

Integrations that can provide data for summaries and reflection.

## Available Integrations

### Browser History

-   **What:** Sites visited, time spent
-   **Reveals:** Actual time usage, interests, distractions
-   **Privacy note:** Can be filtered to exclude sensitive sites
-   **MCP:** Custom or ActivityWatch

### Calendar Events

-   **What:** Meetings, appointments, scheduled activities
-   **Reveals:** How time was allocated, commitments kept/missed
-   **MCP:** Google Calendar, Apple Calendar

### Email Activity

-   **What:** Emails sent/received, response patterns
-   **Reveals:** Communication load, responsiveness
-   **MCP:** Gmail, custom

### App Usage (ActivityWatch)

-   **What:** Screen time by application, window titles
-   **Reveals:** Deep work vs. shallow work, tool patterns
-   **MCP:** ActivityWatch

### Git Commits

-   **What:** Code contributions, project activity
-   **Reveals:** Technical productivity, project progress
-   **MCP:** Built-in to Cursor/OpenCode

### Fitness Data

-   **What:** Steps, workouts, sleep, heart rate
-   **Reveals:** Physical activity, rest quality
-   **MCP:** Apple Health (custom), Fitbit

### Task Completion

-   **What:** Todos checked off in task apps
-   **Reveals:** Execution on intentions
-   **MCP:** Todoist, Things, custom

### Quick Captures

-   **What:** Notes, voice memos throughout day
-   **Reveals:** Thoughts, ideas, in-moment reflections
-   **MCP:** Apple Notes, Obsidian, custom

---

## Integration Status

Each source in a user's profile can be:

-   **Active** — Agent queries and uses this data in summaries
-   **Configured** — Set up but not actively queried
-   **Not configured** — No MCP/integration connected yet

---

## Adding Custom Sources

Users can define additional data sources. The agent needs to know:

-   Source name
-   What data it provides
-   How to query it (MCP server name or manual input prompt)

---

## Adding New Integrations

When a user wants to add a data source:

1. Research available MCP servers (web search)
2. Guide through setup and configuration
3. Update MCP config files (.cursor/mcp.json, opencode.json)
4. Update user's profile with new source
5. Test the integration
