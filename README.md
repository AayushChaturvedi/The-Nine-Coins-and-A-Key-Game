# The Nine Coins and A Key Game

To play the game:

1. Download/Clone this repository and save the folder at recognised place in your system.
  let's suppose that folder is saved in as Documents/game directory

2. Launch a local Server
    If you have Node, simply type the following in the command line
    ```
        npm -g install http-server
        cd Documents/game
        http-server
    ```
    If you have Python, type the following in the command line
    ```
        cd Documents/game
        python -m SimpleHTTPServer
    ```
    Note : For some users, this may not work. For those who have python, and running the above command shows the error "No such     module found" use the following:
    ```
       python2.7 -m SimpleHTTPServer
    ```
3. The above step will display a PORTNUMBER where the system has set up a local server.
   In the browser, go to the URL : localhost:PORTNUMBER.
   For example, if your port has been setup at port 8000, go to 
   localhost:8000
   in your browser.

NOTE : 
  It has also came in observation that simply opening the index.html file does it in certain configurations. You may first like   to try that before following above procedure.
   
   
------------------------------------------------------------------ ENJOY THE GAME !!! ------------------------------------------------------------------
