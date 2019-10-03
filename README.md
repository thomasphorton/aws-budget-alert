Have you been procrastinating setting up an AWS budget because you're just too busy building?

This CloudFormation Template will set up a basic budget alert for your global AWS spend. It'll take 30 seconds.

## Parameters
### NotificationEmail:
* Required: Yes
* Type: String
* Description: Email address to receive budget alerts.

### MonthlyBudget:
* Required: Yes
* Type: Number
* Description: (USD) Monthly budget in USD.

### AlertThreshold:
* Required: Yes
* Type: Number
* Description: (%) Alert when forecasted budget exceeds this percentage.
