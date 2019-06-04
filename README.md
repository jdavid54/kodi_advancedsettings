#Links

    ref : https://kodi.wiki/view/Advancedsettings.xml#cache

    ref : https://kodi.wiki/view/HOW-TO:Modify_the_video_cache

2.8.4 cache

 
   memorysize=0                          <!--
    
    Number of bytes used for buffering streams in memory . Can be 30% of available memory in bytes

    When set to 0 the cache will be written to disk instead of RAM -->
    
  buffermode=0,1,2,3                      <!-- 

     Choose what to buffer:

     0) Buffer all internet filesystems (like "2" but additionally also ftp, webdav, etc.) (default)
     
     1) Buffer all filesystems (including local)
     
     2) Only buffer true internet filesystems (streams) (http, etc.)
     
     3) No buffer -->
     
  readfactor=4.0                          <!-- 

     This factor determines the max readrate in terms of readfactor * avg bitrate of a video file. 

     This can help on bad connections to keep the cache filled. It will also greatly speed up buffering. Default value 4.0. -->




# kodi_advancedsettings

## what is this for

this release fix the addon from repo : http://toptutorialsrepo.co.uk/kodi

the file advancedsettings is created but never be updated with the 3 items (buffermode, memorysize and readfactor)
due to bad regex patterns in buildsection and write_xml functions

## how to use this

Download and install in kodi as zip file
