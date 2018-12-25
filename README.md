# downlaod-imagenet
python3 script to download image net data just using the links 

First run the bash script using
>>bash get_data.sh

By Default it will download falls-11 dataset you can change it altering the link in the bash script.
If you do so dont forget to do the same in both the remaining python scripts from falls_11url.txt to 
the new txt file which was unzipped.


use the browse_classes.py to select the choose among the classes you want.

next use download_image.py to download image using the syntax----
>>python download_image.py -c class_names -n no_images -o output_folder_name


You can also write random_10 to randomly choose 10 different classes to out of 1000 classes from imagenet 
data.
>>python download_image.py -c random_10 -n no_images -o output_folder_name

To download all images of class you can use :
>>python download_image.py -c random_10 -n all -o output_folder_name

output folder name defaults to ILSVRC and classes defaults to random_10.
-n has to be provided always.

##Acknoledgement:
akshaychawla for your repository on the same. I have tried to make it way more user-friendly and removed all 
the issues and errors from the and made it python 3 compatible.

