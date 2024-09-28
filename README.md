# Jira to PostgreSQL Integration

This project extracts data from Jira tickets, including monitoring information from Site24x7, and stores it in a PostgreSQL database.

## Features

- Fetches Jira ticket data, including monitoring information such as `Display Name`, `Monitor Status`, `Down Since`, and `Failed Locations`.
- Inserts or updates the extracted data in a PostgreSQL database.

## Setup Instructions

### Prerequisites

- Python 3.6+
- PostgreSQL database with access credentials
- Jira API credentials (`JIRA_URL`, `JIRA_USERNAME`, `JIRA_API_TOKEN`)

### Steps to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/ayushpathak299/jira-to-postgresql-lambda.git
    cd CAM-Project
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Configure your Jira API and PostgreSQL credentials inside the script.

4. Modify the `JQL_QUERY` in the script if necessary.

5. Run the script:
    ```bash
    python main.py
    ```

