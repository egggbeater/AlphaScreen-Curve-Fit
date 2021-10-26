# AlphaScreen Inhibitor Screening Curve Fit
Python package that reads Excel input file containing AlphaScreen data, produces sigmoid fit according to the following equation provided by GraphPad (non-open-source statistics software): 

<code>Y=100/(1+10^(X-LogIC50))</code>

Along with the graphs, it will also display the IC50, 95% confidence interval and R-squared value.

This code is intended to generate a single graph for each inhibitor used in a multi-inhibitor screen, where each inhibitor is tested at the same series of concentrations.

### Instructions:
1. Obtain AlphaScreen data and arrange data points by descending inhibitor concentration. 
2. Delete data in <code>Input.xlsx</code> and replace with your data. Ensure your positive control zero-concentration data points are in the bottom row, along with a zero value for the concentration column. Keep the concentration column on the left.

![data](https://user-images.githubusercontent.com/49679286/138839301-d829ed8b-5167-4d40-89c1-7c4be3bd94b2.PNG)

3. Ensure <code>Input.xlsx</code> and <code>AlphaScreen-Curve-Fit.ipynb</code> are in the same directory (same folder, not one in a folder and one in a subfolder) before running.
4. Open <code>AlphaScreen-Curve-Fit.ipynb</code> in the IDE of your choice, hit Run, and generate graphs! Sample output below:
![image](https://user-images.githubusercontent.com/49679286/138866438-0db2b57a-4ac3-4567-80dd-1f8e8acca066.png)
