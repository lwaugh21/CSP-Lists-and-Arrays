# CSP-Lists-and-Arrays
Practice 

var itemIndex =0 ;
var myFavoritethings = ["chocolate", "dogs", "cookies"];
onEvent("Next", "click", function( ) {
  itemIndex=itemIndex + 1
  setText("text_area1",myFavoritethings[itemIndex] );
setText("label2", (itemIndex + 1) + "of" + myFavoritethings.length);
});
onEvent("add", "click", function( ) {
  
});

