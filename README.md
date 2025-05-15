# Crime_Analysis
This project implements a data-centric approach to analyze historical crime patterns and forecast future incidents across Toronto, aiming to enhance public safety and inform data-driven decision-making. By integrating crime records from the Toronto Police Service (2014–2024) with historical weather data from NOAA APIs, we construct a robust dataset that captures both temporal and environmental influences on criminal activity.

We employ a hybrid modeling pipeline combining classical statistical methods (SARIMA), ensemble learning techniques (Random Forest, XGBoost), and deep learning architectures (LSTM networks). Our results indicate that LSTM models outperform others in capturing complex temporal dependencies and non-linear trends in monthly crime occurrences. Although Graph Neural Networks (GNNs) were proposed to explore spatial interdependencies, they remain a component of future development.

Key deliverables include:

A 3-year forecast of category-wise crime trends using LSTM-based models.

An interactive web-based heatmap dashboard (built with Folium) visualizing spatial crime density by temperature bands and crime types.

Preliminary correlation insights between weather and crime seasonality.

Future enhancements aim to incorporate socio-economic indicators and GNN-based spatial models to improve causal inference and prediction accuracy. The system provides an actionable tool for urban planners, law enforcement, and policy-makers to anticipate and mitigate urban crime more effectively.
