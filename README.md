Download Link: https://assignmentchef.com/product/solved-console-assignment3-numerator-denominator-in-a-reduces-fraction
<br>
<h1>1.  Date and Time difference</h1>

Write functions, with given prototypes, for computing difference of dates and times:

int datediff(int y1,int m1,int d1,int y2,int m2,int d2,int&amp; yd,int&amp; md,int&amp; dd);

// return value is the difference in number of days

// reference parameters used for difference in terms of years, months and days  // write proper checks for leap year, number of days in months, etc.

int timediff(int h1,int m1,int s1,int h2,int m2,int s2,int&amp; hd,int&amp; md,int&amp; sd);

// return value is the difference in number of seconds

// reference parameters used for difference in terms of hours, minutes and seconds

<h1>2.  Cartesian and Polar conversion</h1>

Write a function that can convert Cartesian coordinates to Polar coordinates. Write another function for Polar to Cartesian conversion.

<h1>3.  Geo-coordinates</h1>

Write a single function that can convert Geo-coordinates (Longitude and Latitude) expressed in degrees, minutes and seconds to their decimal equivalent.

Consider the following resources for explanation of Geo-coordinates and their conversion:

<a href="https://en.wikipedia.org/wiki/Geographic_coordinate_system">https://en.wikipedia.org/wiki/Geographic_coordinate_system</a> <a href="https://www.latlong.net/degrees-minutes-seconds-to-decimal-degrees">https://www.latlong.net/degrees-minutes-seconds-to-decimal-degrees</a>

<h1>4.  Reduce fraction</h1>

Write a function that takes two positive integer arguments as the numerator and denominator of a fraction, and reduces the fraction.  This reduction is achieved by dividing each of the two arguments by the greatest common divisor of the two integers.  The function should return the value 0 (to indicate failure to reduce) if either of the two arguments is zero or negative, and should return the value  1 otherwise.

Thus, for example, if  m  and   n are two integer variables with values 25 and 15 respectively; then passing them as parameter to reduce function, will result in their values 5 and 3, upon exit from the function.