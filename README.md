# AlphaScreen Inhibitor Screening Curve Fit
Python package that reads Excel input file containing AlphaScreen data, produces sigmoid fit according to equation provided by GraphPad (non-open-source statistics software). Displays IC50, 95% confidence interval, and R-squared value.

This code is intended to generate a single graph for each inhibitor used in a multi-inhibitor screen, where each inhibitor is tested at the same series of concentrations.

### Instructions:
1. Obtain AlphaScreen data and arrange data points by descending inhibitor concentration. 
2. Delete data in Input.xlsx and replace with your data. Ensure your positive zero-concentration data points are in the bottom row, along with a zero value for the concentration column. Keep the concentration column on the left.

![data](https://user-images.githubusercontent.com/49679286/138839301-d829ed8b-5167-4d40-89c1-7c4be3bd94b2.PNG)

3. Ensure Input.xlsx and the program are in the same directory (same folder, not one in a folder and one in a subfolder) before running.
4. Open the program in the IDE of your choice, and generate graphs! Sample output below:
![sample out](https://user-images.githubusercontent.com/49679286/138838078-095018f4-5fc7-45ea-954b-8cfd1298152a.PNG)
