This folder containes two examples for automations:

1. Send a Slack/Teams message whenever a scorecard rule result is **updated**
   
   Pre-requisites:

   The workflow requires a Slack webhook URL and/or a Microsoft Teams webhook URL to send the message.  

    **Slack**:
    1. To set up a Slack webhook, follow the instructions [here](https://api.slack.com/messaging/webhooks).
    2. Once you have the webhook URL, add it as a secret in your GitHub repository named `SLACK_WEBHOOK_URL`.

    **Microsoft Teams**:
    3. To set up a Microsoft Teams webhook, follow the instructions [here](https://learn.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook).
    4. Once you have the webhook URL, add it as a secret in your GitHub repository named `TEAMS_WEBHOOK_URL`.

2. Create a GitHub issue whenever a scorecard rule result is **degraded**

Each example contains a JSON definition for the automation, and a GitHub workflow that serves as the backend.