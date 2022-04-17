# image-to-lc3-converter
Credit: Khuong H. Nguyen
The program converts .bmp, .png, and .jpg images into lc3 codes.

Tutorial:
  Step 1: run the "image_to_lc3.exe" once to create "images" and "image_to_lc3" folders.
  Step 2: move the images want to be converted into the "images" folder. 
  Step 3: run the "image_to_lc3.exe" again, the codes will be save in "image_to_lc3" folder as format "<file_name>_<file_extension>_lc3.txt".
  Note: The program only converts .bmp, .png, and .jpg images, other than these will be ignored!
        The files must be less than 128x124 resolution, otherwise the files will be ignored!
        The images will be scaled down 8-bit color to 5-bit color!
        The program will overwrite the .txt file if they have the same <file_name> and <file_extension>!
        If the .txt files are not created corresponding to their images. Check the error.txt file for details!
