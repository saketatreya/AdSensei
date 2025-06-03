# Agentic Campaign Attribution MVP

Agentic Campaign Attribution MVP – simulates campaign events, runs last-touch attribution, and demonstrates an autonomous agent that auto-pauses or re-allocates budget. 

**Key Features:**
*   **Data Simulation**: Generates realistic marketing campaign data (`campaigns`, `users`, `events`, `conversions`).
*   **Attribution Engine**:
    *   Supports multiple attribution models: Last-Touch, Linear (Time-Decay planned).
    *   Calculates campaign performance metrics (spend, cost per conversion, ROI).
*   **Agentic Core**:
    *   Identifies underperforming and high-performing campaigns.
    *   Automatically pauses campaigns or increases their budgets.
    *   Logs all actions taken.
*   **Interactive UI**: A Streamlit application (`app.py`) to:
    *   View campaign data and attribution summaries.
    *   Manually trigger the agent.
    *   Monitor agent actions and current campaign statuses.
    *   Visualize ROI by channel.
*   **Demo Notebook**: An end-to-end demonstration in `notebooks/demo_end_to_end.ipynb`.
*   **Modular Design**: Code is organized into `data_simulator`, `attribution_engine`, and `agentic_core` for clarity and extensibility.

This project showcases a simplified end-to-end workflow for data-driven campaign optimization using agent-based decision making. 