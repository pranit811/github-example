###The battle of neighbourhoods
Find Location to Build New Cinema in Hong Kong
##Where to visit if you want to eat burger

##INTRODUCTION

Lets assume you never visit US before. And you want to eat only burger. So you are finding a place where you can find a lot of number of shops 
of burger.The problem we aim to solve is to analyze the burger stores’ locations in the major US cities. Find the best place for our tourist
for good burger.

##Data Part

I will use the FourSquare API to collect data about locations of burger stores in 5 major US cities which are:
New York,NY, San Francisco, CA,Jersey City, NJ, Boston, MA and Chicago,IL.These are one of the most populated US cities and I am
where tourist can find good restaurant for burger.

##Methodology

My main target here is to asses which city would have the highest Pizza store density. I used the Four Square API through 
the venues.channel. I used the near query to get venues in the cities. Also, I use the CategoryID to set it to show only burger Places.
An example of my requests.
https://api.foursquare.com/v2/venues/explore?&client_id=&client_secret=&v=20180605&New York, NY&limit=100&categoryId=4bf58dd8d48988d1ca941735


##Discussion

One thing I noticed in the figure is that there is a really far away burger Store in Jersey City 
that is probably giving it a higher MDMC. So I cheched what if I removed it, it would not harm anyone
to try 99 burger places than 100 and New York is just at the other shore.

##Conclusion

Now there is no doubt that New York is the best place to try many burger Places in the US. 
Also, if our tourist is done with all the New York burger places he can cross to Jersey City and enjoy 99 more.

Also, we would recommend that our tourist book a hotel close to the mean coordinate.
