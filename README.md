# gr5206-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [GR5206 Homework 5 Solved](https://www.ankitcodinghub.com/product/gr5206-homework-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94745&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GR5206 Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

Part 1 (Iris)

Background: Edgar Anderson’s Iris Data

The R data description follows:

This famous (Fisher’s or Anderson’s) iris data set gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. The species are Iris setosa, versicolor, and virginica.

Task

The purpose of this task is to construct a complex plot using both base R graphics and ggplot. Consider the follwoing base R plot.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Length",main="
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
5)

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
# Base plot

plot(iris$Sepal.Length,iris$Petal.Length,col=iris$Species,xlab=”Sepal Length”,ylab=”Petal

<pre># loop to construct each LOBF
</pre>
for (i in 1:length(levels(iris$Species))) {

extract &lt;- iris$Species==levels(iris$Species)[i] abline(lm(iris$Petal.Length[extract]~iris$Sepal.Length[extract]),col=i) }

# Legend

legend(“right”,legend=levels(iris$Species),fill = 1:length(levels(iris$Species)), cex = .7

<pre># Add points and text
</pre>
points(iris$Sepal.Length[15],iris$Petal.Length[15], pch = “*”, col = “black”) text(iris$Sepal.Length[15]+.4,iris$Petal.Length[15],”(5.8,1.2)”,col=”black”) points(iris$Sepal.Length[99],iris$Petal.Length[99], pch = “*”, col = “red”) text(iris$Sepal.Length[99]+.35,iris$Petal.Length[99],”(5.1,3)”,col = “red”) points(iris$Sepal.Length[107],iris$Petal.Length[107],pch = “*”, col = “green”) text(iris$Sepal.Length[107],iris$Petal.Length[107]+.35,”(4.9,4.5)”,col = “green”)

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Gabriel’s Plot

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
(4.9,4.5) *

*

</div>
<div class="column">
(5.1,3)

*

</div>
</div>
<div class="layoutArea">
<div class="column">
(5.8,1.2)

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
setosa versicolor virginica

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4.5 5.0 5.5 6.0 6.5 7.0 7.5 8.0

Sepal Length

1) Produce the exact same plot from above using ggplot as opposed to Base R graphics. That is, plot Petal Length versus Sepal Length split by Species. The colors of the points should be split according to Species. Also overlay three regression lines on the plot, one for each Species level. Make sure to include an appropriate legend and labels to the plot. Note: The function coef() extracts the intercept and the slope of an estimated line.

<pre>### your code goes here
</pre>
Part 2 (World’s Richest)

Background

We consider a data set containing information about the world’s richest people. The data set us taken form the World Top Incomes Database (WTID) hosted by the Paris School of Economics [http://topincomes. g-mond.parisschoolofeconomics.eu]. This is derived from income tax reports, and compiles information about the very highest incomes in various countries over time, trying as hard as possible to produce numbers that are comparable across time and space.

Tasks

2) Open the file and make a new variable (dataframe) containing only the year, “P99”, “P99.5” and “P99.9” variables; these are the income levels which put someone at the 99th, 99.5th, and 99.9th, percentile of income. What was P99 in 1993? P99.5 in 1942? You must identify these using your code rather than looking up the values manually.

</div>
</div>
<div class="layoutArea">
<div class="column">
wtid &lt;- read.csv(“wtid-report.csv”, as.is = TRUE) ### your code goes here

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Petal Length

</div>
</div>
<div class="layoutArea">
<div class="column">
1234567

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3) Plot the three percentile levels against time using ggplot. Make sure the axes are labeled appropriately, and in particular that the horizontal axis is labeled with years between 1913 and 2012, not just numbers from 1 to 100. Also make sure a legend is displayed that describes the multiple time series plot. Write one or two sentences describing how income inequality has changed throughout time. Remember library(ggplot2).

<pre>### your code goes here
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
