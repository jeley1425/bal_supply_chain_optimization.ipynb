Global Supply Chain Disruption & Fleet Routing Optimization Engine

Business Case Overview
Global shipping corridors are highly susceptible to non-linear operational drag caused by weather anomalies, port backlogs, and heavy cargo payloads. Unmitigated delays trigger strict contractual delivery penalties ($250 per hour past a 40-hour threshold) and disrupt downstream warehouse fulfillment timelines. This project implements a multi-layer deep learning neural network regression pipeline that models route-level delays down to the exact hour and couples it with a prescriptive cost optimization system to automate fleet diversion actions before catastrophic capital penalties hit the operating budget.

Technical Architecture & Workflow
The system utilizes a 5-phase data infrastructure lifecycle built in Python:

- Phase 1: Geospatial Ingestion Registry – Formatted a data engine processing 800 international freight profiles spanning route tracking, transit vectors, and vehicle types.
- Phase 2: Friction Feature Engineering – Synthesized multi-variable bottlenecks into a composite Supply Chain Friction Index alongside vectorized contractual penalty financial metrics.
- Phase 3: Supervised Deep Learning (Multi-Layer Perceptron) – Implemented a multi-layer neural network regressor (MLPRegressor) to map continuous features directly into high-accuracy transit hour forecasts, achieving an R² Score of approximately 0.96.
- Phase 4: Prescriptive Operational Optimization – Engineered a risk-triage automation algorithm that sets an executive financial ceiling ($5,000) to isolate shipments crossing critical risk thresholds for tactical rerouting.
- Phase 5: Executive Dashboard Synthesis – Visualized high-dimensional shipment clusters mapping environmental friction scores against neural timeline forecasts.

Model Performance & Prescriptive Triage Outputs
The trained pipeline evaluated 160 unseen cargo shipments in the production test split, generating the following automated operational actions:
- MAINTAIN CURRENT SHIPMENT CORRIDOR: 111 Shipments (Low financial risk exposure)
- CRITICAL: TRIGGER IMMEDIATE FLEET DIVERSION: 49 Shipments (High-risk allocations crossing the $5,000 penalty threshold)

By isolating these 49 critical routes, the optimization matrix allows logistics directors to target fleet intervention budgets strictly where capital loss is guaranteed, preserving infrastructure capital.

Tech Stack Used
- Language: Python 3
- Environment: Google Colab / Jupyter Systems
- Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
