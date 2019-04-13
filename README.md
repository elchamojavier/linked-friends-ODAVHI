# linked-friends-ODAVHI
OPEN DATA AND VENEZUELAN HEALTH INDICATORS

From the original repo in Code4Venezuela repo 
https://github.com/code-for-venezuela/2019-april-codeathon/tree/master/challenges/HRW-VIZ

PROBLEM STATEMENT

Human Rights Watch has been doing research that shows:

Increased levels of maternal and infant mortality.
The spread of vaccine-preventable diseases, such as measles and diphtheria.
Increases in the number of infectious diseases such as malaria and tuberculosis.
High levels of food insecurity and child malnutrition.
The report describes the public health implications in Venezuela and abroad, explains government policies that contributed to this crisis, and concludes that the United Nations, at its highest levels, should lead efforts to implement a large-scale assistance plan in Venezuela.

In order to create these reports, we analyzed data provided in "Boletin Epidemiológicos". However, the Venezuelan government stopped publishing those reports in 2017 [^1], so it is becoming more and more difficult to get this information. In addition to those reports, we started using X as a source.

We would like to make it easier and more transparent to start having access to Venezuelan health data. This could contribute to further research in the future and ….

CHALLENGE
In order to create more awareness about this issue, we would like to create a platform that makes this information available and discoverable through APIs. Similar to the work that PAHO is doing but completely focused on Venezuelan data.

OPEN DATA: The government used to publish reports about the health data of the country. You will have access to data in this folder. These documents are in a format that are not parseable by computers. The goal of this project is to create a system to parse all this data and make it available through APIs.
Partnerships - Bonus:
Explore partnerships with DataDrum, Transparencia Venezuela and Vendata.
Can we make these reports available through their platforms?
Visualization and Outreach: in order to create awareness about these issues, we want to present this data in a way that is easy to understand by the general public and easy to distribute. The goal of this project is to find creative ways to achieve this. Here are some directions:
Create a "bar chart race" visualization (like this) using data provided by HRW and PAHO for diseases in Venezuela and how they compare to other parts of the world?
Using the data from Boletin Epidemiológico, develop maps and dashboards for each Venezuela state?
Explore the correlation between these diseases and mortality rates.
Explore cases per capita compared to other countries.
Skills Required
Machine Learning, OCR, Image Processing, NLP.
API integration and development.
Javascript, D3, Web animation.
Open data initiatives.
Project contacts
Tamara Taraciuk, TODO

# Setup

```bash
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements_dev.txt
make install
```

Remember to always do `source venv/bin/activate` when working for the project.
