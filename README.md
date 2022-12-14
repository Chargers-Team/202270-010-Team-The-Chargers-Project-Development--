DEAN 690 Fall Project Professor: Brett Berlin Organization: GMU Center for Air Transportation Systems Research (CATSR) Project POC(s): Dr. Lance Sherry, Director CATSR, lsherry@gmu.edu and Jomana Bashatah, jbashata@gmu.edu 

Team Chargers has the task of working with Standard Operating Procedures from the airline industry, specifically to solve the following question. 

For the airline industry’s Standard Operating Procedures (SOPs) defined as Flight Crew Operators Manuals (FCOM)/ Airplane Flight Manual (AFM) can Natural Language Processes tools be implemented to classify and detect the 4 main activities already preestablished as Action, Decision-Action, Action-Waiting-Verification, and Decision-Action with Waiting-Verification? 

Problem Scope 

Standard Operating procedures (SOPs) are documented step by step instructions followed by human operators which are essential to perform critical, repetitive, complex, and emergency-related tasks as efficiently as possible. Due to these aspects and since SOPs play an important role in any type of process, it's critical to find a systematic method to quantify their information. Nowadays SOPs are created manually by a subject matter expert in the field, which is a time-consuming and tedious process to follow. In addition to this, these documented instructions usually are in formats that are difficult to systematically extract any type of data from. The challenge of the project will be to extract useful statistical information from SOPs to help future research on their possible automation when created to reduce costs, improve training and as well most important increase safety and reduce human error. The methodology and logic of the project are going to e applicable to any SOPs, however, due to time constraints our focus is going to be based in the airline industry defined by the operation manuals used by pilots like the Flight Crew Operators Manual (FCOM) or Airplane Flight Manual (AFM). 

Github folder structure 

Documents: Contains all algorithm comparison the team did before picking the best performing one. 

Python: Contains python scripts used for building NLP model and testing. 

Data: Contains all annotated data collected from UBIAI tool. Files are cleaned after downloading from UBIAI before being used in NLP model. 

Model_results: Contains model results we get after running the model. 

Visualizations: Contains all visualizations used for report. The report explains the visuals we get when running the model and sequential analysis. Test: 

Data 

The dataset used for this model was collected from SOPs annotated by Jomana and SOPs annotated by our team. We cleaned the data after annotating and replaced some airline acronyms or short words, so the algorithm does not get confused with other words. 
