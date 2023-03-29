#Background-image
    
    the background-image property repeats an image both horizontally and vertically by default

#syntax

    .container{
        background-image: url("saksham.png");
    }

    Specifies the URL of an image to be used as the background. You can use a relative or absolute URL.
#background-repeat

    Determines how the background image should repeat. It can be set to repeat, repeat-x, repeat-y, or no-repeat.

    background-repeat:no-repeat;
    background-repeat:repeat-x;


#background-attachment  

    Determines if the background image should be fixed or scroll with the content. It can be set to scroll or fixed.

    background-attachment: fixed;

#background-position
     
     Specifies the starting position of the background image. It can be set to a keyword (e.g. center, top, left)
#shorhand-property

    You can combine these individual properties into the shorthand background property. Here is an example:

    background: #ff9a8d url(./back1.webp) no-repeat center fixed ;
