## extractImages.py
### Utility for Video-2-Image converter : Extract every nth frame from a video input file

### usage: pytjhon extractImages.py --pathIn PATHIN --pathOut PATHOUT [--every EVERY]

For eg., python extractImages --pathIn .\datasets\*.mp4 --pathOut .\test_frames\extracted_ --every 5

arguments:
  -h, --help         show this help message and exit
  --pathIn PATHIN    path file pattern to video. For eg. .\datasets\*.mp4
  --pathOut PATHOUT  path to store extracted images with file prefix. For eg.,
                     . est_frames\extracted_
  --every EVERY      every nth frame to be captured.
***
## labelme2coco.py
### Utility to convert labelme annotation file to coco format annotation file

### usage: labelme2coco.py [-h] --labelme_images LABELME_IMAGES --output OUTPUT

optional arguments:
  -h, --help            show this help message and exit
  --labelme_images LABELME_IMAGES
                        Path to a folder containing labelme-images and
                        labelme-annotation-json-files.
  --output OUTPUT       Output json file path.
