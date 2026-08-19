# Dashboard Exporing the Effects of AI on Human Cognition
Interactive Dash dashboard exploring AI dependency, cognitive outcomes, professions, scenarios, and future outcomes.

## Project Overview
This project uses the "AI Impact on Human Mental Growth" dataset to explore relationships between artificial intelligence dependency on human cognitive outcomes, professions, future scenarios, and years.

The dashboard was developed using Python, Plotly, and Dash and provides interactive visualizations that allow users to explore different aspects of the dataset.

## Dashboard Visualizations

### 1. AI Dependency and Cognitive Outcomes
This graph examines the relationship between AI Dependency Score and a selected cognitive measure under different future scenarios.
Users can select:
- A cognitive measure
- A future scenario

### 2. AI Dependency by Profession
This heatmap compares average AI dependency across professions for a selected future scenario.
Users can select a scenario to explore differences in AI dependency across professions.

### 3. Future Outcomes by Scenario and Year
This graph shows the distribution of future outcomes across scenarios for a selected year.
Users can use the year slider to explore changes over time.
The outcome classifications are provided in the dataset and include:
- Positive Growth
- Stagnant / Moderate
- Cognitive Decline Risk

## Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Plotly
- Dash

## Installation
Install the required Python packages using:
```bash
pip install -r requirements.txt

## Running the File
1. Download or clone this repository.
2. Install the required packages using the command above.
3. Open `AI_Dependency_Dashboard.ipynb` in Jupyter Notebook or JupyterLab.
4. Make sure the dataset file is in the same directory as the notebook.
5. Run the notebook cells in order.
6. Run the final cell to launch the Dash dashboard.
