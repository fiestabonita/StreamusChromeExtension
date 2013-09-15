Streamus™
=========

A Google Chrome extension which allows users to add YouTube videos to playlists, share playlists and discover new YouTube videos.

Overview
========

Streamus consists of a front-end client, the Google Chrome extension, a back-end server ("Streamus Server"), server test cases ("Streamus Server Tests"), and a website. This repository contains the files for the Google Chrome extension. Please see the other repositories, StreamusServer and StreamusWebsite, to gain a full understanding of the product.

Client
------

The Google Chrome extension utilizes the following libraries: 

* [jQuery (v2.0.3+)](http://jquery.com/)
* [jQuery UI (v1.10.3+)](http://jqueryui.com/) [AutoComplete and Sortable modules only]
* [BackboneJS (v1.0.0+)](http://backbonejs.org/)
* [RequireJS (v2.1.8+)](http://requirejs.org/)
* [UnderscoreJS (v1.5.1+)](http://underscorejs.org/)
* [Jasmine (v1.5.8+)](http://pivotal.github.io/jasmine/) [Coming soon...]

Installation
========

1. Navigate to the page: chrome://extensions
2. Check the checkbox 'Developer mode.' This will introduce several new buttons to the chrome://extensions page
3. Click the button 'Load unpacked extension...'
4. Select the StreamusChromeExtension directory, click OK.
5. The extension should now be loaded and ready to be interacted upon.

* NOTE: StreamusChromeExtension is dependent on a server. If you wish to debug without a local server instance you will need to set the property 'localDebug' to false. To do so, navigate to: 'StreamusChromeExtension/js/background/model/settings.js"

Supported Functionality
========

* YouTube search
* Add YouTube video to playlist
* Add YouTube playlist as playlist
* Add YouTube channel as playlist
* Play, pause, skip, rewind, shuffle, repeat video, repeat playlist
* Radio / Discovery
* Desktop notifications of currently playing video
* Customizable keyboard shortcuts to control play, pause, skip, previous
* Sharing of playlists via URL
* Enhancement of YouTube video pages with injected Streamus HTML
 
Usage Demo
========

A video explanation of how to use Streamus can be found at:
* "Streamus - Stream Bar Preview" - http://youtu.be/wjMLQWGYGOc

License
=======
This work is licensed under the GNU General Public License v2 (GPL-2.0)

Authors
=======

* MeoMix - Original developer, main contributor.
* Misostc - Phenomenal user interfactor designer.
* MiracleBlue - Brought on as a second developer to help with work load.
