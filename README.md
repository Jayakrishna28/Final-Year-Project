# Final-Year-Project
🚀 Project Showcase: Artificial Intelligence Applications in Power Systems

By A. S. Venkat Srinivas, B. Kowshik, A. Pavan, K. Jaya Krishna(Myself), K. Vikram Siddhardha | B.Tech, EEE – 2025 | Sri Venkateswara University College of Engineering, Tirupati

🔗 Supervised by Prof. M. Damodar Reddy, Department of EEE

As the global energy ecosystem evolves with the integration of renewables, smart metering, and growing consumption demands, the need for intelligent, adaptive, and automated systems in power management has never been more pressing. Recognizing this, we embarked on our final-year B.Tech project titled:

"Artificial Intelligence Applications in Power Systems"
A practical demonstration of how AI and ML can transform legacy electrical infrastructure into robust, smart, and future-ready systems.

🔍 Objective
Our project explores four critical applications of Artificial Intelligence in the energy sector:

Power Theft Detection

Load Forecasting

Load Balancing

Load Outage Prediction

Each module was independently designed, developed, and integrated using synthetic and real-world datasets, evaluated against standard ML/DL models like Random Forest, Isolation Forest, SVM, LSTM, and Prophet.

📌 Highlights
1. Power Theft Detection
Problem: Electricity theft contributes significantly to Non-Technical Losses (NTLs), especially in developing countries.

Our Solution:

Developed both supervised (Random Forest, SVM) and unsupervised (Isolation Forest) models.

Trained on synthetic datasets mimicking real smart meter data.

Identified anomalous consumption patterns indicating potential theft.

Visualized with Power BI and Python plots for intuitive inspection.

Results:

Random Forest achieved over 93% accuracy.

Detected anomalies like high consumption with suspicious voltage-current mismatches.

🧠 Impact: A scalable detection framework that utilities can deploy alongside smart meters to reduce revenue loss.

2. Load Forecasting
Problem: Grid stability and economic operation depend on precise demand forecasting.

Our Solution:

Used LSTM for deep time-series learning and Prophet for trend-seasonality modeling.

Feature-rich dataset: weather, time-of-day, solar irradiance, etc.

Compared performance with Random Forest (ML baseline).

Results:

LSTM outperformed with MAE: 19.6 kWh, MAPE: 3.5%

Accurately captured seasonal fluctuations and peak hour surges.

📈 Impact: Helps in energy planning, scheduling generation, and balancing intermittent renewable input.

3. Load Balancing
Problem: Imbalanced load can damage transformers, increase losses, and cause voltage instability.

Our Solution:

Applied Q-Learning to optimize load dispatch actions based on grid states.

Integrated Fuzzy Logic for rule-based decision making.

Used Genetic Algorithms (GA) for load pattern optimization.

Results:

Overload events reduced by 67% using Q-learning.

GA minimized transmission losses by 12%.

Visual dashboards highlighted real-time surplus/deficit zones.

🛠️ Impact: A decision-support engine for Distribution Control Centers and microgrid operators.

4. Load Outage Prediction
Problem: Unexpected outages lead to economic and operational disruptions.

Our Solution:

Trained models like Random Forest and Isolation Forest on enriched data: transformer temperature, current-voltage deviations, weather, fault history.

Engineered features like ΔI/Δt, time since last maintenance, and equipment stress indexes.

Results:

Achieved 90%+ precision in outage prediction.

Enabled preventive maintenance by flagging at-risk components.

💡 Impact: Moves utilities from a reactive to a proactive maintenance approach—key for smart grid reliability.

🧰 Tools & Technologies
Languages: Python

Libraries: Scikit-learn, TensorFlow/Keras, Prophet, Seaborn, Matplotlib

Platforms: Jupyter Notebook, Power BI

Algorithms: Random Forest, Isolation Forest, SVM, LSTM, Prophet, Q-Learning, Fuzzy Logic, Genetic Algorithms

📊 Evaluation Metrics
Each module was evaluated using relevant metrics such as:

Classification: Accuracy, Precision, Recall, F1-Score, ROC-AUC

Forecasting: MAE, RMSE, MAPE

Optimization: Loss reduction %, load variance

Visualization: Time-series plots, heatmaps, confusion matrices

💭 Key Takeaways
AI is no longer a theoretical tool—it is practically deployable in utility operations.

Smart grid resilience can be significantly enhanced through proactive, AI-driven systems.

With real-time data integration, these models can scale into full-fledged intelligent grid systems.

📌 Challenges Faced
Limited access to real-world smart meter data (solved via synthetic data generation).

Need for modular, interpretable ML models for field deployability.

Ensuring low-latency inference for real-time applications like load balancing.

🚀 Future Scope
Integration with SCADA and IoT sensors for real-time grid interaction.

Blockchain-based secure energy sharing among microgrids.

Deployment on edge devices for localized prediction and action.

Hybrid DL models combining CNN+LSTM for spatio-temporal insights.
