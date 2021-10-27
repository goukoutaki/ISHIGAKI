<H1>OpenISHIGAKI Dataset</H1>


<img src="./IIDAMARU/H268/measure/0001/image_L.jpg" width=200><img src="./IIDAMARU/H268/measure/0002/image_L.jpg" width=200><img src="./IIDAMARU/H268/measure/0003/image_L.jpg" width=200><img src="./IIDAMARU/H268/measure/0004/image_L.jpg" width=200><img src="./IIDAMARU/H268/measure/0005/image_L.jpg" width=200>




# IIDAMARU dataset


・<a href="http://navi.cs.kumamoto-u.ac.jp/~koutaki/ISHIGAKI/H268.zip">H268: 250 stones (H268.zip 1.2GByte)</a> 

・<a href="http://navi.cs.kumamoto-u.ac.jp/~koutaki/ISHIGAKI/H269.zip">H269: 120 stones (H269.zip 458MByte)</a> 

# File structure
The data is hierarchically organized as follows.

　ISHIGAKI->Face ID->database or measure -> stone_ID 

One folder contains the data for one stone.
The same Stone ID with the same Face ID means the same stone.
This is the result of mapping by the stonemason.


<img src="./structure.png" width=400>

## Files before the collapse of each stone
Includes image data and 2D contour data (unit: mm) before the collapse. Position data before the collapse is also available.

<img src="./before.png" width=400>

## Files after the collapse of each stone
Includes stereo image pair, reconstructed 3D obj model, and 3D contour data (unit: mm) after the collapse. GPS Position data after the collapse is also available.

<img src="./after.png" width=700>


# All files
http://navi.cs.kumamoto-u.ac.jp/~koutaki/ISHIGAKI/

