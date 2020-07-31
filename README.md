# Recipe-finder
Link to working version: https://xiongkb.github.io/Recipe-finder/  

Ever feel hungry and don't know what to cook with your leftover? Enter an ingredient or more and the program will look for recipes based on those ingredients for you.

How it works?
Our team used edamam api to call for its database of recipes based on ingredients input by the user. By entering one ingredient at a time, it gets added to an array where once user clicks enter, it will do a ajax call to the edamam api database. From there, it will display the first 3 recipes it finds onto the html. User can clear the array if they would like to add different kind of different by clicking on the clear button. 

Technologies used:
We used materialize to help with styling and certain button animetions. Jquery, html, and additional css were used to create this app.
