# fullin-release

#### Introduce

fullin player releases page

A music player that supports precise desktop lyrics, with smooth desktop lyrics that can be obtained by OBS live streaming software, and supports KRC and LRC lyrics

Before using this software, please install the LAVFilters decoder first

#### Changelog

##### 1.0.0

1.  fix: When maximizing window lyrics, the album cover does not fit for the window in time
2.  fix: When lyrics with read or translation switch to lyrics which no contain read or translation, dragging the progress bar will cause a crash
3.  fix: Failed to initialize the config of shortcut keys
4.  new: Double lines desktop lyrics support, you can switch between single or double lines, as well as alignment
5.  new: Desktop lyrics countdown, read, text, translation combination display function
6.  new: Window lyrics setting function
7.  new: Added specify additional lyrics directory, default priority matches the lyrics of the directory where the song is located, if the song directory cannot match and an additional directory is specified, the additional directory is matched
8.  new: Multiple lyrics switching function, click the KRC or LRC box behind the song title, you can click to select the retrieved lyrics, and the default song directory and additional directory each match up to 5 lyrics with the highest matching degree to the song name
9.  new: Now when dragging in songs, if there is a folder dragged in, all the songs in it will be automatically traversed
10. new: The playback mode adds once mode, that is, the current song stops when it finishes playing
11. new: Software icons and in-software images are all self-design
12. mod: Optimize window edge dragging
13. mod: Optimize the immediacy of cover switching
14. mod: Optimize the logic of the previous and next tracks

##### 0.1.0-pre3

1.  fix: Window lyrics cover is not centered and filled
2.  fix: A suffix problem when dragging songs into the list
3.  new: Customize the theme function and add two default themes
4.  new: Now you can directly click the progress bar to change the song progress
5.  new: Desktop lyrics alignment function
6.  new: Prompt to install LAVFilters when opening the software for the first time
7.  new: New traditional Chinese and English languages
8.  mod: Update \[src\live\next_song_notice.txt\] 15s before the end of the song

##### 0.0.0-pre1

1.  First release
