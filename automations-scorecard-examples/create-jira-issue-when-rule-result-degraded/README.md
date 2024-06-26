## Create a Jira issue whenever a scorecard rule result is **degraded**
   
### Pre-requisites:

#### Port & Jira credentials

In your GitHub repository, go to `Settings`>`Secrets` and add the following secrets:

- `JIRA_API_TOKEN` - A [Jira API token](https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/) used to authenticate with Jira
- `JIRA_BASE_URL` - The URL of your Jira organization
- `JIRA_USER_EMAIL` - The email of the Jira user that owns the Jira API token
- `PORT_CLIENT_ID` - Your port [client id](https://docs.getport.io/build-your-software-catalog/custom-integration/api/#find-your-port-credentials)
- `PORT_CLIENT_SECRET` - Your port [client secret](https://docs.getport.io/build-your-software-catalog/custom-integration/api/#find-your-port-credentials)

