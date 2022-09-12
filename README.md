# Disable-Blue-Highlight-when-Touch-Press-object-with-Cursor-Pointer


## There is a blue highlight that appears whenever a Div that has the cursor:pointer property applied is touched in Chrome. How can we get rid of it?

button, textarea, input, select, a, html, body, *{
     -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
     -webkit-tap-highlight-color: transparent;
     -webkit-user-select: none;
     -khtml-user-select: none;
     -moz-user-select: none;
     -ms-user-select: none;
      user-select: none;
      }
