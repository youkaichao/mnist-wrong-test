# images in MNIST test set with wrong labels



## file name format in wrongImages directory

id-label.jpg

id: [0, 10000), int

label:[0, 10), int

## explanation for wrongImagesInMNISTTestset.csv

the correction may be one of the following values:

**-1:**  we think the image should be discarded. No labels can be attached to it.

**a or b:**  we think the number in the image is ambiguous. Both a and b can be the label of the image.



## contribution

we find 70+ test images with not appropriate labels. Given that the state-of-the-art is often 99.5+%, we think these state-of-the-art results may need to be re-run.



 