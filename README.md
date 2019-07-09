# Yolo-Annotation-Tool-New
To launch YATN just type.
```
python main.py
```
After launching choose the directory containing your YOLO dataset(the directory has to be located in the directory "Images").

Next run process.py:
```
python process.py -d dataset_images_dir
```
The script above will generate your train.txt file.

NOTE: If you use new annotation tool, please create classes.txt file and write all classes what you train the objects. Because i read the all classes from classes.txt.

The dataset is ready for yolo training.
