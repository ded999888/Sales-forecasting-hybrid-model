# Sales-forecasting-hybrid-model
This project presents a hybrid machine learning approach to sales forecasting. The objective was to improve demand prediction accuracy by incorporating controllable business drivers into the forecasting model.
Multi-Factor Sales Forecasting. Hybrid LSTM + Random Forest Model

The solution integrates:
•	Price dynamics.
•	Promotion activity.
•	Seasonality.
•	Holiday effects.

Business Context.
Accurate sales forecasting is critical for:
•	Demand planning.
•	Inventory optimization.
•	Pricing strategy.
•	Promotion effectiveness evaluation.
Traditional models often ignore controllable factors such as pricing and marketing campaigns.
This project addresses that gap.

Modeling Approach. 
The forecasting system combines:
-LSTM (Long Short-Term Memory).
•	Captures temporal dependencies.
•	Extracts seasonality patterns.
•	Learns demand dynamics.
-Random Forest (Stacked Layer).
•	Enhances nonlinear factor interactions.
•	Improves predictive robustness.

Data Processing.
•	One-Hot Encoding of categorical variables.
•	Feature scaling.
•	Sliding time window (7-day sequences).
•	Multi-brand forecasting.

Model Evaluation.
Models evaluated using:
•	MAE.
•	RMSE.
•	R².

Comparison performed between LSTM and hybrid LSTM + Random Forest architecture.
Forecasting Capability.
•	7-day forward sales prediction.
•	Brand-level forecasting.
•	Export of forecast results to Excel.

Business Value.
The project demonstrates how machine learning can support managerial decision-making by:
•	Quantifying promotion impact.
•	Improving sales planning reliability.
•	Supporting data-driven pricing strategy.

Future Improvements.
•	Time-series cross-validation.
•	Gradient boosting models.
•	Production deployment pipeline.
•	Integration with BI dashboards.

Tech Stack.
•	Python.
•	Pandas / NumPy.
•	Scikit-learn.
•	TensorFlow / Keras.
•	Matplotlib.
