Radio-IL: M3U Playlist for Israeli Radio Stations
---------------------------------------------------

This playlist is intended to be used with IPTVSimple PVR-addon for XBMC by afedchin but will work with any player that support m3u playlist (e.g. VLC).  
Logos for the stations available at https://github.com/xbmc-il/logos-il  

Installation instructions:   
* Download the logos from https://github.com/xbmc-il/logos-il/archive/master.zip and extract somewhere.  
* On IPTVSimple configuration choose the m3u (if downloaded) or enter the m3u link.  
* Choose the logos library.  

To stay updated please use the following links to the playlists:   
* Stations listing in Hebrew @ http://xbmc-il.com/radio-il.m3u  
* Stations listing in English @ http://xbmc-il.com/radio-il.en.m3u  

To stay updated when playing in VLC or any other m3u enabled player use the m3u files in the folder vlc.  

Limitatios:  
* When more than one pvr clients are enabled, XBMC will not show channels from a client that its initialization is cosiderably longer due to a bug in XBMC, for exmaple: IPTVSimple and Tvheadend, see: http://trac.xbmc.org/ticket/14498.  
* A local copy of the stations' logos need to be kept.  
* IPTVSimple doesn't support asx/asp so the streams links were extracted,  
   if the asx/asp contains a stream playlist and auto rotate between the stream then the transmission may cut off.  
* No epg is available currently.  
* IPTVSimple won't update m3u playlist over GitHub and Dropbox links.  


I'm a bit new to git and vcs but I'm always happy to get PR's,  
logos and new stations' stream url are welcome.  


