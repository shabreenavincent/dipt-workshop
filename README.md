# REG NO: 212222230141
# NAME:SHABREENA VINCENT

# Working on Images
My submission
Instructions for submission 
1. The image should be a plant, Tree, flower or building

2. The filename should be username.jpg

3. The image should be Converted to gray scale and HSV 

4. Display the H, S and V planes



## Program:
# Convert to Gray Scale and HSV:
```
import cv2
image = cv2.imread('Screenshot 2024-03-08 092502.png')
grayscale_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
hsv_image = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)
```

## ORIGINAL OUTPUT:




![florals 💐🌸](https://github.com/shabreenavincent/dipt-workshop/assets/119475721/0db0c8e9-27c4-4777-8f43-ea3eaf069285)


# Display H, S, and V Planes:

```
h, s, v = cv2.split(hsv_image)

# Display the H, S, and V planes
cv2.imshow('Hue', h)
cv2.imshow('Saturation', s)
cv2.imshow('Value', v)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
# OUTPUT:




![Screenshot 2024-03-08 202148](https://github.com/shabreenavincent/dipt-workshop/assets/119475721/b7d8badd-f519-4b37-9822-b38abe1f58f8)





![Screenshot 2024-03-08 202159](https://github.com/shabreenavincent/dipt-workshop/assets/119475721/6bf27d51-d055-4cd3-b0ed-d081ea61b33c)




![Screenshot 2024-03-08 202212](https://github.com/shabreenavincent/dipt-workshop/assets/119475721/326a6a6a-3c50-49bb-9d3f-2c07ff8c4635)





# Save the Processed Image:
```
cv2.imwrite('username_gray.jpg', grayscale_image)
cv2.imwrite('username_hsv.jpg', hsv_image)

```
# OUTPUT;





![Screenshot 2024-03-08 202255](https://github.com/shabreenavincent/dipt-workshop/assets/119475721/7da35b79-411f-44de-b983-3523a76186f2)


