Project Focus:
The primary goal of this project was to understand the relationship between funding for libraries and various other factors collected from multiple sources. The aim was to investigate which of these factors have the most substantial impact on library funding.

Data Collection:

Data was gathered from diverse sources, including the libraries themselves, the Ontario data website, and the Stats Canada website.
Multiple datasets were combined to form a comprehensive pool of information for analysis.
Correlation Analysis:

Correlation analysis was conducted on the collected data to identify the most significant factors.
Over 70 features exhibited a correlation higher than 0.8 with funding.
Predictive Model Generation:

A predictive model was developed using highly correlated features to forecast funding expectations for the upcoming year.
Initially, the model suffered from underfitting, which was mitigated by further reducing the feature set.
Subsequently, an overfitting issue arose, necessitating additional feature reduction.
The final model adopted was an Extra Tree Regression model, achieving an accuracy of 87%.
Dashboard Creation:

The project team designed a dashboard to visually represent key insights.
Selected dashboard features:
Current funding amounts
Predicted funding amounts
Expenses (constituting 4 of the top 5 correlated features)
Population (the most significant feature in the predictive model)
Ratio of spending on print vs. electronic materials (aligned with the primary goal of Ontario public libraries).
Potential Impact:
If implemented, the predictive model and dashboard could provide the following benefits:

Enable the government to estimate future funding needs for libraries.
Facilitate strategic decisions, such as determining optimal locations for new libraries based on predicted funding requirements.
Enhance the government's accuracy in budgeting for funding of Ontario libraries.
