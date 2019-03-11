# What is the features branch?
The features branch (as the name implies and as you might have read from the master branch readme) is a seperate branch for adding basic features, such as boardlinks. If i feel brave and competent enough, i might add more complex features, such as custom capcodes.

I've tested this branch and it works fine, however i will still add a disclaimer that this might be more unstable than the master branch.

# How to use banners and boardlinks
Banners: replace all the images in bimg/ with your own banners. The filename does not matter, as the banner script (boardimg.php) pulls a random image from the bimg folder. make sure the dimensions are 300x100.

Boardlinks: modify line 1265 to link to boards you have created. to make boards, make a new folder with the boardname, put in the 3 php files and then link to the folder. this does require to modify the futaba.php in every single board, but it shouldn't be a big hassle if you don't have over 9000 boards.
