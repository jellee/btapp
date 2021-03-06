[Documentation](http://pwmckenna.com/projects/btapp/documentation.html "documentation")  
[Annotated source code](http://pwmckenna.com/projects/btapp/backbone.btapp.html "source")  
  
#backbone.btapp.js
backbone.btapp.js is an extension built on Backbone.js that keeps an up-to-date representation of your uTorrent client's state/torrents/etc. It runs in your browser and can connect to an arbitrary number of clients on your local machine, or remotely through uTorrent/BitTorrent's remote feature.

__Dependencies__:  
[jquery](http://jquery.com/ "jquery")  
[jquery json](http://code.google.com/p/jquery-json/ "jquery json")  
[underscore](http://documentcloud.github.com/underscore/ "underscore")  
[backbone](http://documentcloud.github.com/backbone/ "backbone")  
  
  
#plugin.btapp.js
plugin.btapp.js is responsible for ensuring that a client is run on your local machine. It provides a default install experience for the browser plugins that will in turn install/run uTorrent/BitTorrent as needed. Do not include if your app doesn't require a client running on the local machine. Keep in mind that you don't need the dependencies. You're more than welcome to style the dialog to your taste. The goal is simply to get the client on the local machine so you can get back to programming and assuming its there.

__Dependencies:__  
[bootstrap-modal](http://twitter.github.com/bootstrap/javascript.html#modal "bootstrap modal")  
[bootstrap css](http://twitter.github.com/bootstrap/1.4.0/bootstrap.min.css "bootstrap css")  
  
  
#Authors

Patrick Williams  
http://github.com/pwmckenna
  
Kyle Graehl  
https://github.com/kzahel
  
  
#License
  
Copyright 2012 BitTorrent, Inc.  
Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0