# Currency-Detection-using-OpenCV


## ABSTRACT
• There are around 200+ different currencies used in different countries around the world. The technology of currency recognition aims to search and extract the visible as well as hidden marks on paper currency for efficient classification. 
• We proposed an automatic currency recognition system using a digital image processing methodology. The following project mainly focuses on the recognition of currency by its image.
• Currency Recognition and conversion system are implemented to reduce human power to automatically recognize the amount monetary value of the currency.
• Many times, currency notes are blurry or damaged; many of them have complex designs to enhance security. This makes the task of currency recognition very difficult. 

## INTRODUCTION
• All currencies around the world look totally different from each other.
• India being a tourist place there is an ever-existing problem of detection of currency for the non-native people.
• A currency detection system can solve their problem by making it easier for them to detect the currency.
• This system uses the Image Processing technique which is being trained on a dataset and further yields the result on the basis of best fits.
• The proposed system is based on image processing and makes the process robust and automatic.

## OBJECTIVE
The main objective of the project is to recognize currency using image processing technique.


## METHODOLOGY
• We used OpenCV3 - Python3 for programming. For Image Acquisition we used a scanner and pre-processed it - cropped it. This was included in our training set.
• For feature extraction and matching  we used OpenCV ORB, to extract keypoints and descriptors of images.
• To implement image processing techniques we used python as programming language because it is much easier to implement digital image processing by using python because of its predefined libraries and frameworks.
• We then set a threshold value to which we compare the number of matches (no. of matches> threshold), take the largest matching training image and yield it to be the matching one.
• Give input as an image (JPG/PNG/GIF format).
• Conversion of the image from BGR to Grayscale.
• The Binary Threshold value will be assigned with the pixels of a grayscale image.
• Match the grayscale image with the template image.
• If the image is matched with the trained data set then show the defined output. 
