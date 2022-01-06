# Room Occupancy Detection
## Overview
- Selected Topic: Room occupancy detection for home or office using a variety of sensors such as temperature, motion, and humidity.  Datasets from multiple experiments have been captured and provide on Kaggle and the UCI machine learning datasets site.
- Reasons for topic selection: The domain (people in a room) is something everyone can easily understand, the type of analysis needed (binary classification) is one of the skills we learned in this course, and availability of multiple, well formed datasets.  Potential use cases for occupancy detection include: 
    - Room cleaning after occupancy such as in clinics, conference rooms, and other public settings; particularly during the COVID pandemic
    - Energy efficiency via room temperature management based on occupancy and turning off lights and other electrical devices    
- Description of Data: Each dataset contains time series sensor telemetry from humidity, temperature, CO2, light and other sensors placed in a room.  The data was collected both when someone is present in the room and when the room is not occupied.  Each sensor reading is labeled with room occupancy ground truth and all sensors report their reading with a floating point value.
- Questions we hope to answer:
    - Of the three datasets we selected, which one provides the best performance for accurate room occupancy detection?
    - What is the best occupancy detection performance that we can achieve given the available data using machine learning classification algorithms?
- We will use the Random Forest algorithm from scikit-learn to analyze the data
- Communications Protocols: 
    - Coordinated schedules via Slack channel. 
    - Microsoft Teams as a virtual meeting platform 2x/week.
    - Utilized class time via Zoom breakout room to work on project
    - Shared resources via GitHub
