                               
                                     < A multi-modal video-RAG based on Python and videodb library >
                                                   Dr. Ing. Ashkan Mansouri Yarahmadi


- The videodb along with Python are used to design a RAG-multi-modal-system on our own captured video.

- Our video contains of three scenes, where each scene contains objects of different colors.
  
- The motivation is to query our video, using text queries describing the colors of the objects.

- The video is indexed and segmented into sub-videos, each of length 2 seconds.

- The designed RAG searches the video to find the scene that visually aligns with the text query.
   
### The devised pipeline :

To briefly visualise our original video that we are going to search through it, let us take three frames from it shown below :

<p align="center">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-1.png" width="256" height="512">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-2.png" width="256" height="512">
  <img src="https://github.com/ashkanmy/Insight-Gallery/blob/main/Figs/lego-3.png" width="256" height="512">
</p>

Note, the entire video is comprised of three above frames, but the objects are moving as time evolves (See the entire video as the link at the bottom of this page).

Next, the original video is segmented into sub-videos each of length two seconds and later is indexed using videodb framework. Now that our video is segmented and 
indexed, we can write text based queries and expect a particular segment from video to be shown to us such that it fully represents our text query. We opt to write 
below queries Q1, Q2 and Q3 :

- Q1 : Show me a scene that contains a yellow, a purple and a green lego.

- Q2 : Show me a cylindrical object in yellow.

- Q3 : A green big lego with two other small legos located on it.

As a result, the indexed video is searched and frames corresponding to Q1, Q2 and Q3 are shown (See the video-link below).

## Link to video :
https://vimeo.com/1050536287?share=copy
