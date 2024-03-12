# Pymaceuticals Data Visualization

* Given the provided data files, files were mergered into a single DataFrame and cleaned to remove the duplicte subjects.
* A summary statictic was generated from the DataFrame presenting the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
* A pair of bar charts were generated to present the Mouse ID and Timepoints. Charts were created using Pandas and Matplotlib.
* A pair of pie charts were generated to present male versus female mice. Charts were created using Pandas and Matplotlib.
* Using the final tumor volume for the four most promissing treatment reginmens, the quartiles and IQR were calculated. Given these calculations, outliers were deteremined and presented using a box plot.
* Using a single treated mouse, a line plot was generated to show the tumor volume versus the timepoint.
* A scatter plot was created to show the mouse's weight versus the average observed turmor volumne for Capomulin.
* Utilizing the generated scatter plot, the correlation coefficient and  a linear regressinon module was created.

* From the analysised data, the following can be concluded:
  * From the bar plots, Capomulin & Ramicane had the highest number of observed timpepoints to the other treatment options.
  * From the pie plots, there was a slight number of more male mice than female.
  * Shown in the box plot, Capomulin & Ramicane produced a lower final tumor valume in the mice.
  * Throught the couse of the treatment, subject l509 had an increase in the volume of the tumor until day 20 then there was significate decrease after day 20 of treatment.
  * There is a high level of correlation in the weight of the mouse and average volume of the tumor. 
