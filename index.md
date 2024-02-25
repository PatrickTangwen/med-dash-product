## Introduction
As health sensor technology becomes more advanced and common amongst the general population, we as data scientists are provided with a whole plethora of health related data that can provide meaningful insights to a person's health status. Our project aims to combine all the different forms of sensor data into a consolidated dashboard that will provide the user with a snapshot of their current health status.<br>

Major insufficiencies in healthcare systems today leave patients and clinicians alike wanting for a more effective way of receiving and giving care. Several major deficiencies are 1) the lack of an integrated Electronic Health Record (EHR), lifelog, and personal omics data, and 2) the lack of standardization across healthcare systems, data standards, and terminologies. This incompatibility creates inefficiencies in operating personalized medicine, leading to problems with interoperability and introducing ambiguity into the healthcare environment, especially amongst patients, their providers, and organizations. We talked to real patients who have struggled with these issues in their medical are history, and identified the core problems they were having with the way care was prescribed to them. Using this information, we proceeded to come up with a solution that could help boost the communication and understanding between patients and their healthcare providers.

## Methods
We were given data from volunteer patients that were eager to help with our project. The data comes from the Vital API and includes variables such as: heart rate, calories burned, number of steps, etc. This is unique from other dashboards as we are obtaining the data from the patients themselves that they provide from different sources. We also established of a user-centric login infrastructure, allowing seamless connectivity of user devices to the Vital API seamlessly integrated within our medical dashboard. Subsequent to user authentication, the Vital API would autonomously generate a distinct token for each user, facilitating the provision of rudimentary visualizations pred-
icated upon the respective device data.

For design, we used third party library called "AntDesign" as the primary tool to integrate visualizations onto our website while using Pandas,Numpy,MongoDB to create a data pipeline that is designed to pull, read, clean, standardize, and add features to the data given to our team from the Vital APIs. To host our work, we used React.js hosted on Github Pages to create a website that would allow the user to interact with the visualizations.<br>
<br>

Below is the architecture of our website:<br>
<img width="789" alt="image" src="https://github.com/PatrickTangwen/med-dash-product/assets/102566928/394f1498-055c-4c66-8aea-1cca5ecff9f2">

The user login system:<br>
<img width="419" alt="image" src="https://github.com/PatrickTangwen/med-dash-product/assets/102566928/cd5976b2-4b41-47a9-86a4-af74d70a5208">


The medical dashboard:<br>
<img width="1142" alt="image" src="https://github.com/PatrickTangwen/med-dash-product/assets/102566928/c9f1db4a-f912-43d5-8b01-09a370802442">


## Results
- At present, our system employs dummy accounts for user login purposes. Looking ahead, patients can create their own username and login based on their needs.
- Ethical considerations in regard to legal and social-related data integration problems as manipulating biometric data is very sensitive and personal.
- Because of privacy related concerns, we did not have much data to work with. Currently all source of data are randomly generated.
- Next step: incorporating more functionalities to the medical dashboard such as journal entry, predictive analytics and real-time health alerts.
- Getting more feedback from patients/users will help us determine what features are helpful.


## Conclusion
- The multiple sources of data are able to be consolidated into a single dashboard in a static manner.
- We were able to create a personalized, interactive, and explanatory dashboard for a single user with login functionality.
- Health data for patients can be visualized with the flexibility to select specific dates.





