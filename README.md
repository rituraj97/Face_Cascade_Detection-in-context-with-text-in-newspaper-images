# Face_Cascade_Detection-in-context-with-text-in-newspaper-images
Take a ZIP file of images and process them, using a library built into python. The files in the ZIP file we provide are newspaper images. Your task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". This will test your ability to learn a new (library), your ability to use OpenCV to detect faces, your ability to use tesseract to do optical character recognition, and your ability to use PIL to composite images together into contact sheets.


Libraries used:
1) zipfile (for extracting zip file)
2) opencv (for face cascade classifier)
3) tesseract (for optical character recognition)
4) PIL (for building contact sheet to display faces)
