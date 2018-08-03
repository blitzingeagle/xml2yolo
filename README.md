# xml2yolo

Converts PascalXML format to YOLO format for all `.xml` files in a directory.

## Usage
```{bash}
python xml2yolo.py
```

The program will prompt for the following information: the directory containing XML files, the location to place `classes.txt`, and the image file extension. (Note: `classes.txt` can pre-exist, in which case the program will load those key values and update it in its output.)

```{bash}
Directory path with XML files: voc
File containing classes: classes.txt
Image file extension: .jpg
```
