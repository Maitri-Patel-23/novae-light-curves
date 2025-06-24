# Nova Light Curve: V7992 Sgr

This notebook performs a light curve analysis of the nova **V7992 Sgr** using publicly available data from the **American Association of Variable Star Observers (AAVSO)**.

The analysis includes:
- Extracting and plotting photometric data using the **'V' filter** (visual band).
- Identifying the nova's **maximum brightness** (minimum magnitude).
- Computing the **t2 and t3 times**, which represent the time taken for the nova to fade by 2 and 3 magnitudes from its peak brightness.
- Visualizing the nova's light curve with Julian Dates on the x-axis and magnitude on the y-axis (inverted scale for standard astronomical convention).

This notebook serves as a basic pipeline for studying classical novae and calculating their decay timescales using time-series photometric data.

Dependencies:
- pandas
- numpy
- matplotlib

- `V7992_Sgr_LightCurve-compute-t2-t3.ipynb`: Plots the full light curve and computes t2/t3 values.
- `V7992_Sgr_V_Filter_LightCurve.ipynb`: Filters the light curve data using only the V filter for higher accuracy in brightness analysis.

## How to Use
Open any `.ipynb` file in Jupyter Notebook or JupyterLab. Ensure the `V7992_Sgr.txt` file is in the same directory.

## Results
- The V filter notebook gives more precise t2 and t3 estimates based on filtered photometric data.
- Visualizations are provided for better understanding of the nova's brightness decline.

## References
- [AAVSO V7992 Sgr](https://www.aavso.org/vsx/index.php?view=detail.top&oid=8278029)
- [Koji’s Nova List](https://projectpluto.com/galnovae/galnovae.htm)
