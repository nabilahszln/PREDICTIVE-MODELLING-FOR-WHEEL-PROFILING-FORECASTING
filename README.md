📌 Project Overview:

This pair project focuses on predictive maintenance for the MRT Kajang (KGL) Line by forecasting and predicting train wheel profiling and Mean Time Before Failure (MTBF) using deep learning and time-series forecasting models.
The project supports Malaysia’s New Industrial Master Plan 2030 (NIMP 2030), especially the mission of building a digitally vibrant nation through advanced analytics and AI-driven maintenance systems.

🎯 Problem Statement:

KGL experiences increasing passenger demand, causing train wheels to wear faster. Worn wheels can lead to:
- Increased vibration and noise
- Passenger discomfort
- Train downtime
- Reduced fleet availability
- Service delays due to disrupted headway
Currently, wheel maintenance forecasting is done manually using Microsoft Excel, which is time-consuming and less accurate.
This project introduces predictive analytics to automate wheel maintenance forecasting and improve operational efficiency.

📊 Objectives:

- To identify features that will give best separation failure and non-failure wheels using 
LDA.
- To forecast and evaluate wheel profiling and replacement using Holt's Winter method 
and GRU model performance with MTBF prediction. 
- To create a graphical user interface (GUI) based on the best-performing model so the 
employee can easily see the predicted month and year for wheel replacement and 
profiling. 

🚄 Train Structure:

Each MRT train consists of:
- Motor Car 1 (M1)
- Trailer Car 1 (T1)
- Trailer Car 2 (T2)
- Motor Car 2 (M2)
Each car contains:
- 2 bogies
- Each bogie has 2 wheelsets
  
Selected Trains:

8 trains were selected for analysis based on maintenance history and availability of complete records:
T01, T05, T25, T45, T46, T55, T57 & T58

⚙️ Failure Criteria:

A wheel is considered failed when:
- Wheel flange thickness < 27.5 mm
- Wheel diameter < 775 mm
- Or both conditions occur simultaneously
  
🖥️ GUI System:

A user-friendly Graphical User Interface (GUI) using Tkinter was developed to display:
- Predicted wheel replacement dates
- Predicted wheel profiling schedules
- Maintenance forecasting results
This helps maintenance teams make faster and more accurate decisions.

🛠️ Technologies Used:

-RStudio
-Python
-Pandas
-NumPy
-Scikit-learn
-TensorFlow / Keras
-Matplotlib
-Tkinter


