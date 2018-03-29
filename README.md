## Description
This is a shell script that can create a bunch of static high resolution ads for Sizmek.

## Dependencies
The script has just one dependency which is [imagemagick](http://imagemagick.org).

## Usage
- Make it executable by running ```$ chmod 777 make-static-ad```
- Copy the script into /usr/local/bin/ to make it accessible from anywhere in your system  
```$ cp make-static-ad /usr/local/bin/```
- Just place your images (jpg, jpeg, png) into an empty folder and run the script
- You can supply the script with a prefix, which will be assigned to each ad, by passing it as an argument

## Example
```
$ ls -1
my-300x250-image.jpg
my-unknown-size-image.png
$ make-static-ad my-new-awesome-ad-
...
$ ls -1
my-new-awesome-ad-160x600
my-new-awesome-ad-160x600.zip
my-new-awesome-ad-300x250
my-new-awesome-ad-300x250.zip
```
