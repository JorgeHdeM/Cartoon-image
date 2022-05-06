This code runs in a GPU if its available, it took 5-10 minutes in a GTX 1660Ti
If there are no CUDA cores available, it will run in the CPU but it will take FOREVER.

VGG architecure was used to extract one image shape and merges it with another.

TO MAKE IT WORK:
Change line 52 'load_img_name' and change it four your desired picture which needs to be in 'images' folder alongside the style picture which is 'mariana.jpg'.
