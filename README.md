ShowMessage
===========
screen shot: http://myteenatanwit.github.io/CssModalMessageBox

Very simple Css to get the modal message box. Often you find the JQ or JS or so. However, we do only CSS, and call it by JavaScript for the fun of it. The cute look of the dialog? yeap! you got it, from the game on my Iphone "clumsy Ninja". I like the message dialog in the game, so I made this one. 

#idea

1- We need to make a background layer covers the whole screen with the setting: position: fixed, top:0, left:0, width:100%, height:100%, margin:0, padding:0. It is transparent too. It is also visibility: hidden. When we show it, then everything behind this layer is inactive or it is becomes modal. 

2- We need our message box showing in mid of the screen, the simple way is set it margin: 60% auto, so it locate 60% from top and center itself in the midle. It must set position:relative so that we can control the inner elements.

3- We need a title, optional actually for it default is a dot. It located -10px from top due to position:absolute. You need to keep in mind that its parent position is relative, so it an be absolute. Try to change these position things in dialogs.css and you can see the boxes running around funny.

4- The graphic on the left of the msgbox is ugly. I tried to find the oldman head as in the game in vain with gg search "clumsy ninja sprites png", so I just put something there. If u got the right one, then just replace it, or do it with your own alpha one.

5- The msg box is dynamic height, so it will extend for longer message. Mind you, message box tend to be short and expressive. It is basically a short message, so you wouldnt put in there your whole thesis.

#Note
It is very simple code, read it then. The whole body of the box is only 6 lines. The function to call it is in pure JS only 3 lines. Therefore, I think it is not necessary to make a plug in.
