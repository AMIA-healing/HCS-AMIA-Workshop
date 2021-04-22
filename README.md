
# The Ohio Opportunity Index Project
## The Children's Opportunity Index

### Translating Research into Practice: construction, visualization, and applications of the Ohio Children’s Opportunity Index
#### Members: Priti Singh[1], PhD, MS (Construction of COI); Ian Dunn[2], MPH, GISP (COI aggregation at Zip Code level); Pallavi Jonnalagadda[1], MBBS, DrPH (Visualization of COI using Tableau); and Christine Swoboda[1], PhD, MS (Applications of COI);
#### Study Lead: Naleef Fareed[1], PhD, MBA

###### [1]College of Medicine, The Ohio State University, Columbus, Ohio
###### [2]Government Resource Center, The Ohio State University, Columbus, Ohio


### Areas of focus 
● Familiarize oneself with the decisions involved in data selection and extraction to construct an area-level index of opportunity 
● Construct a multi-year area-level index of opportunity using R Studio and R Markdown 
● Apply different approaches to aggregate area-level indices of opportunity at the Zip Code level using Esri’s ArcGIS ● Develop visualizations of opportunity indices using an off the shelf software: Tableau 
● Learn how public health agencies can use the information.

### Overivew
Area-level measures of deprivation account for social determinants of health (SDoH) factors at the geographic level. These indices have been successfully used in other countries for resource allocation. The state of Ohio, through the Ohio Department of Medicaid, tasked researchers at the Ohio State University with the development of an area-level measure of SDoH relevant to children’s outcomes known as the Ohio Children’s Opportunity Index (COI). A dashboard tool for the visualization of COI to end-users was needed. The workshop covers the following modules: a. Input, data selection, and extraction for the Ohio COI, b. Construction of the COI: the compilation of 53 measures in eight domains to construct the COI, alternative approaches to weighting the COI: use of latent class analysis to combine the eight domains into the COI and equally-weighting all eight domains to construct the COI, c. Approaches to aggreate area-level indices of opportunity at the Zip Code level using ArcGIS, d. Visualization of COI using Tableau: visualizations to effectively present COI using Tableau, and e. Applications of COI: use cases of COI for end-users from public health agencies.

The goal of our workshop is to present an approach for the development, visualization, and communication of an area-level deprivation measure that can be easily adopted by audience members to their own SDoH context and problems. Our approach, moreover, engenders a user-centered design philiosphy that engages key stakeholders as co-creators of our measures and their associated tools. This approach ensures their sustained and meaningful use over time, which we will also highlight during our workshop.

### Introduction
Individual factors alone have been insufficient in capturing determinants of disease thereby making the spatial context important. The relationship between deprivation in terms of place of residence, access to healthy food, water and sanitation, and health has been recognized for centuries. [[1]](#1) The high rate of infant mortality in Ohio,(#2)[[2,3]](#3) and the wide disparity in infant mortality rate between infants born to White and Black mothers [[3]](#3) provided the Ohio Department of Medicaid (ODM) with the impetus for the creation and visualization of the Ohio Opportunity Index (OI) [[4]](#4) and the Ohio Childrens Opportunity Index (COI) as part of the Infant Mortality Project. Our team has successfully presented the Ohio OI through an interactive analytical dashboard. [[4]](#4) The ODM indicated a similar dashboard for the Ohio COI. The Ohio COI is a measure of area-level SDoH composed of 53 measures spanning eight domains. Our team used an iterative and user-centered design approach to develop the Ohio COI dashboard.

This workshop is divided into the following modules: 1-Input, data selection, and extraction for the Ohio COI,; 2-Construction of the COI; 3-Aggregation of COI; 4-Visualization of the COI & 5-Application of the COI.

# Modules 1 & 2
<details>
  <summary>Click to expand!</summary>
  
Module 1: Input data selection and extraction for the Ohio COI

In this module, we will discuss the decisions involved in the selection of input data for the construction of the Ohio COI. Further, we will describe the extraction of data from multiple sources and linkage of the information by Census Tract across data sets.

  
Module 2: Construction of the Ohio COI

We will walk the audience through the construction of the Ohio COI based on the seminal approach that is the foundation for several well-known area level SDoH measures used internationally and in the US. [[5,6]](#5)(#6) In this module, we will:
1.	Demonstrate the multi-step approach proposed by the authors of the seminal study, which we adapted for the Ohio COI using R and R Studio. This step will also involve showing the audience how to develop an area level SDoH measures for multiple time periods. 
2.	Demonstrate two approaches our team used for the development of the Ohio COI and explain the preference of one approach over the other. For the initial development of the Ohio COI, we followed a previously described approach [[5,6]](#5)(#6) of latent factor analysis to assign weights to each of the eight domains. Our team also used an approach where each domain was equally weighted. We will walk the audience through constructing the weighted and unweighted indices during our workshop. 
3.	Show examples of how area level SDoH measures can be validated using existing measures that are publicly available. This will also involve describing results from our validation study of the Ohio COI by assessing its association with health indicators like life expectancy, and racial distribution. 

{% include youtubePlayer.html id="yhYXBpB9tkM" %}

[Modules 1 & 2 slides](https://github.com/OEIcat/AMIA_Workshop/raw/Introduction/AMIA_Slides.pdf)



[Modules 1 & 2 video]

</details>

# Module 3
<details>
  <summary>Click to expand!</summary>

### Module 3: Ohio COI aggregation at Zip Code level 
In this module we will walk the audience through how to aggregate the Ohio COI to the Zip Code level. A Zip Code is not an inherent geographic unit with defined boundaries, but a unique code used by the United State Postal Service to group addresses together to aid in mail delivery. Zip Codes are often used in public health to collect and report data because they are more common to the general public than geographic units such as the Census Tract. Zip Codes and Census Tracts do not share geographic commonalities which makes aggregating data collected at the Census Tract level to the Zip Code a challenge. We will demonstrate various geospatial approaches using Esri’s ArcGIS software to aggregate COI values to Zip Codes. These methods can also be used to aggregate data between any geographic units that do not share common boundaries (e.g. drive time radii and census tracts).



{% include youtubePlayer.html id="JZO4I3XpZvc" %}

[Module 3 slides](https://github.com/ChildrensOpportunityIndex/The-Ohio-Opportunity-Index-Project/raw/main/W13_ZipCode_Ian.pdf)



</details>

# Module 4
<details>
  <summary>Click to expand!</summary>

### Module 4: Visualization of the Ohio COI using Tableau
Our team used an iterative user-centered design approach to develop the Ohio COI dashboard and used Tableau to create various components of the dashboard. In this module we will:
1.	Discuss the choices and decisions made in regard to the content, function and aesthetics of the Ohio COI dashboard based on iterative feedback from project sponsors, also known a co-creation or user-centered design. We will provide the audience with a set of usability tools to systematically collect information from stakeholders to help improve the tool.  
2.	Demonstrate the use of Tableau to visualize Ohio COI scores at the Census Tract level; display Ohio COI data calculated at different time points; display change in Ohio COI data between two time points; and compare relative positions for Census Tracts. 
3.	Demostrate the visualization of Ohio COI and the race/ethnic distribution of the Ohio population, as well as, other publicly-available SDoH data like the Social Vulnerability Index (SVI). 

{% include youtubePlayer.html id="Y7Ux5ia1FoE" %}

[Module 4 slides](https://github.com/OEIcat/AMIA_Workshop/raw/Introduction/AMIA-presentationv2.pdf)

[Module 4 video]

</details>

# Module 5
<details>
  <summary>Click to expand!</summary>
  
### Module 5: Applications of the Ohio COI
In this module, we describe real-life scenarios on how the Ohio COI can be used by key stakeholders. Our example pertains to a public health program manager trying to gain a better understanding of infant outcomes in certain geographic areas. In this example, we will demonstrate how the program manager can assess the Ohio COI and its individual domains, but also visually examine other characteristics of the areas under consideration like the race and ethnic make-up, the social vulnerability index, and the change in scores over time. 

{% include youtubePlayer.html id="xC6JFpjRc2k" %}

[Module 5 slides](https://github.com/OEIcat/AMIA_Workshop/raw/Introduction/AMIA_PowerPoint_Template_2021%20CMS%20slides.pdf)

[Module 5 video]

</details>

### Discussion
The evidence base for SDoH measures indicates their strong potential to influence the health outcomes of individuals and populations. Another emerging evidence base for data visualization suggests that systematic, user-centered development of tools such as dashboards result in sustainable and effective use of such tools by end-users. Our workshop will fill two critical gaps: 1) it will reveal the inner workings of an area-level SDoH measure; allowing audience members to understand and interpret such measures, which they can later explain to their stakeholders when developing similar measures; and 2) it will provide them with a set of tools on the systematic design, development, and deployment of dashboards to visualize and analyze the SDoH measure. 

There is a critical need to incorporate research findings in to practice in this field. Current practices around SDoH indices need critical thought around development, communication, and use. Our five-module workshop – focused on data selection, construction, aggregation, visualization, and application – will help participants to gain expert insights on how to effectively engage in these vastly different aspects of deploying an area-level SDoH measure that leverages knowledge from multiple disciplines, that include informatics, geospatial science, public health, and user experience. Our tool can also be incorporated in to the electronic health record through FHIR and SMART applications, which will be the topic of a future workshop at AMIA. 

The evidence base for SDoH measures indicates their strong potential to influence the health outcomes of individuals and populations. Another emerging evidence base for data visualization suggests that systematic, user-centered development of tools such as dashboards result in sustainable and effective use of such tools by end-users. Our workshop will fill two critical gaps: 1) it will reveal the inner workings of an area-level SDoH measure; allowing audience members to understand and interpret such measures, which they can later explain to their stakeholders when developing similar measures; and 2) it will provide them with a set of tools on the systematic design, development, and deployment of dashboards to visualize and analyze the SDoH measure. 

There is a critical need to incorporate research findings in to practice in this field. Current practices around SDoH indices need critical thought around development, communication, and use. Our five-module workshop – focused on data selection, construction, aggregation, visualization, and application – will help participants to gain expert insights on how to effectively engage in these vastly different aspects of deploying an area-level SDoH measure that leverages knowledge from multiple disciplines, that include informatics, geospatial science, public health, and user experience. Our tool can also be incorporated in to the electronic health record through FHIR and SMART applications, which will be the topic of a future workshop at AMIA. 

### Conclusion
Our implementation of the state-wide COI began in 2019, and is noteworthy because of its state-wide impact and its intended use by diverse stakeholders, which include policy makers, community health workers, and providers. Our efforts to disseminate our experience will help maximize the benefits of using similar area-level SDoH indices in other settings. The anticipated audience includes informatics researchers, IT developers, health providers, and public health analysts. 


## References
<a id="1">[1]</a> 
Rosen, G. (1958). 
MD monographs on medical history. 
A history of public health, Vol 1, 147-148.
MD Publications. https://doi.org/10.1037/11322-000

<a id="2">[2]</a> 
Infant Mortality Rates by States. (2019). 
Center for Disease Control and Prevention
https://www.cdc.gov/nchs/pressroom/sosmap/infant_mortality_rates/infant_mortality.htm.

<a id="3">[3]</a> 
Infant Mortality Report.(2018). 
Ohio Departement of Health 
https://odh.ohio.gov/wps/wcm/connect/gov/dd1865c0-909c-4378-a8e0-61e28364bbae/2018+Ohio+Infant+Mortality+Report.pdf?MOD=AJPERES&CONVERT_TO=url&CACHEID=ROOTWORKSPACE.Z18_M1HGGIK0N0JO00QO9DDDDM3000-dd1865c0-909c-4378-a8e0-61e28364bbae-n1Z1tQk

<a id="4">[4]</a> 
Fareed N, Swoboda CM, Jonnalagadda P, Griesenbrock T, Gureddygari HR, Aldrich A.(2020). 
Visualizing Opportunity Index Data Using a Dashboard Application: A Tool to Communicate Infant Mortality based Area Deprivation Index Information.
https://odh.ohio.gov/wps/wcm/connect/gov/dd1865c0-909c-4378-a8e0-61e28364bbae/2018+Ohio+Infant+Mortality+Report.pdf?MOD=AJPERES&CONVERT_TO=url&
Applied Clinical Informatics, 11(04): 515-527

<a id="5">[5]</a> 
Townsend P, Phillimore P, Beattie A. (1988). 
Health and Deprivation : Inequality and the North..
Nurs Stand. Jan 30;2(17):34. doi: 10.7748/ns.2.17.34.s66. 

<a id="6">[6]</a> 
Noble M, Wright G, Smith G, Dibben C.(2006). 
Measuring Multiple Deprivation at the Small-Area Level.
Environment and Planning A: Economy and Space.2006;38(1):169-185. doi:10.1068/a37168.


