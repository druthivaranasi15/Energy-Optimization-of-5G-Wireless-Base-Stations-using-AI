# Energy Optimization of 5G Using AI

An exploratory machine-learning project focused on energy optimization in 5G wireless networks. The project includes a Jupyter notebook, a 5G energy-consumption dataset, and a system CPU log.

## Project contents

| File | Description |
|---|---|
| [`Energy optimization of 5G using AI.ipynb`](Energy%20optimization%20of%205G%20using%20AI.ipynb) | Main notebook for the project’s analysis and implementation. |
| [`5G_energy_consumption_dataset.csv/5G_energy_consumption_dataset.csv`](5G_energy_consumption_dataset.csv/5G_energy_consumption_dataset.csv) | Dataset file used for energy-consumption analysis. |
| [`5G_energy_consumption_dataset.csv/system_log.txt`](5G_energy_consumption_dataset.csv/system_log.txt) | System CPU-usage log captured during a run; it is not a 5G network energy-measurement report. |

> **Note:** The dataset is currently stored inside a directory named `5G_energy_consumption_dataset.csv`. Keep that directory structure when opening the dataset from the notebook, or update the notebook’s data path if you move the file.

## Project goals

- Explore the relationship between 5G network parameters and energy consumption.
- Apply machine-learning techniques to support energy-efficiency analysis.
- Investigate ways to reduce energy use while maintaining network performance.

## Tools and libraries

The project is implemented in Python using Jupyter Notebook. The existing project documentation lists these libraries:

- NumPy
- Pandas
- scikit-learn
- Matplotlib

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/druthivaranasi15/Energy-Optimization-of-5G-Wireless-Base-Stations-using-AI.git
cd Energy-Optimization-of-5G-Wireless-Base-Stations-using-AI
```

### 2. Install the dependencies

```bash
python -m pip install jupyter numpy pandas scikit-learn matplotlib
```

### 3. Open the notebook

```bash
jupyter notebook "Energy optimization of 5G using AI.ipynb"
```

Run the notebook cells in order. If a cell cannot find the dataset, check that the CSV remains at the path shown above and that the notebook uses that relative path.

## Results

The repository’s README does not currently document specific evaluation metrics or numerical energy savings. Run the notebook to inspect its outputs before drawing conclusions about model performance or the amount of energy saved.

## Future work

- Document the dataset’s features, source, and preprocessing steps.
- Report evaluation metrics and quantify any observed energy savings.
- Compare additional models or optimization approaches.
- Explore validation with real-time or operational network data.

## Author

**Druthi Varanasi**
