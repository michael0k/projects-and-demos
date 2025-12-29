## Visualizing NYC Ranger Data With Python

Exploratory data analysis and visualization of NYC Park Ranger wildlife response data using Python.

### Overview
- Goal: Analyze wildlife call data to identify patterns in animal condition, ranger response, and borough-level trends.
- Stack: Python (pandas & matplotlib), Jupyter Notebook, DB Browser for SQLite, and Tableau.

### Dataset
- Source: NYC Open Data - Park Ranger Animal Condition and Response dataset.
- Included: Cleaned and processed data used for analysis.

### Methods
- Cleaning: Datetime parsing, category standardization, handling nulls, and basic filtering.
- Analysis: Aggregations by borough, species status, animal condition, and response type.
- Visualization: Bar charts, area charts, heat maps, and distribution plots highlighting ranger actions and conditions.

### Results
- Most ranger responses involve healthy or injured animals.
- Manhattan and Brooklyn account for the highest volume of ranger calls.
- Clear variation in ranger actions depending on reported animal condition.
- Visual summaries embedded in the project site.

### How to Run
1. Download the NYC Ranger dataset from NYC Open Data.
2. Run the data cleaning and analysis notebook.
3. Render plots locally or export visuals for static hosting.

### Structure
- `data/`: datasets (raw and cleaned)
- `notebooks/`: analysis and visualization
- `visualization/`: exported charts and assets


### Next
- Add geospatial mapping of ranger responses.
- Build an interactive dashboard.

### License
GNU GPL v3
