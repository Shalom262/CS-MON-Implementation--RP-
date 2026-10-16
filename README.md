# CS-MON Implementation

## Dataset

The image dataset is not stored in Git because it is approximately 2 GiB. Place
the project images in a `Dataset/` directory at the repository root; the
notebooks load images from that location and use the tracked `details.csv`
metadata file. Obtain the images separately from the authorized project
dataset source.

`Dataset/` is ignored by Git, so adding the files locally will not add them to
the repository or its pushes.
