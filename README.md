# core-websocket
A polymer websocket adapter that provides a declarative way to drop 
reconnecting websockets onto a page.  If multiple URLs are provided, 
the socket will automatically connect to the fastest and roll through
them in the event that a connection is lost.

To see the events, attributes and methods exposed, take a look at the
source literate coffee files [here](src/core-websocket.litcoffee "Events, Attributes, and Methods")
