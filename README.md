Download Link: https://assignmentchef.com/product/solved-msds6371-unit-11-black-eared-wheatears-birds
<br>



<ol>

 <li>Black-eared wheatears are small birds of Spain and Morocco. Males of the species demonstrate an exaggerated sexual display by carrying many heavy stones to nesting cavities. This 35-gram bird transports, on average, 3.1 kg of stones per nesting season! Different males carry somewhat different sized stones, prompting a study of whether larger stones may be a signal of higher health status. M. Soler et al. calculated the average stone mass (g) carried by each of 21 male black-eared wheatears, along with T-cell response measurements (in mm) reflecting their immune system strengths. Analyze the data and write a statistical report (by answering the questions below); treat the T-cell as the response and the stone mass as the explanatory variable. You may assume all criteria for regression and related t-tests are met. You can find the data for this problem on 2DS. (Male Display Data Set)</li>

</ol>

Analyze the data, providing the following:

<ol>

 <li>Provide a scatterplot with 99% confidence intervals of the regression line and 99% prediction intervals of the regression line. Please do this in R.</li>

 <li>Provide a table showing the t-statistics and p-values for the significance of the regression parameters (as different from 0). Please do this in R.</li>

 <li>Using the output in (b), show all 6 steps of <strong><em>each</em></strong> hypothesis test. (That’s one test for and one test for .) Find critical values in R. Your conclusion should include a confidence interval. Use alpha = 0.01.</li>

 <li>State the regression equation. Be careful to use the mean Tcell or predicted Tcell, rather than just Tcell.</li>

 <li>Interpret the slope in the model (regression equation).</li>

 <li>Interpret the y-intercept in the model (regression equation).</li>

 <li>Find and interpret the 99% <u>confidence</u> interval for the mean t-cell response conditional on a stone mass of 4.5 grams. Please do this directly in R.</li>

 <li>Find and interpret the 99% <u>prediction</u> interval for the predicted t-cell response given a stone mass of 4.5 grams. Please do this directly in R.</li>

 <li>Calibration intervals:

  <ol>

   <li>Using the <strong>graphical method</strong> (using your best judgment using the graphs from part (a)), find the following using R, as part (a) was done in R.

    <ol>

     <li>99% calibration interval for the <strong>mean</strong> t-cell response of 0.3.</li>

     <li>99% calibration interval for a <strong>single</strong> t-cell response of 0.3.</li>

    </ol></li>

   <li>Using <strong>software directly</strong>, find the following using R, as SAS does not provide calibration intervals directly. (R: package investr)

    <ol>

     <li>99% calibration interval for the <strong>mean</strong> t-cell response of 0.3.</li>

     <li>99% calibration interval for a <strong>single</strong> t-cell response of 0.3.</li>

    </ol></li>

   <li><strong>Interpret</strong> the following using the results from (1) and (2) above.

    <ol>

     <li>99% calibration interval for the <strong>mean</strong> t-cell response of 0.3.</li>

     <li>99% calibration interval for a <strong>single</strong> t-cell response of 0.3.</li>

    </ol></li>

   <li>Provide a scatterplot of residuals. Please do this in R.</li>

   <li>Provide a histogram of residuals with a normal distribution superimposed. It might be helpful to use studentized residuals, rather than regular residuals, with a normal curve overlay. Use R. (You may need to research this, such as googling “histogram with normal curve in R.”)</li>

   <li>Provide a measure of the <strong>proportion</strong> of variation in the response that is accounted for by the explanatory variable. <strong>Interpret</strong> this measure. Use R.</li>

  </ol></li>

 <li>Using the data for Black-eared Wheatears, calculate by “hand” (using Excel) the following elements. (An example of much of this was in the PowerPoints and in the videos below.)

  <ol>

   <li></li>

   <li>The t-statistics and p-values for the hypothesis tests (and for ).</li>

   <li>99% confidence intervals for the mean of Y when X = {3,4,5,6,7,8,9} grams. You do NOT need to make a Bonferroni (or any other type of) multiple interval correction, as the primary purpose of these intervals is to be able to plot confidence interval bands.</li>

   <li>99% prediction intervals for the predicted Y when X = {3,4,5,6,7,8,9} grams. You do NOT need to make a Bonferroni (or any other type of) multiple interval correction, as the primary purpose of these intervals is to be able to plot prediction interval bands.</li>

   <li>Provide a plot for the confidence intervals and prediction intervals using Excel. Fully label your graph. (Use the regression equation and parts (c) and (d) above to create the plot.)</li>

   <li>Calibration intervals:</li>

  </ol></li>

 <li>Using the SE equations given in class and in the book (Version 3 page 194), find the following <strong>analytically</strong>. (Use Excel for calculations.)

  <ol>

   <li>99% calibration interval for the mean t-cell response of 0.3.</li>

   <li>99% calibration interval for a single t-cell response of 0.3.</li>

  </ol></li>

 <li>Using the <strong>Excel graphs</strong>, find the following. You may want to add data points to parts (c) and (d) so that the confidence and prediction limits extend well beyond the data range (although their interpretation is questionable outside the range).

  <ol>

   <li>99% calibration interval for the mean t-cell response of 0.3.</li>

   <li>99% calibration interval for a single t-cell response of 0.3.</li>

  </ol></li>

</ol>




<ol start="3">

 <li>Bonus!

  <ol>

   <li>Repeat 1 (a) using SAS.</li>

   <li>Repeat 1 (b) using SAS.</li>

   <li>Repeat 1 (c) using SAS.</li>

   <li>Repeat 1 (g) using SAS.</li>

   <li>Repeat 1 (h) using SAS.</li>

   <li>Repeat 1 (j) using SAS.</li>

   <li>Repeat 1 (k) using SAS.</li>

   <li>Repeat 1 (l) using SAS.</li>

  </ol></li>

</ol>




Videos for using Excel:

<a href="http://screencast.com/t/ztSxTImiOk6s">http://screencast.com/t/ztSxTImiOk6s</a>

SE of  and RMSE: <a href="http://screencast.com/t/V9gnhSwb">http://screencast.com/t/V9gnhSwb</a>

Confidence Intervals: <a href="https://www.screencast.com/t/ELiUGTe7Kc">https://www.screencast.com/t/ELiUGTe7Kc</a>

Prediction Intervals: <a href="https://www.screencast.com/t/ap8WETxsGUqN">https://www.screencast.com/t/ap8WETxsGUqN</a>

CI and PI Plotting: <a href="https://www.screencast.com/t/efrpHrqgYZnG">https://www.screencast.com/t/efrpHrqgYZnG</a>

Calibration Mean Gross:  <a href="https://www.screencast.com/t/Yu7eqiiH0X">https://www.screencast.com/t/Yu7eqiiH0X</a>

Calibration Single Movie:  <a href="https://www.screencast.com/t/2vS1lGqtJ">https://www.screencast.com/t/2vS1lGqtJ</a>