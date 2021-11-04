# node-red-examples
Look under "import". The examples supplied by node-red can be found there!</br>
I created the examples in this repository because I had problems with a number of packages / functions. </br>
I hope this will help you :-)

* ping_flow_with_dashboard</br>
    Ping Target, show Result in Dashboard
    
* screenshot_tesserract</br>
    Take Screenshot an analyse Text with Tesseract
    
* powershell_ping_with_dashboard</br>
    Ping Target over Powershell, show Result in Dashboard</br>
    -> You need to manually update powershell.js, cause the installed package has not the newest version

* powershell_with_much_sourcecode</br>
    Execute Scripts which are more than "One-Liners"


# HINTS
If an Package is newer on github than the installed package from npm you can do the following to update manually (hint from node-red Forum):

Install direct from github by going into your .node-red folder (that is important) and running</br>
npm install [Packagename] 

Example: npm install tobiassoltermann/node-red-contrib-powershell
