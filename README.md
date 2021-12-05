# How big is the universe?
#### Video Demo:  <URL HERE>
#### Description: 
  This is my final project for the CS50x 2021 course. It is a visualisation of the size of the observable universe, starting by visualising an object that is a metre long, using that to visualise another object that is ten metres long, then a hundred, a thousand, etc., until we reach the size of the universe.
  
  The project is a tribute to the breathtaking nature and scale of cosmology, a subject I love but have trouble wrapping my head around. As the numbers and zeros grow, everything becomes so abstract that it is hard to appreciate, or even comprehend, just how big or far away anything is. This project takes a stab at visualising that abstraction.
  
  There are three files in this project:
  
  First, index.html has the HTML for a simple, single webpage. One particularly tricky part, for me, was the ruler. I experimented with various ways of depicting a ruler that could be responsive, and ultimately a table scaled the best. This was a remnant of my first draft that I later redid, which consisted of tables instead of divs.
  
  Next, styles.css has the CSS, and is pretty straightforward.
  
  Last of all is scripts.js, the Javascript and heart of the project. It begins with an array containing the  details of all the items presented, and was the product of much wrestling with and giving up on using a CSV file. I still think a CSV file might have been neater, but I simply could not work out the various transitions from one language to another. 
  
  The next portion of scripts.js is the item transition. I tried to design everything as programmatically as possible, but I still had to separate different sorts of items, with different changes to different elements. There is probably still much redundancy here. 
  
  The extension I would most want to make would be a 'Zoom In' button, that reverses the 'Zoom Out' one. I had hoped there would be a library or function in Javascript that could do this automatically, but I couldn't find anything appropriate. I would have manually coded it then, inverting each line in the entire function.
  
  Although nothing to do with the code, the research for this project was intense and fascinating. I wanted to the content to be understandable to a layman, while keeping the details that make the subject as interesting as it is. 
  
  Finally, this project is directly inspired by, and at times quotes and borrows from, the fantastic _You Are Here: A Portable History of the Universe_, by Christopher Potter. Other sources are as follows, arranged by item number.
  
#### Text sources
  This list includes only the sources I directly quoted or paraphrased, and is a fraction of the many more that helped me understand what on Earth they were talking about, or to corroborate the vastly ranging numbers at times. I used Wikipedia by default for my sanity given the breadth of topics, although the secondary sources in each page would be the actual source.
1. https://www.nature.org/en-us/get-involved/how-to-help/animals-we-protect/african-bush-elephant/
2. https://www.livescience.com/supersaurus-longest-dinosaur-on-record/
3. https://en.wikipedia.org/wiki/New_Century_Global_Center
4. https://www.britannica.com/place/Uluru-Ayers-Rock
5. https://en.wikipedia.org/wiki/Gotthard_Base_Tunnel
6. https://en.wikipedia.org/wiki/List_of_mountain_ranges#Mountain_ranges_by_length, https://en.wikipedia.org/wiki/Western_Alps
7. https://www.britannica.com/place/Russia
8. https://en.wikipedia.org/wiki/Earth%27s_circumference
9. https://en.wikipedia.org/wiki/Lunar_distance_(astronomy)
10. https://www.space.com/51-asteroids-formation-discovery-and-exploration.html
11. https://www.space.com/18529-distance-to-venus.html
12. https://en.wikipedia.org/wiki/Planet, https://www.space.com/18383-how-far-away-is-jupiter.html
13. https://sitn.hms.harvard.edu/flash/2020/fly-distant-asteroid-provides-clues-formation-solar-system, https://en.wikipedia.org/wiki/Kuiper_belt 
14. https://en.wikipedia.org/wiki/Heliosphere, https://spaceplace.nasa.gov/interstellar/en/, https://solarsystem.nasa.gov/resources/2232/where-is-the-edge-of-the-solar-system
15. 
16. https://en.wikipedia.org/wiki/Oort_cloud, https://solarsystem.nasa.gov/solar-system/oort-cloud/in-depth/, https://en.wikipedia.org/wiki/Comet#Long_period
17. https://en.wikipedia.org/wiki/Alpha_Centauri
18. https://en.wikipedia.org/wiki/51_Pegasi_b, https://en.wikipedia.org/wiki/Exoplanet, https://exoplanets.nasa.gov/resources/289/infographic-profile-of-planet-51-pegasi-b/
19. https://en.wikipedia.org/wiki/Betelgeuse, https://en.wikipedia.org/wiki/Supernova
20. https://en.wikipedia.org/wiki/Crab_Nebula, https://www.nasa.gov/multimedia/imagegallery/image_feature_460.html
21. https://en.wikipedia.org/wiki/Galaxy, https://earthsky.org/astronomy-essentials/what-is-the-milky-way-galaxy/, https://en.wikipedia.org/wiki/Galactic_Center, https://en.wikipedia.org/wiki/Black_hole
22. https://en.wikipedia.org/wiki/Galactic_halo, https://en.wikipedia.org/wiki/Satellite_galaxy, https://en.wikipedia.org/wiki/Large_Magellanic_Cloud, https://en.wikipedia.org/wiki/Small_Magellanic_Cloud
23. https://en.wikipedia.org/wiki/Andromeda_Galaxy, https://en.wikipedia.org/wiki/Andromeda%E2%80%93Milky_Way_collision
24. https://en.wikipedia.org/wiki/Local_Group, https://en.wikipedia.org/wiki/Virgo_Cluster
25. https://en.wikipedia.org/wiki/Virgo_Supercluster, https://en.wikipedia.org/wiki/Laniakea_Supercluster, https://en.wikipedia.org/wiki/Shapley_Supercluster
26. https://en.wikipedia.org/wiki/MACS_J1149_Lensed_Star_1, https://en.wikipedia.org/wiki/Gravitational_lens
27. https://en.wikipedia.org/wiki/Observable_universe, https://en.wikipedia.org/wiki/Universe
  
#### Image sources 
  All images are free content from Wikimedia Commons.
1. https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Male_African_Elephant_After_Mud_Bath_2019-07-25.jpg/640px-Male_African_Elephant_After_Mud_Bath_2019-07-25.jpg
2. https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Supersaurus_dinosaur.png/640px-Supersaurus_dinosaur.png
3. https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/New_Century_Global_Center.jpg/640px-New_Century_Global_Center.jpg
4. https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Uluru_sunset_glow.jpg/640px-Uluru_sunset_glow.jpg
5. https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Neat_gotthard_schema_deutsch.png/640px-Neat_gotthard_schema_deutsch.png
6. https://upload.wikimedia.org/wikipedia/commons/b/b3/Alpen.jpg
7. https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Russia_administrative_location_map.svg/640px-Russia_administrative_location_map.svg.png
8. https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Physical_Map_of_the_World_%282021%29.svg/640px-Physical_Map_of_the_World_%282021%29.svg.png
9. https://upload.wikimedia.org/wikipedia/commons/9/9e/Pin-location.png, https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/Full_Moon_Luc_Viatour.jpg/238px-Full_Moon_Luc_Viatour.jpg
10. https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Vesta_black_background.png/240px-Vesta_black_background.png
11. https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Venus_globe.jpg/240px-Venus_globe.jpg
12. https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/PIA23605_-_The_Exotic_Marble.jpg/240px-PIA23605_-_The_Exotic_Marble.jpg
13. https://upload.wikimedia.org/wikipedia/commons/5/5a/Outersolarsystem_objectpositions_labels_comp_%28without_labels_and_scale%29.png
14. https://upload.wikimedia.org/wikipedia/commons/a/ac/NewHeliopause_558121_%28cropped%29.png
15. https://ide.cs50.io/5d4fdf3c21b441e78b139328faaefe00
16. https://upload.wikimedia.org/wikipedia/commons/d/d7/Oort_cloud_%28cropped_to_square%29.png
17. https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/The_bright_star_Alpha_Centauri_and_its_surroundings.jpg/240px-The_bright_star_Alpha_Centauri_and_its_surroundings.jpg
18. https://upload.wikimedia.org/wikipedia/commons/a/a1/51_Pegasi.jpg
19. https://upload.wikimedia.org/wikipedia/commons/thumb/8/88/Betelgeuse_star.png/240px-Betelgeuse_star.png
20. https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/Crab_Nebula.jpg/240px-Crab_Nebula.jpg
21. https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Milky_Way_Galaxy.jpg/240px-Milky_Way_Galaxy.jpg
22. https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Smclmc-35deg-16k-min20k-4550k-m19-g1-s8.png/240px-Smclmc-35deg-16k-min20k-4550k-m19-g1-s8.png
23. https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Andromeda_galaxy.png/240px-Andromeda_galaxy.png
24. https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Virgo_cluster.png/240px-Virgo_cluster.png
25. https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Shapley_supercluster.png/240px-Shapley_supercluster.png
26. https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Icarus.png/240px-Icarus.png
27. 

