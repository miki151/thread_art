# Thread art generator

Create thread art from any image.

![alt text](http://keeperrl.com/~michal/emilka.png)

To use this tool first you'll need to compile the Zenon compiler from https://github.com/miki151/zenon.

After that use the following command to compile:

/path/to/zenon main.znn --cpp="g++ -g -O3 -I/usr/include/SDL2" -lSDL2 -lpthread

And to run:

./main -path=image.bmp -numPoints=200 -length=1000 -min=100

* numPoints is the number of thread attachment points
* length is the number of thread segments
* min is a constant controlling the contrast of the image and can be tweaked for a better effect
