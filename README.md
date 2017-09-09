# Face_reco_scripts
<h2> Generalities

python scripts for (basic) face recognition

<ul>
<li> python 2.7+, cv2
<li> uses haarcascades xml files
<li> reco_face_static.py, reco_face_video.py
</ul>

<h3> static
reco_face_static.py takes 2 arguments : 
<ul>
<li>the first one is the path to an haarcascades xml file for default face. 
<li>The second argument is the path to a picture.
<li>The script makes a copy with faces recognized (overlay green rectangle)
</ul>

<h3> dynamic
reco_face_video.py
<ul>
<li> loads your webcam and recognize faces, eyes 
<li> overlay with color rectangles
<li> esc to close /stop the script
</ul>








