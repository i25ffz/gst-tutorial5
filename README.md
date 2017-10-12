# gst-tutorial5
GStreamer tutorial 5 for android.

### Run basic tutorial-5 on ubuntu:
```sh
sudo apt install libgtk-3-dev
sudo apt install libgstreamer-plugins-base1.0-dev
git clone https://anongit.freedesktop.org/git/gstreamer/gst-docs.git
gcc -Wall -o basic-tutorial-5 basic-tutorial-5.c $(pkg-config --cflags --libs gstreamer-1.0 gstreamer-video-1.0  gtk+-3.0)
```
