Landing Page Project: My first JS project.
HTML, CSS and Javascript.

1- Firstly I started by creating the navbar by first defining my global variables 
  - making the navbar I looped over sections and created a new li and anchor for each section
  - creating a document fragment and appending the new (li) to it 
  - appended the fragment to the UL item 
  - afterwards I checked the browser and only saw a white line in place of the nav-bar and then realised there was an exisitng class of css that needed to be linked to the Li and then I linked it.
  
2- adding an event listener to li so that each section I clicked on the navbar took me to it's appropriate section
  - after checking the browser for changes I found out that after clicking the navbar it did not scroll to the section related to the click but instead jumped to it instantly, even though I added the scroll 'behavior: smooth' to the event listener... later testing I found out that I had to enable smooth scrolling inside "chrome://flags" then it worked.

3- creating an active_section and an active_link
  - decided to go with the getBoundingClientRect 
  - adding eventlistener scroll and then looping over section to check if they're in the viewport
  - I first went with innerHeight + 100" but then found its better to just check the top value isntead
  - also inner height somehow got in the way of scrolling to section on click instead of taking me to the top of the section on small screen I found myself in the middle of the section.
  - with looping over sections done I started another loop to get the active link.

4- adding a back to top button
  - I took some help from w3schools
  - added html button and css styling
  - linked them to Javascript scroll event to show back to top button after scrolling 
  
  with that i decided to do some finshing touches and hopefully writing this readme file for the first time is not the worst reading experience.(sorry).
