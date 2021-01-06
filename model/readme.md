In order to run the demo, you will first need to download the pre-trained data from this location.  Place the file in the folder with this readme.

python main.py --image grey.jpg --prototxt deploy.prototxt --model colorization_release_v2.caffemodel --points pts_in_hull.npy
python main.py --prototxt model/colorization_deploy_v2.prototxt --model model/colorization_release_v2.caffemodel --points model/pts_in_hull.npy --image grey.jpg
[INFO] loading model...