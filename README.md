# Working-On-Images
# AIM :
To write a python program using OpenCV to convert image to gray and hsv. display the  H,S,V.
1. The image should be a plant, Tree, flower or building
2. The filename should be username.jpg
3. The image should be Converted to gray scale and HSV 
4. Display the H, S and V planes
## Software Used
Anaconda - Python 3.7
## Algorithm
## Step 1:
Use cv2.imread to read the image

## Step 2:
Use cv2.COLOR_RGB2GRAY to change the image into rgb to gray
## Step 3:
Usecv2.COLOR_RGB2HSV to change the image into rgb to hsv
## Step 4:
use cv2.split(hsv_image) to split the image.

## Step 5:
End the program.
## Program:
### Developed By: k Santhan Kumar
### Register No:  212223240065
# Program:
```python
import cv2
color_image=cv2.imread("USERNAME.jpg")
cv2.imshow("colorimage",color_image)
gray_image1=cv2.cvtColor(color_image,cv2.COLOR_RGB2GRAY)
cv2.imshow("RGB2GRAY",gray_image1)
hsv_image=cv2.cvtColor(color_image,cv2.COLOR_RGB2HSV)
cv2.imshow("RGB2HSV",hsv_image)
h,s,v=cv2.split(hsv_image)
cv2.imshow("H PLANE",h)
cv2.imshow("S PLANE",s)
cv2.imshow("V PLANE",v)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
# Output:
# Original Image:
![WhatsApp Image 2024-02-29 at 22 24 19_9b175438](https://github.com/SANTHAN-2006/Working-On-Images/assets/80164014/c361c21b-d8d4-44f1-ad87-f4bba2fe6e23)
# Hue(H):
![WhatsApp Image 2024-02-29 at 22 24 18_7e9ea054](https://github.com/SANTHAN-2006/Working-On-Images/assets/80164014/74b65c40-7dde-437e-81cd-0314d32a440b)
# Saturation(S):
![WhatsApp Image 2024-02-29 at 22 24 20_dc362f71](https://github.com/SANTHAN-2006/Working-On-Images/assets/80164014/53793d68-bb51-4ff9-b78d-77c5bdb08f38)
# Value(V):
![WhatsApp Image 2024-02-29 at 22 24 24_9f335482](https://github.com/SANTHAN-2006/Working-On-Images/assets/80164014/ac914951-b5ec-4cb0-a625-4862b8179d36)

# Result:
Thus the image is converted to gray scale and HSV using python and displayed successfully.


