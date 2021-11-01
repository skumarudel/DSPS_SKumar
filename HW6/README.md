# Part 2
Plot of significance distribution of `background` data and `signal+background` data

Basically the below plots are one dimensioal significance distribution of 2-dimensional significance maps i.e. take significance of each bin in the 2D map and crete 1D map out of it. In the background map, signal region is masked and in the signal+background map, signal region is not masked. As you see in the signal+background distribution, signal is clearly showing at a 8-9 sigma level, whereas in the background only region, the significance distribution mean at zero and sigma=1, which is consistent with the background fluctuations around a mean of zero.

## Original plot 
This plots shows two histograms on top of each other but the signal+background histogram in the back is hard to see. I even try to reduce the alpha value but it is still not looking great. This is because in the overlapping region, bin counts are more or less same and its hard to distinguish what is what. Also the black curve is the fitted gaussian curve on only background bins. I did not show the value of parameteres in the same plot (mean, sigma), which can tell me immediately if the background estimation is wrong or right. For example if the paraemteres are close to mean of 0 and sigma of 1, it means that our background is estimated correctly.
![image](https://github.com/skumarudel/DSPS_SKumar/blob/master/HW6/originalimage.png)

## Modified plot
I modified the original plot and use a steptype histogram instead of default (filled one). Now you can see both the histograms clearly. Also adding the gaussian fit in the legend make it clear about the background estimation. I also changed the fitted line to dotted which looks appealing. The font size of axis labels is also increased a bit. The legend is also clearly distinguished from the plot, by giving the legendframe a light color.  


![image](https://github.com/skumarudel/DSPS_SKumar/blob/master/HW6/modifiedimage.png)

