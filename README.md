This the repository for MasterMind Tree Classifier.

This file should be in the direct child folder of *TreeClassifier*.

- train.ipynb: contains all the codes you need to train a deep learning model.
- utils.ipynb: contains others codes need for this project. Currently it's only for image resizing.
- see README.md under each child folder to know what it holds. **Please read them**.

The folders under *./data/train/*, *./data/test/* and *../src/* is the standard folder structure for image data. As you can see we should make all folders in 3 folders above as the same. And each folder should contains all the images we need for this kind of tree, whose name is exactly the name of this folder. Otherwise *train.ipynb* won't work normally.

Image data folders are not uploaded. If your want to know where to put your image data in this project, see the image below:

![example](https://github.com/EMUNES/MS-TreeClassifier/blob/main/folder%20structure%20example.PNG)

After all, each folder stands for a certain type of tree and holds all the images (leaves images) for that tree. You need to make sure in *data/train/*, *data/test/* and *src/* there are the same folders.
