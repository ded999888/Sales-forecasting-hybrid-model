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

# Гибридная модель LSTM + Random Forest.
Проект представляет собой гибридный подход к прогнозированию продаж на основе методов машинного обучения.
Целью работы являлось повышение точности прогноза спроса за счёт интеграции управляемых бизнес-факторов в модель прогнозирования.

Интегрируемые факторы.
В модели учитываются:
•	динамика цены;
•	промо-активность;
•	сезонность;
•	календарные и праздничные эффекты.

Бизнес-контекст.
Точное прогнозирование продаж критически важно для:
•	планирования спроса;
•	оптимизации запасов;
•	формирования ценовой стратегии;
•	оценки эффективности маркетинговых инициатив.
Традиционные модели прогнозирования часто не учитывают управляемые факторы (цену, промо-кампании), что снижает их применимость для управленческих решений. Данный проект направлен на устранение этого ограничения.

Подход к моделированию.
Система прогнозирования построена на гибридной архитектуре:
LSTM (Long Short-Term Memory).
•	выявление временных зависимостей;
•	извлечение сезонных паттернов;
•	моделирование динамики спроса;
Random Forest (в качестве ансамблевого слоя).
•	усиление нелинейных взаимодействий факторов;
•	повышение устойчивости прогноза;
•	снижение риска переобучения.

Обработка данных.
•	One-Hot Encoding категориальных переменных.
•	масштабирование признаков.
•	использование скользящего временного окна (7-дневные последовательности).
•	прогнозирование по нескольким брендам.

Оценка качества модели.
Качество прогнозирования оценивалось с использованием метрик:
•	MAE.
•	RMSE.
•	R².
Проведено сравнение базовой модели LSTM и гибридной архитектуры LSTM + Random Forest.

Возможности системы.
•	прогнозирование продаж на 7 дней вперёд.
•	прогнозирование на уровне отдельных брендов.
•	экспорт результатов в формат Excel.

Бизнес-ценность.
Проект демонстрирует, как методы машинного обучения могут поддерживать управленческие решения за счёт:
•	количественной оценки эффекта промо-активностей.
•	повышения надёжности планирования продаж.
•	формирования data-driven ценовой стратегии.

Возможные направления развития
•	кросс-валидация для временных рядов.
•	применение моделей градиентного бустинга.
•	разработка production-пайплайна.
•	интеграция с BI-панелями.

Используемый стек технологий.
•	Python.
•	Pandas / NumPy.
•	Scikit-learn.
•	TensorFlow / Keras.
•	Matplotlib.
