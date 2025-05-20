✈️ Flight Delay Analysis & Prediction (2018–2024)

This project analyzes over **580,000 US domestic flight records** between 2018 and 2024 to uncover trends in delays and build a predictive model that forecasts whether a flight will be delayed.

 📊 Project Highlights

- ✅ Cleaned and analyzed a dataset with 120+ features and 580k+ entries.
- 📈 Performed **exploratory data analysis (EDA)** to identify key delay patterns by airline and route.
- 🤖 Built a machine learning model to **predict flight delays** using features like departure time, airline, and delay history.
- 📉 Identified that **late aircraft** and **carrier-related issues** were among the top contributors to delays.



 ✈️ Average Delay by Airline (Sample)

| Airline | DepDelay | ArrDelay | CarrierDelay | WeatherDelay | LateAircraftDelay |
|--------|----------|----------|---------------|---------------|--------------------|
| AA     | 19.63    | 16.28    | 24.90         | 10.16         | 38.10              |
| F9     | 18.85    | 14.72    | 23.00         | 3.51          | 44.91              |
| B6     | 19.15    | 13.52    | 31.23         | 2.80          | 28.39              |
| HA     | 9.95     | 10.66    | 19.88         | 4.06          | 17.81              |

Column Definitions

- **DepDelay**: Average delay in scheduled departure time.
- **ArrDelay**: Average delay in actual arrival time.
- **CarrierDelay**: Delay due to issues under the airline’s control (e.g., maintenance or crew).
- **WeatherDelay**: Delay caused by weather conditions (e.g., storms, fog).
- **LateAircraftDelay**: Delay because the incoming flight (using the same aircraft) arrived late.
---

📉 Model Performance

Class 0 (On-Time):
- Precision: 0.79
- Recall:    0.89
- F1-score:  0.84

Class 1 (Delayed):
- Precision: 0.45
- Recall:    0.27
- F1-score:  0.34

Macro Avg:
- F1-score: 0.59

🔧 Tools & Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, Seaborn)
- **Google Colab** for cloud-based execution
- **GitHub** for version control and project showcasing

📁 Dataset Source

- US Domestic Flight Data (2018–2024)
- Source: Kaggle / U.S. Department of Transportation (if applicable)

🚀 How to Run

1. Mount Google Drive in Colab
2. Load and preprocess the dataset
3. Run the EDA and visualization sections
4. Train the predictive model
5. Evaluate performance using metrics like accuracy 

---

Feel free to clone, use, and build upon this project!

