# Thumbor

The easiest way of testing out the capabilities of Thumbor is by using Docker.

To start Thumbor as a Docker Container on Windows, just enter the command below in a command prompt and test out use cases below.

`docker run -p 8888:8000 apsl/thumbor`

[Original Coffee Berries image](https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

## Changing its size

### 300px by 200px

[Coffee berries image with 300px by 200px](http://localhost:8888/unsafe/300x200/https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

### Proportional to the width

[Coffee berries image proportional to the width](http://localhost:8888/unsafe/300x0/https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

## Flipping the image

[Coffee berries image flipped](http://localhost:8888/unsafe/-0x-0/https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

## Filters

[Coffee berries filtered (brightness 50 | contrast 50)](http://localhost:8888/unsafe/filters:brightness(50):contrast(50)/https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

## Meta
[Coffee berries endpoint returns metadata](http://localhost:8888/unsafe/meta/300x200/https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Coffee_berries_1.jpg/1200px-Coffee_berries_1.jpg)

## Test 300px by 200px

[Person image](http://localhost:8888/unsafe/300x200/smart/https://www.euram.eu/JoshuaTree/Content/pictures/Bart.jpg)


