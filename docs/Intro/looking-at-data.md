The world is full of data, and we the people have to make decisions.

**Statistics** comes to our rescue - it takes data and turns it into information that we the people can use to make decisions. Whether you are in social sciences, medicine, engineering, public policy,
psychology, climatology, robotics, even archaeology, health sciences,
finance, business and marketing, or pretty much any other discipline that you can study. All of those are now driven by data, including unlikely fields like biology or physics
and so many others.

One of the standard problems that people study in statistics has to do with purchasing decisions. Suppose you wish to buy a house - there are small houses and big houses, but you really like this one special house build by a famous designer which has a certain price.

In statistics, the way we find out is by looking at data. Let's assume there is a database of previous house sales of homes in the same neighborhood. Just for simplicity, let's assume we know about two things -
the size of the home and the cost at which it was sold.

|Size (sq.ft)|Cost ($)|
|----|----|
|1400|112000|
|2400|192000|
|1800|144000|
|1900|152000|
|1300|104000|
|1100|88000|

It turns out that this data set has this amazing property that the cost per square foot is constant.

$$\frac{112000}{1400} = 80$ /sq.ft$$

**How much money should you expect to pay if you're trying to purchase a house with 2100 & 1500 sq.ft?**

$$\frac{144000 + 192000}{2} = 168000$$

2100 is just halfway between 1800 and 2400. If you take halfway between $144,000 and $192,000 - we get the mean of 144,000 and 192,000 and that is $168,000.

$$112000+\frac{144000 - 112000}{4} = 120000$$

By our logic, 1500 lies between 1400 and 1800. In fact, it's a quarter away from 1400.
We'd say it's $112,000 plus 1/4 of the way from 1400 to 1800.

But as we go forward, we're going to look into data where the cost might not just be
a constant factor times the size of a home.