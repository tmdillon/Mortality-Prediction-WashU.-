# Mortality-Prediction-WashU.

## 1. This project is within the Tools and Cloud Architecture Core. 
## 2. Under the Dream Challenge Project.  
## 3. Mortality-Prediction-WashU. 


************ WashU Mortality Prediction Contribution **************

Research Design

The Washington University contribution to the Dream Challenge (mortality prediction) project is an enhancement to the original project and a solution to a potential pitfall that was identified. Specifically, the data on which the original algorithms will be built span multiple care sites in the University of Washington Medicine system with visits occurring from 2007 to 2019 [approximately 1.3 million patients with more than 800,000 having 3 or more visits documented in the electronic health record (EHR)]. Washington University will fill the subsequent algorithm validation gap by contributing to the project an EHR-generated validation data set spanning the same time period that will be used to validate mortality prediction algorithms developed on University of Washington data.  The validation dataset from Washington University will be a synthetic dataset that provides the volume and accuracy of actual EHR data but also 100% protects sensitive patient information.  The validation dataset from Washington University will comprise data which follow the OMOP v5.0 common data model and thus will be compatible with the data source used for algorithm development. 

The research design is agile and scalable to other Challenges and outcomes, as distinct validation datasets can be generated in response to features of algorithms that need to be validated. As such, Washington University will also provide expertise on defining the Challenge and evaluating the outcome. Drs. Foraker and Maddox will determine best practices and clinical utility for building and validating each prediction model. An example prediction algorithm for this Challenge would be defined as identifying factors that predict a patient dying within the subsequent 6 months.

Methodology

The synthetic data will be created by the Washington University team using a tool called MDClone. Washington University’s Institute for Informatics and MDClone (https://www.mdclone.com/) have a strategic partnership. The MDClone tool as deployed at Washington University uses input from source data that is composed of deidentified EHR data.  After extracting source data based on criteria entered by the researcher, MDClone creates a synthetic dataset that is statistically identical to a data set composed of the original data. The synthetic data can be analyzed as if it were original data but is 100 percent unidentified, non-human subject data.  These data sets can be directly analyzed by Challenge participants, or Washington University can run their algorithms on data sets generated by MDClone.

For the purposes of the Challenge, Dr. Foraker and her postdoctoral fellow (Dr. Guo) will be responsible for generating validation data sets for the Challenge participants on which algorithms will be validated. They will also provide assistance to Challenge teams to conduct model validation and run queries if necessary. Dr. Maddox and Ms. Fretty will additionally track clinical utility and model performance, as described in the next section.  They will also connect with other clinical partners among the various CTSAs involved in the Challenge to determine the best use in a care delivery setting.  Finally, they will work with this clinical group to design future use cases and predictive models using the Challenge methodology.

Analytic Approaches  

Model-building and validation approaches are expected to include a multi-pronged approach, using logistic regression: 1) a model including demographic information (age, gender, ethnicity) only; 2) a model composed of demographic information plus 4 diseases of interest, due to their expected contributions to mortality within the specified time frame (cancer, coronary heart disease, type 2 diabetes, and chronic obstructive pulmonary disease); and 3) a model comprising demographic information and the top 10 conditions (selected by a chi-square scoring function).

Expected Outcomes

The mortality prediction algorithms accepted to the Challenge will be evaluated against data that correctly validates their accuracy while patient PHI is protected. The primary comparison metric used to assess the predictive capabilities of Challenge models will be to assess the area under the receiver operator curve (AUROC) which will enable us to compare results across different cohorts and modeling strategies. A secondary performance metric will include the area under the precision-recall curve (AUPR) which will assist us in managing the unbalanced data sets used in this Challenge.
 
Deliverables
•	A validation dataset that can use to validate mortality prediction algorithms.  The dataset will be a synthetic dataset that provides the volume and accuracy of actual EHR data but also 100% protects sensitive patient information.   
•	Contribution to defining the Challenge. 
•	Participation in evaluating the outcome
•	Convening of clinical expertise among the participating CTSAs
•	Design of additional predictive model use cases

Timeline (monthly)
Due Date	Milestone	Status
Aug 31 2019	Complete identification of the data fields required for the synthetic data set.    Determine all data selection criteria (EHR date range, Patient age range etc.)   	Not Started
Sept 30 2019	Produce the synthetic data file.	Not Started
Oct 31, 2019	Using a sample algorithm(s) validate that the synthetic dataset is producing expected results	Not Started
Dec 31 2019	Create and execute a use case that compares Algorithm results produced from synthetic data to results produced from University of Washington data.	Not Started
Oct 2019	Participate in defining the Challenge	Not Started
March 2020	Participate in evaluating algorithms submitted to the challenge	Not Started



Budget
A separate Excel document contains our proposed budget information.
