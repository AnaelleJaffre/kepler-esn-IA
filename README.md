# Quick Setup

## Dataset

1. Go to the Kaggle dataset main page: [Exoplanet Hunting in Deep Space](https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data).
   
2. Click on the **"Download"** button, and choose a zip folder.

3. Extract the two files **"exoTrain.csv"** and **"exoTest.csv"** from the archive.
   
4. Place them into the **"data"** folder of the current project.

## Program

### On Windows

1. Create a virtual environement (unless you don't care about it)
   ```
   python -m venv kepler-esn-env
   ```

2. Enter the virtual environment
   ```
   .\kepler-esn-env\Scripts\Activate
   ```

3. Install `reservoirpy` and the other dependencies
   ```
   pip install reservoirpy pandas numpy matplotlib scikit-learn
   ```
   