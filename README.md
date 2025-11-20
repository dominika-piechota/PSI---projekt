The project was created as a coursework assignment for the course “Foundations of Artificial Intelligence”

# 📍 Route Planning Using a Genetic Algorithm

This project is designed to determine the optimal route between selected points in a city based on OpenStreetMap data, using:

* **Dijkstra’s algorithm** as a reference point that allows comparison of the obtained result with the best possible path,
* **a genetic algorithm** as the main algorithm of the project, which searches for the shortest route connecting all points selected by the user on the map.

Visualization and point selection are done interactively on a map using `ipyleaflet`.

Additionally, the user can modify genetic algorithm parameters and observe how these changes affect the accuracy of the resulting routes.

---

## 💻 Key Technologies and Libraries

* **Python 3.10+**
* `networkx` – graphs and paths
* `osmnx` – geographic data from OpenStreetMap
* `ipyleaflet` – interactive map for point selection
* `ipywidgets` – dynamic notebook interaction
* `matplotlib` – accuracy plots
* `folium` – visualizations
* `random`, `itertools` – permutation and randomness logic

---

## 🚀 How to Run

* Launch a Jupyter Notebook or Google Colab.
* Import the library and run the code with the point selection interface.
* Select points on the map (start, end, intermediate points).
* Run the genetic algorithm.
* Compare the results with the Dijkstra route.

---

The project supports a map of Kraków within a 10 km radius from the Main Square, but this can be easily changed to select another area or location.
