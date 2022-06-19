# UFOs

## Overview
Creating a web page of UFO sighting data using JavaScript to make page interactive.

## Results
![Screen Shot 2022-06-19 at 4 34 03 PM](https://user-images.githubusercontent.com/96406929/174504582-cfe3f5d8-f44a-44e2-9238-977f7ae58427.png)

* Our web page consist of an interactive 'UFO Sightings' header that, when clicked, will return the page to it's default form and clear any filters. The page also has a dark background and with white text, which were customized using css styles and bootstrap. Underneath a banner reading 'The Truth is Out There' is a paragraph prompting us to consider our place in the universe due to UFO sightings. We can then see a table with UFO sighting data that is filterable. 
* To use the filters all you have to do is type in a specific date, city, state, country or shape of UFO in the respective search box.
  * ![Screen Shot 2022-06-19 at 4 43 47 PM](https://user-images.githubusercontent.com/96406929/174504840-3ddda4a3-df3d-4a96-a920-1a6f149da1da.png)
* Once filter critera is specified all you have to do is press enter. Below is an image of the web page returning data filtered after entering 'ny' in the state category 
  * ![Screen Shot 2022-06-19 at 4 50 23 PM](https://user-images.githubusercontent.com/96406929/174504921-c37a4a2f-0029-4405-bceb-5a4d558460ff.png)

## Summary
One draw back of this webpage is that applied filters have to specifically match values stored in the data.js file, meaning that if I was to type 'NY' instead of 'ny' on the "Enter a State" filter no values would be returned. For this reason I would reccomend a change where the stored data used to create the table is cleaned up and that the search parameters could be a bit more flexible. Another reccomendation would be to make the table filterable by drop downs on the table it self, giving users more options to explore it. 
