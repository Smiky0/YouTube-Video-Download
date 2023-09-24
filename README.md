# YouTube-Video-Download

**ABOUT:** The project aims to download YouTube videos on your local machine in best quality possible. It's a completely CLI based project it doesnt have and GUI version so you need to paste the link inside your terminal.

**DESCRIPTION**: I used a python library called pytube to fetch and download videos from youtube using youtube link. Also to download higher quality videos sometimes pytube wont let you download videos with audio files so the solution that I came up with is to download the HQ video and audio seperately then mix them together. In order to mix botht he audio and video file I used another library called moviepy which lets you merge audio and video files seperately.

 Links to library documentation: 
 1. PyTube: https://pytube.io/en/latest/
 2. MoviePy: https://pypi.org/project/moviepy/

**INSTRUCTIONS**: Simply clone the repo and run the python file you will be asked to put the youtube link after you paste that choose your desired options and download the video. Also if you want to change the download directory you can do so inside the code itself otherwise it will download file on your current directory.

PROS: 
1. Download audio files only
2. Download high resolution videos
3. Able to choose quality of video you want to download
4. Set your desired download directory

CONS:
1. There is no download progress bar while downloading audio or video file
2. While merging audio and video files it takes lots of time
3. Its totally CLI based so there is no easy GUI interface to work with
4. I'm a lil lazy to implement new features :(

***NOTE**: No promises but I will try to fix all the cons and make it more simple and fast in future so that you dont have to do any hassle whatsoever.

I hope my project helps you and if it does give a star or something.. Have a good day!
