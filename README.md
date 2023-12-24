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
which is conveniently linked in the helper tool site :), 
for documentation purposes though here it is, 

[Quake Topographic Map](https://ahounain.github.io/quake-topomap)
\
\
IMPORTANT NOTE!!!!!

![Screenshot 2023-12-23 at 8 49 34 PM](https://github.com/ahounain/quake-topomap/assets/69880126/36339d5e-3cd5-40ec-84c3-79012f0a15ba)

Make sure that you follow the GUI steps in order from top to bottom, I have included warnings and errors to yell at you
in case you slip up though so don't worry too much.
Another important note, if you want to do another map, simply refresh the page and reenter your new variables and data.

Now with your data, put in a center latitude and longitude into the GUI and specify the radius you want (NOTE MAKE SURE YOU HAVE FORM POPUPS ENABLED THATS WHAT I USED TO PROMPT THE USER FOR VARIABLES), keep in mind that 
if all the earthquakes happen outside of the region you set they will be outside of the "Walls." Make sure you choose a good 
center for the best visual results. 

For a cool experimental (terrible occurence :(( ) one, try these variables.\
Lat: 38\
Long: 143\
Radius: 5km\

URL: https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2011-03-01&endtime=2011-03-31&minlatitude=37&maxlatitude=39&minlongitude=142&maxlongitude=143
note: Its reaaaaaaaaally long.

![Screenshot 2023-12-23 at 8 54 04 PM](https://github.com/ahounain/quake-topomap/assets/69880126/927d8efc-9374-4d86-a571-c0ebefe8c1e7)

Doesn't look as visually impressive because its in the middle of the ocean. (that is where lots of earthquakes tend to happen though)

And with that you're done! 
Feel free to clone the repo and mess with anything as much as you like (just use your own token please..).
