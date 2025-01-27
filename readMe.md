                               
                                     < A video-RAG based on Python and videodb library >
                                              Dr. Ing. Ashkan Mansouri Yarahmadi


- The videodb along with Python are used to design a RAG-system on our own captured video.

- The video contains of three scenes, where each scene contains objects of different colors.
  
- The motivation is to query our RAG based on text describing the colors of the objects.

- The video is segmented into sub-videos, each of length 2 seconds.

- The designed RAG searches the video to find the scene that visually aligns with the text query.
   
### The video to be searched

We select three frames from the video with each frame contains objects of different colors, namely Legos with different colors:

<p align="center">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-1.png" width="512" height="812">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-2.png" width="512" height="812">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-2.png" width="512" height="812">
</p>


## Link to video :
https://vimeo.com/1050536287?share=copy
