# Historical Market Returns
For this project, we are replicating the excess market return outlined on the French Fama website in the below URL:

https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html

This is a value-weighted portfolio calculating the total excess US market return from July 1926 to January 2024 (subject to available data). Stocks are analyzed on a monthly basis. The risk free rate is imported from the French Fama website. We will filter our stocks to only use the 10 and 11 sharecodes and the 1, 2 and 3 exchanges, per the French Fama website.

# Packages
The following packages in Python to run these scripts:

\item wrds
\item pandas
\itme pandas_datareader
\item datetime
\item numpy
