### we need more data
### we need more data
### we need more data

I only used a few data to test whether codes run normally. Folders as *Gauva* and *Jamun* are not needed (we do need Chinar though). They are just for testing.

WE NEED TO:
- Add more classes. To make this project worthy, we need to add those tree types (at least 5 of them):
    - Chinar
    - Camphora
    - Osmanthus
    - Ginkgo
    - Elaeocarpus sylvestris
    - Bamboo
    - Cycas revoluta
    - and more
- Add more images. For each tree type we added, we need to add **at least 2000** images (one or many leaves in an image is ok) of images, the more the better. We can download images in batches from Google or Biying but we need to filter those images mannually so we can be sure those images are from the exactly tree type.
- Resize all our images. we need to resize all our images to the same size. I've already written codes in utils.ipynb so we just need to change the folder name and we can resize all images from *./src/certain tree type/* folder to *./data/train/certain tree type/* folder. Default image size is 224x224. Read those codes can save you a lot of time from resizing.
- Split some images(224x224) to *./data/test/* folder with the same folder structure under *./data/train/*.
- The baseline project repo won't contain any images. We need to find a way to gather all images we find as group work so someone can train the model with all our images all together (Maybe we directly use github?). 

I suggest to search those tree leaves and download them in batches so we only need to filter them. GOOD LUCK EVERYONE!!! I will do some work in my spare time too.