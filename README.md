# Algerian-Forest-Fire


The Algerian Forest Fires Dataset contains meteorological and fire occurrence data collected from two regions in Algeria: Bejaia and Sidi Bel-Abbes.

The aim of this assignment is to process and clean the dataset, generate visualizations, and derive insights from the Algerian forest fire dataset by analyzing the Fire Weather Index (FWI). This analysis will involve utilizing Linear Regression and its regularization techniques. Additionally, the assignment will include performing cross-validation and hyperparameter tuning to evaluate the model's performance. After developing the model, you will create pickle files and test the model on unseen data.


📊 Dataset Characteristics:
Instances: Around 244 records

Features: Includes temperature, humidity, wind, rain, and several Fire Weather Index (FWI) system components:

Temperature — Ambient temperature in °C

RH — Relative humidity (%)

Rain — Rainfall in mm

FFMC — Fine Fuel Moisture Code (related to surface litter flammability)

DMC — Duff Moisture Code (moisture in loosely compacted organic layers)

DC — Drought Code (deep organic layer dryness / long-term drought index)

ISI — Initial Spread Index (potential fire spread rate)

BUI — Build-Up Index (amount of fuel available for combustion)

FWI — Fire Weather Index (final fire risk score from the Canadian FWI system)

Region — Geographic region indicator (e.g., 0 or 1)

Target: A binary label indicating fire occurrence (Classes: fire or not fire)

