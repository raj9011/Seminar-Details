# Seminar-Details

# Introduction 
- Cyber Attacks affecting elements of Electric Vehicles , including battery life , motor drives , IoT embeded systems ..
- Supervisory Control and Data Acquisition , Industrial Control System .

# Literature Survey
- New architecture and methodology proposed to detect cyber attacks in Electric Vehicles .

# Motivation 
- Need to work with faults in Electric Vehicles in less time .


# System Architecture 


       -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -
       -                    -          -                    -          -                       -          -                          -          -                          -
       -       INPUT        -  ----->  -        LSTM        -  ----->  - Fully Connected Layer -  ----->  -         Softmax          -  ----->  -          Classify        -
       -                    -          -                    -          -                       -          -                          -          -                          -
       -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  -          -  -  -  -  -  -  -  -  -  - 


                                                                       NEURAL NETWORK ARCHITECTURE


  # Problem Statement 

  - Detect Faults in 3 Major Parts 
  - 1. Sensors
    2. Controllers
    3. Communication Channels ( Energy Management System )
   
  # Methodology 
  - Support Vector Machine is supervized Machine Learning Algorithm used for Classification and Regression .
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

    # Networks Protocols

    - Media Oriented System Transport
    - Local Interconnect Network
    - Flexray

    # Conclusion
    - With the use of currently available tools and techniques, future study on the security of data and communication in the EVs infrastructure can be conducted. The machine algorithm        technique proposed can predict attacks at early stage from getting it to severe .

  
