# Let's learn CSS Grid!

Clone this down to your local environment, and follow along. 


/*Add this code to rad.css at the bottom where it says to style the grid  */

#grid {
  display: grid;
}

/* 
  Answer using comments
  How many columns are in this "grid"?
  How many rows?
  How many items total are there?
  How wide is the column? (We're going for answers like "100%" or "fullscreen")
  How tall are the rows? (This is a good opportunity to look at the computed styles)
  */

/* add the following to the previous code*/
    #grid {
      display: grid;
      grid-gap: 8px;
      grid-template-columns: 250px auto 175px;
}

/* Predict
  How many columns will there be?
  How big will the first column be?
  How big will the last column be?
  How big will the middle column be?
  How many rows will there be?
*/
