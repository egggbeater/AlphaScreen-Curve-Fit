# AlphaScreen Inhibitor Screening Curve Fit
Reads Excel input file containing AlphaScreen data, produces sigmoid fit according to equation provided by GraphPad (non-open-source statistics software). Displays IC50, 95% confidence interval, and R-squared value.

This code is intended to generate a single graph for each inhibitor used in a multi-inhibitor screen, where each inhibitor is tested at the same series of concentrations.

### Instructions:
1. Obtain AlphaScreen data and arrange data points by descending inhibitor concentration. Ensure your positive zero-concentration data points are in the bottom row, along with a zero value for the concentration column.
2. Delete data in Input.xlsx and replace with your data.
3. Ensure Input.xlsx and the program are in the same directory before running.
4. Open the program in the IDE of your choice, and generate graphs!
