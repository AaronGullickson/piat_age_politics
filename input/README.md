# Data Source Description

The data we will use for this project come from the [Cooperative Election Study](https://cces.gov.harvard.edu/) which is administered by YouGov. This study regularly collects information on respondent's political attitudes and voting behaviors. We will specifically examine the 2020 wave of this dataset.

From the full data, I have extracted and recoded the following variables for our use as an analytical dataset. To load this dataset in R, you just need to run the setup code chunk in the full_report.Rmd R Markdown document. The name of the dataset in R is `ces`. 

* **conservative**: This variable is derived from a political ideology question that allowed respondents to respond to a 7-point scale from "Very Liberal" to "Very Conservative" with "Middle of the Road" being offered as the middle category. We are using that scale as a point system from 1-7 where 1 indicates "Very Liberal" and 7 indicates "Very Liberal". Thus higher values on this scale indicate greater conservatism. This is the key dependent variable.
* **age**: The age of the respondent in years. This is the key independent variable.
* **gender**: The self-reported gender of the respondent as male or female.
* **degree**: The highest educational degree of the respondent from no high school diploma to graduate degree.
* **race**: The self-reported race of the respondent in the categories of White, Latino, Black, Asian, Amerian Indian, Multiracial, Other.
* **region**: Region of the country in the categories of northeast, midwest, south, and west.
* **social_media**: Categorical variable indicating whether the respondent used social media in the last 24 hours or not.
* **watch_fox**: TRUE/FALSE variable indicating whether the respondent regularly watches FOX news. This is one of the key contextual variables.
* **watch_msnbc**: TRUE/FALSE variable indicating whether the respondent regularly watches MSNBC news. This is one of the key contextual variables.
