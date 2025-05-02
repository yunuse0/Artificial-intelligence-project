# Artificial-Intelligence-Project
## Codes for retrieving visual data from Google for Software Development Lab. course

**Project Summary:**
In our project, we first wrote the codes that allow us to retrieve the desired data from the relevant places. We used the Python language. The first code block we wrote is used to download images by scanning the relevant keyword in 'Google Search'.
The code block image in question:
![data retrieval part](https://github.com/user-attachments/assets/6ec6718e-cc6d-4f93-b9c9-788a116c0888)

We downloaded around 15,000 images with the keywords we selected using the relevant code. We edited the downloaded data, cleaned it and applied the necessary data processing steps.
We applied the data augmentation process by writing a python code again on the cleaned data we had.
The code block in question is visual (2):
![data processing and augmentation](https://github.com/user-attachments/assets/49fa1371-a7b5-4655-ad9a-b709d2f07af6)
The code block in the visual performs the operations of rotating, filtering and color editing the selected data.

**Usage of Codes and Program**
In the code blocks written for data provision, a keyword must be entered in the space in the 'query' tag. When the code is run, it opens a new tab with the entered keyword and pastes it into the 'Google Search' search bar, accessing the url addresses of the ''img'' tags on the source page. It downloads all the images in the accessed url addresses up to the target specified number. It performs 2-second scrolling operations for visual and ease of access. When the end of the page is reached, it prints the path of the folder containing the downloaded files in the form of a message and closes the tab. In this way, the process is completed.

In the code blocks written for data processing and augmentation, it needs defined input and output folders. We specify the path of the input folder before running the code and it applies the processing of the images in this folder as specified in the code blocks and the augmentation operations to the selected number. If there is an output folder, this is specified, otherwise, it automatically creates an output folder thanks to the written code section. It completes the process by saving the processed images to this folder.

