# Seminar-Details

## Introduction 
- Cyber Attacks affecting elements of Electric Vehicles including battery life , motor drives , IoT embeded systems .
- Supervisory Control and Data Acquisition , Industrial Control System .
- General algorithm cannot detect attacks on EVs with satisfied output .
- Attackers gain illegal access on electric drive system we can detect signal hampering at early stage and prevent it .

## Literature Survey
- New type of architecture system presented importance of battery health in EVs and the algorithms for optimizing it .
- Data integrity attacks on ESDs and AGC operation played vital role and caused more impact on power train .
- Analysis of major engine components and elaboration of risk factors associated with it .

## Motivation 
- Need to work with faults in electric drives and IoT enabled system of Electric Vehicles.
- There are various vehicle network protocols, including Media Oriented
Systems Transport  (MOST) , Local Interconnect Network (LIN), FlexRay, and
CAN Flexible Data-Rate (CAN FD) can be used in electric vehicles which will give an advantage to build system .



## System Architecture 


       -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -
       -                    -          -                    -          -                       -          -                          -          -                          -
       -       INPUT        -  ----->  -        LSTM        -  ----->  - Fully Connected Layer -  ----->  -         Softmax          -  ----->  -          Classify        -
       -                    -          -                    -          -                       -          -                          -          -                          -
       -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  - 


                                                                       NEURAL NETWORK ARCHITECTURE


  ## Problem Statement 

  - Detect Faults in 3 Major Parts of EVs
  - 1. Sensors
    2. Controllers
    3. Communication Channels ( Energy Management System )
   
  ## Methodology 
  - Support Vector Machine is Supervized Machine Learning Algorithm used for Classification and Regression .
  - Technique used is Kernal Trick to transform the data based on transformations finds an optimal boundary between the possible outputs .

  - Confusion Matrix :


                            Normal      Attack                                                           Normal        Attack
                          -  -  -  -  -  -  -  -  -                                                   -  -  -  -  -  -  -  -  -
                 Normal   -   9177    -    13     -                                           Normal  -   9188    -    2      -
                          -  -  -  -  -  -  -  -  -                                                   -  -  -  -  -  -  -  -  -                 
                 Attack   -   1273    -    1074   -                                           Attack  -   49      -    2298   -          
                          -  -  -  -  -  -  -  -  -                                                   -  -  -  -  -  -  -  -  -

                                  Pure Data                                                                Physics- Guided

   - LSTM Network Accuracy - 98.4 %

   ## Networks Protocols

   - Media Oriented System Transport
   - Local Interconnect Network
   - Flexray

  ## Conclusion
   - With the use of currently available tools and techniques, future study on the security of data and communication in the EVs infrastructure can be conducted. The machine learning           algorithm technique proposed can predict attacks at early stage from getting it to severe .

  
