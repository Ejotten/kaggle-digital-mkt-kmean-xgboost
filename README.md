# Marketing Data Analysis using K-Means and XGBoost

This project utilizes marketing data to uncover customer patterns and develop predictive models for purchase likelihood. Insights gained will be used to optimize digital marketing budget allocation.

## Features

| Variable           | Description                                                                  |
|--------------------|-------------------------------------------------------------------------------|
| CustomerID        | Unique identifier for each customer                                          |
| Age               | Age of the customer                                                            |
| Gender             | Gender of the customer (Male/Female)                                               |
| Income             | Annual income of the customer in USD                                           |
| CampaignChannel    | The channel through which the marketing campaign is delivered (Email, Social Media, SEO, PPC, Referral) |
| CampaignType      | Type of the marketing campaign (Awareness, Consideration, Conversion, Retention). |
| AdSpend            | Amount spent on the marketing campaign in USD.                               |
| ClickThroughRate  | Rate at which customers click on the marketing content.                           |
| ConversionRate     | Rate at which clicks convert to desired actions (e.g., purchases).               |
| AdvertisingPlatform (Confidential) | Platform used for advertising                                  |
| AdvertisingTool    (Confidential) | Tool used for advertising                                        |
| WebsiteVisits      | Number of visits to the website.                                                   |
| PagesPerVisit     | Average number of pages visited per session.                                      |
| TimeOnSite         | Average time spent on the website per visit (in minutes).                         |
| SocialShares       | Number of times the marketing content was shared on social media.                |
| EmailOpens         | Number of times marketing emails were opened.                                   |
| EmailClicks        | Number of times links in marketing emails were clicked.                            |
| PreviousPurchases  | Number of previous purchases made by the customer.                              |
| LoyaltyPoints      | Number of loyalty points accumulated by the customer.                            |
| **Target Variable** |                                                                                |
| Conversion          | Binary variable indicating whether the customer converted (1) or not (0).        |

## Usage

This project employs two main approaches:

**1. Identify Key Patterns using K-Means:**

* Analyze the dataset to identify significant patterns and trends in customer interactions and behaviors.
* Segment customers based on natural groupings discovered through K-means clustering.
* Understand which demographic and engagement metrics are most indicative of conversion success for different customer segments.

**2. Predictive Modeling using XGBoost:**

* Develop machine learning models using XGBoost to predict customer purchase likelihood.
* Train models based on historical data, including customer demographics and engagement metrics.
* Use the models to segment customers based on their predicted conversion probability.

## Optimizing Budget Allocation

Insights from both pattern recognition and predictive modeling will be used to optimize the allocation of the digital marketing budget.

* Focus resources on high-potential customer segments identified through clustering and prediction.
* Maximize return on investment (ROI) by targeting marketing efforts towards customers most likely to convert.
