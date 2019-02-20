# Retirement-Calculator
Calculates how given portfolio, annual spending, and retirement length would have fared historically to help plan retirement savings.

The initial calculator included 'decade' as an input -- it uses the average inflation and S&P 500 return rates for an inputted decade, or multiple, to calculate how one's portfolio would have performed.

However, using the same inflation and return rates for every year of your retirement is very unrealistic, so the second version of the calculator uses the appropriate inflation and return rates for each year of retirement, based on the data, and does as many cycles as it can given the length of the retirement. For example, if you entered in a duration of 30 years, the first cycle would start at 1928 and the last cycle would start at 1988, for a total of 61 cycles.

Inspired by: firecalc.com

Sources:
- https://firecalc.com
- S&P 500 data from 1928 to 2018: http://pages.stern.nyu.edu/~adamodar/New_Home_Page/datafile/histretSP.html
- Inflation data from 1914 to 2019: https://www.usinflationcalculator.com/inflation/historical-inflation-rates/
