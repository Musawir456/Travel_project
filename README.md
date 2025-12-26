# Travel_project
# Travel_project

A data analysis project on Indian travel destinations using Python, Pandas, and Seaborn.  
The goal is to explore the dataset, calculate popularity statistics, visualize trends, and build a basic recommendation function.

## Dataset

- File: `Expanded_Destinations.csv`
- Columns:
  - `DestinationID` – Unique ID for each row
  - `Name` – Destination name (e.g., Taj Mahal, Goa Beaches)
  - `State` – Indian state / region
  - `Type` – Category (Historical, Beach, City, Nature, Adventure)
  - `Popularity` – Popularity score (float)
  - `BestTimeToVisit` – Best time range to visit (e.g., Nov-Feb, Apr-Jun)

## Technologies Used

- Python 3
- Jupyter Notebook (VS Code)
- Pandas – data loading and analysis
- Matplotlib & Seaborn – visualizations

## Main Features

1. **Data loading & cleaning**
   - Load CSV using Pandas
   - Convert `Popularity` to numeric
   - Remove rows with missing popularity values

2. **Analysis functions**
   - Average popularity by destination (`average_popularity_by_destination`)
   - Average popularity by state (`average_popularity_by_state`)
   - Average popularity by type (`average_popularity_by_type`)
   - Top N destinations by popularity (`top_n_destinations`)

3. **Visualizations**
   - Bar chart of top destinations by average popularity
   - Bar chart of average popularity by state
   - Bar chart of average popularity by type

4. **Simple recommendation**
   - Function `recommend_destination(df, best_time=None, dest_type=None, top_n=5)`
   - Filters destinations based on:
     - `BestTimeToVisit` (e.g., `Nov-Feb`)
     - `Type` (e.g., `Historical`, `Beach`, `Adventure`)
   - Returns top N destinations sorted by popularity

## How to Run

1. Clone the repository:

2. (Optional) Create and activate a virtual environment.

3. Install dependencies:

4. Open the project in VS Code or Jupyter and run:
- `project_1.ipynb` notebook  
or
- `main.py` (if present) using:
  ```
  python main.py
  ```

## Project Structure

- `Expanded_Destinations.csv` – dataset
- `project_1.ipynb` – main analysis notebook
- `README.md` – project description

## Future Improvements

- Convert the notebook into a clean Python script (`main.py`)
- Add an interactive CLI or Streamlit web interface
- Add more metrics (median popularity, distribution plots)
- Improve recommendation logic with more filters

## Author

- **Your Name** – Data / IoT student interested in Python, data analysis, and networking.
