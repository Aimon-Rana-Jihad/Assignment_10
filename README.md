# Assignment 10

# **Filtering image collection in GOOGLE EARTH ENGINE**
## **Making RGB image composite from image collection:**
I used "**Harmonized Sentinel-2 MSI: MultiSpectral Instrument, Level-2A**" dataset for this task.I imported the previously uploaded "**Administrative Boundary Of Bangladesh**".Then printed my desired upazilla "**Fatikchhari**".After that,i filtered the dataset by boundary,date and image property.Then i made a composite image from all the filtered results.To get an RGB composite,i selected "**B4**","**B3**","**B2**" as bands in visParams.This is the result i got:


*   [GEE LINK](https://code.earthengine.google.com/4adb602bab1b7e24af1af7cc89c9443c)
*   [Screenshot LINK](https://github.com/Aimon-Rana-Jihad/Assignment_10/commit/ed73a094b7dea6ebec9bd7c0a296ba3a595feba7)




## **Making False Color composite from image collection:**
Here,i selected "**B8**","**B4**","**B3**" as bands in visParams.Other procedures are as same as i did  while making the RGB composite.And this is what i got:


*   [GEE LINK](https://code.earthengine.google.com/d05064248fca80542ab7498d7a49507a)
*   [Screenshot LINK](https://github.com/Aimon-Rana-Jihad/Assignment_10/commit/227df943aef253b4ecf3097241089e8d631e14db)



## **Figuring out capture date of an image:**
At first,i got 1 point then filtering this by boundary,date and image property.Then i selected one image out of those 10 results.Finally,found out the capture date of that image.The result is:



*   [GEE LINK](https://code.earthengine.google.com/0583d5dd9a39dc6bfe2a9255136d3033)
*   [Screenshot LINK](https://github.com/Aimon-Rana-Jihad/Assignment_10/commit/9c211fd2de7b8131c723a1fe5a7f198065052c4b)

