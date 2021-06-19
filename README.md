# YourMovie - CIM (Computerized-Integrated Manufacturing) project
A project that was done during a CIM course.<br>
In this project, based on streamlit platform, the user can make his own video by two possible ways:<br>
1. Drawings that will be processed in nVIDIA's GauGAN network (http://nvidia-research-mingyuliu.com/gaugan/)
2. Pictures that the user can upload<br>

If the user choose to process the drawings in the GauGAN network, the result will be a artificial nature movie. If he chooses not to do so, he can use his own uploaded pictures and make from them a video.<br>
Before processing the video, the user can choose to either enable subtitles or not (using a txt file or subtitles that were written within the program),<br>
and he can also choose whether to have soundtrack or not (using a mp3 file or a soundtrack from a youtube video, using pytube).<br>
Then, using opencv and moviepy, the program builds the desired video and lets the user to watch his just-created video.
