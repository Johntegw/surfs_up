# surfs_up
Background
      W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to           determine if the surf and ice cream shop business is sustainable year-round.

What You're Creating
  This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

    Deliverable 1: Determine the Summary Statistics for June
    Deliverable 2: Determine the Summary Statistics for December
    Deliverable 3: A written report for the statistical analysis (README.md)
    Files

Instructions
      Deliverable 1: Determine the Summary Statistics for June (40 points)
      Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then       convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Follow the instructions below to complete Deliverable 1.

      Download the SurfsUp_Challenge_starter_code.ipynb file into your surfs_up folder, then rename it SurfsUp_Challenge.ipynb.
      Use the instructions below to add code where indicated by the numbered comments in the starter code file. The starter code file includes all dependencies needed for this Challenge.
      In Step 1, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June.
      In Step 2, convert the June temperatures to a list.
      In Step 3, create a DataFrame from the list of temperatures for the month of June.
      In Step 4, generate the summary statistics for the June temperatures DataFrame.
      After you run Step 4 in your SurfsUp_Challenge.ipynb file, confirm that the summary statistics match the image below.
      The summary statistics for the June temperatures DataFrame

Deliverable 2: Determine the Summary Statistics for December (40 points)
    Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll          then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

    Follow the instructions below to complete Deliverable 2.

    Use the instructions below to add code where indicated by the numbered comments in your SurfsUp_Challenge.ipynb file.
    In Step 6, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of December.
    In Step 7, convert the December temperatures to a list.
    In Step 8, create a DataFrame from the list of temperatures for the month of December.
    In Step 9, generate the summary statistics for the December temperatures DataFrame.
    After you run Step 9 in your SurfsUp_Challenge.ipynb file, confirm that the summary statistics match the image below.
    The summary statistics for the December temperatures DataFrame

RESULTS:
     Provided below is a summary of three major points from the two analysis deliverables. 
    There are two differences in the in the number of days reported for June and December temps that were captured. In June data we are looking at 1700 data points and December we are looking at 1517 data points. 
    The mean or average temp between the two are : June 74 degrees with a standard deviation of 3.2  and December 71 with a standard deviation of 3.7.
    The max temp captured for June is 85 degrees and in December it is 83 degrees . See snapshot below: 
 
              June tobs
              count	1700.000000
              mean	74.944118
              std	3.257417
              min	64.000000
              25%	73.000000
              50%	75.000000
              75%	77.000000
              max	85.000000


            December tobs
            count	1517.000000
            mean	71.041529
            std	3.745920
            min	56.000000
            25%	69.000000
            50%	71.000000
            75%	74.000000
            max	83.000000

Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

    The basic queries that were completed statistically for month of June showed that out of the 1700 points 50% were around 75 degrees while 75% were around 77 degrees. In December it showed that 50% were around 71         degrees and 75% were around 74 degrees. Between the two months the variance between the degrees were only a 3 to 4 degree difference. Two other queries that could be done on the data would be to show if there were       certain days that had the same temp and if certain years the temps were around the same midpoints , min and max degrees.
