### Libraries used
Pandas : To process data <br>
Numpy : For mathematical calculations<br>
Matplotlib : Simple Data Visualization <br>
Seaborn : To see trend between CodeForces rating and CodeChef rating

### Why :
BitByte (Programming Club, PDPM IIITDM Jabalpur) is organising <b>M</b>ost <b>I</b>mproved <b>C</b>ompetitive<b> P</b>rogrammer <br>In which members are ranked based on improvement in rating on different platforms. <br>
Comparing users who are active only on one platform was in-accurate simple sorting, hence CC to CF rating converter modelled using Linear Regression was developed. <p>

### How
<ol>
<li> Scraped data of around 12000 from StopStalk.
<li> Solved data-discrepancies using Excel and Pandas
<li> Spotting a linear trend between CodeChef and Codeforces rating (using scatter plot)
![Scatter plot between ratings.](https://user-images.githubusercontent.com/87320561/209918341-bf33d5ec-9a33-4595-b224-2731b3bd425d.png)

)
<li> Parameters for best fit line were calculated.
![Regression plot for CodeChef and CodeForces Rating.](https://user-images.githubusercontent.com/87320561/209918288-38a02e41-376e-4f11-8913-2caa7d1cad9d.png)

)
</ol>


### Further development :
<ol>
<li> Update the dataset regularly over the course of <b>MICP</b>
<li> Develop a web-app for the same
</ol>
