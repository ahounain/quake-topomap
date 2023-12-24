# quake-topomap
Tool to visualize earthquake data using the USGS API for earthquake data, and Mapbox for satellite tile photos.

To get started first you're going to need some data. 

Acquire the time span in which the earthquake event occured, and the bounding latitude and longitude of the area in which it happened, 
(be aware originally the limit is 5km for time/resource reasons but with your own API token you can feel free to go as big as you want)
(p.s. I raised the radius to 125 for my own sake)
and enter all the data into the tool that I created,
![Screenshot 2023-12-23 at 8 48 34 PM](https://github.com/ahounain/quake-topomap/assets/69880126/a82af8db-2fbe-4edd-af5f-183a4918fa7d)
[Simple tool!!](https://ahounain.github.io/quake-topomap/init/)
which will generate a USGS url, which you can then simply copy all the data from and head on over to the main site
which is conveniently linked in the helper tool site ( :) ), 
for documentation purposes though here it is, 

[Quake Topographic Map](https://ahounain.github.io/quake-topomap)


IMPORTANT NOTE!!!!
Make sure that you follow the GUI steps in order from top to bottom, I have included warnings and errors to yell at you
in case you slip up though so don't worry too much.
Another important note, if you want to do another map, simply refresh the page and reenter the variables and data.

Now with your data, put in a center latitude and longitude into the GUI and specify the radius you want, keep in mind that 
if all the earthquakes happen outside of the region you set they will be outside of the "Walls." Make sure you choose a good 
center for the best visual results. 

And with that you're done! 
Feel free to clone the repo and mess with anything as much as you like (just use your own token please..).
