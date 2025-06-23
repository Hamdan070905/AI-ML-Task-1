# AI-ML-Task-1
1. The first cell contains the header files :
       > Pandas is the go-to library for data manipulation and analysis.
       > NumPy is a library for numerical operations and arrays.
       > The seaborn and the matplotlib are the two Python's main data visualization libraries
       > The tools of the Scikit-learn, the most popular ML library in Python
       > SciPy is a library used for scientific computing.
2. The second cell contains:
       First, we're importing the dataset using Pandas.
         > df.info() gives us a summary of the columns, data types, and missing values.
         > df.describe() gives some basic stats like mean, min, max, and standard deviation for numerical columns.
3. The third cell contains:
        > We handle missing values in numeric columns by replacing them with the mean of each respective column.
So, if a column like Age has NaN values, they'll be filled with the average value of that column.
4. The fourth cell contains:
        > Here, we loop through all categorical columns (text data) and convert them to numbers using Label Encoding.
This means something like:
          "Male" → 0, "Female" → 1
5. The fifth cell contains:
        > After encoding, we standardize all numerical columns using StandardScaler.
This brings everything onto the same scale:
       print("Means after scaling:  Mean will get some value  )
       print("Standard deviations after scaling: Standard deviation will get some value )
6. The sixth cell contains:
       > Now we visualize our cleaned dataset using a boxplot.
Boxplots help us see outliers — values that are unusually high or low compared to the rest.
We rotate the x-axis labels so they don’t overlap.
7. The last cell conatins:
       > Finally, we remove outliers using the Z-score method:
We calculate how far each value is from the mean (in standard deviations).
If any value in a row has a Z-score greater than 3 (either too high or too low), that whole row is removed.

AT LAST :
   THE df is now:

Cleaned

Free of missing values

Numerically encoded

Normalized

Outliers removed



          

       
