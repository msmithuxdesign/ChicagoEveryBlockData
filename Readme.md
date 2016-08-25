# Chicago EveryBlock

**This project requires a Everyblock developer ID**

Once you have an API Key Edit the file global_vars.js

To run the project open up a terminal, browse to folder containing the project.
Start up a server
python -m SimpleHTTPServer 8001

Point a browser to localhost:8001

Data is slow to filter in and the requests eventually die because the recursive calls blow through the the JavaScript Stack.

After a little load time the project should look something like this:
![Screen shot of chicago map with everyblock data](/everyBlockChicago.png?raw=true )

Mark Smtih
mark@msmithuxdesign.com
www.msmithuxdesign.com
