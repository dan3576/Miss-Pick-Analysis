# Miss-Pick-Analysis (Exploratory Data Analysis)

## Objective
Analyze warehouse picking errors (misspicks) to identify patterns and root causes, helping to improve operational accuracy. Consequently improving order accuracy, customer satisfaction and reducing operational costs
 
## Tools Used
- Python - Main data analysis
- SQL - Data extraction
- Jupyter Notebook - Visualisation of findings

## Deliverables 
- Jupyter Notebook with all analysis
- Visualisations with heatmaps and charts
- Insight Report with reccomendations of strategy

## Questions Answered
1. Which products are most often miss-picked?
2. Are slow-moving items miss-picked more often than fast movers?
3. Which pickers make the most picking mistakes?
4. Do pickers make more mistakes when handling slow, medium, or fast-moving products?
5. Does the time of day affect how often pickers make mistakes?
6. Do larger picking waves lead to more picking mistakes?
7. Are some warehouse locations more prone to picking mistakes than others?
8. Are picking mistakes mainly caused by how products are stored or by picker perform

## Data Source
- Dataset: Simulated warehouse picking data based on realistic warehouse operations and picking processes
- Description: The dataset represents customer orders, picking waves, product information, storage locations, and picker activity within a warehouse environment.
- Key data points include:
- Order number and picking wave
- Product reference and product speed (fast / medium / slow)
- Storage location and warehouse coordinates
- Picker ID
- Date and time of each pick
- Expected vs picked quantities (used to identify picking errors)

Note: Picking errors are not provided directly in the data. Miss-picks are identified by comparing what should have been picked with what was actually picked, reflecting how errors are typically identified in real warehouse systems.
