CC = g++
FILES=main.cpp

exemplo: clean
	$(CC) -I/usr/local/include -I/usr/local/include -L/usr/local/lib/ -g -o app $(FILES) -lopencv_calib3d -lopencv_core -lopencv_features2d -lopencv_flann -lopencv_highgui -lopencv_imgproc -lopencv_ml -lopencv_objdetect -lopencv_photo -lopencv_stitching -lopencv_superres -lopencv_ts -lopencv_video -lopencv_videostab

clean:
	- rm app
