# TDControl
TDController

Two pane controller: Tox Loader and Record/Playback control of saved animations.

Use:
Tox Controller Notes - 
  - All TOX files should be placed in the root/TOX folder
  - Naming convention for TOX files is crucial: each COMP type has a filter to only show the TOX files appropriate to that comp
 Tox Controller Selection -
  - Select any listed TOX and press the LOAD button. A confirmation box will appear.
  - If there is an issue, press the RE-INIT button
  - If new files are added to the TOX folder and do not appear in the list, press the FOLDER button to refresh the list
  
 Record/Playback - 
  - All .bclip files must live in the root/BCLIP folder
  - Shot and Take information is sent via external sources and cannot be manually entered
  
 Record -
  - Set a file name in the file prefix box.
  - Press SET to begin the process. This stops the Timeline and prepares the nodes for recording.
  - When all is ready, press ACTION to begin the recording. The RECORD MODE button will flash.
  - The indicator frame at the bottom will show the incoming data in Trail form
  - Press CUT when finished. This saves the incoming data to  [filePrefix+Shot#+Take#.bclip] with a confirmation box.
    
Playback - 
  - Choose a file to playback via the BCLIP box. You may need to navigate to the correct folder but it should retain that information after the first file load.
  - Press PLAYBACK MODE to run the file. Current settings allow the file to loop.
  - The indicator frame at the bottom will show the outgoing data in Timesliced form.
  - Press PLAYBACK MODE again to stop.
