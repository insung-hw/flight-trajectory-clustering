# Flight Trajectory clustering

## 🚀 Project Overview
This project analyzes flight path data from FlightAware, using the HDBSCAN algorithm.
The goal of this project is to identify robust flight paths which is less affected by outliers and to deeply understand how HDBSCAN works.

## 🛠️ Tech Stack
| Category | Tools |
|-----------|--------|
| Language | Python 3 |
| Data Processing | Pandas, NumPy |
| Clustering | HDBSCAN, SciPy |
| Visualization | Matplotlib, Folium |
| Environment | Kaggle |

## 🧩 System Architecture
Here is a simple diagram of how the system works:

          +------------------------+
          |    Raw Flight Data     |
          +-----------+------------+
                      |
                      v
          +------------------------+
          |     Preprocessing      |
          |    - Cleaning          |
          |    - Coordinate Norm.  |
          +-----------+------------+
                      |
                      v
          +------------------------+
          |     HDBSCAN Model      |
          +-----------+------------+
                      |
                      v
          +------------------------+
          |     Visualization      |
          +-----------+------------+


## 🎨 Demo / Results


