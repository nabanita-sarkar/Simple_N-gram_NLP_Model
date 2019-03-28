# New-Project
import numpy as np
import cv2
import matplotlib.pyplot as plt

#reading the image

image = cv2.imread('index.png')
image = cv2.cvtColor(image,cv2.COLOR_BGR2RGB)
#plotting the image
plt.imshow(image)

#saving image
cv2.imwrite('test_write.jpg',image)
