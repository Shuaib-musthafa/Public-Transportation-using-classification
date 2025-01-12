**Public Transport Schedule Optimization using Demand Prediction**

This project aims to optimize public transport schedules by predicting demand levels (Low, Medium, High) for various time slots based on factors such as weekdays, weather conditions, and passenger count. The model utilizes a logistic regression algorithm to classify demand levels, helping transit systems make more efficient decisions regarding vehicle dispatch, scheduling, and resource allocation.

### Key Features:
- **Data Preprocessing:** Handling and scaling data to improve model performance.
- **Model Training:** A custom-built logistic regression model for multiclass classification.
- **Prediction:** Predicting demand levels for a given time slot based on real-time user inputs (e.g., weekday, weather, passenger count).
- **Deployment:** Saving and loading the model using pickle, with an easy-to-use command-line interface for predictions.
- **Real-World Application:** The model can be adapted to optimize public transport schedules and improve operational efficiency.

### Technologies Used:
- Python
- Numpy
- Pandas
- Scikit-learn (for modeling)
- Pickle (for saving/loading models)

### Instructions to Run:
1. Clone the repository to your local machine.
2. Install the necessary dependencies.
3. Run the script to predict demand levels for specific time slots.
4. (Optional) You can modify the dataset or experiment with different machine learning algorithms.

### Future Work:
- Extend the model to consider more variables such as holidays, traffic conditions, or historical demand.
- Build a user-friendly web application (e.g., using Streamlit) for real-time predictions.
