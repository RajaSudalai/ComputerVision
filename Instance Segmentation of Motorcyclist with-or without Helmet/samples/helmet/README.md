# Instance Segmentation model to detect Motorcyclist with-or-without Helmet

### To Train : 
##### current folder should be this helmet folder and conda environemnt should be currectly set

python helmet-json.py train --dataset="../../datasets/helmet" --weights==coco

### To run in inference mode to detect instance segmentation. 
Launch Spyder
Change current folder to this Helmet folder in spyder
Open helmet-json.py program in spyder 
Select 'Run' from spyder menu and select 'Configuration per file'
Enter 'splash --weights=last --image="path/to/image-input-file.jpg" in "Command line options:"
Run the program in spyder
