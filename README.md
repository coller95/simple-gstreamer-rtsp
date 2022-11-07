# simple-gstreamer-rtsp

g++ test.cpp `pkg-config --libs gstreamer-1.0 gstreamer-rtsp-server-1.0 gobject-2.0 glib-2.0` `pkg-config --cflags gstreamer-1.0 gstreamer-rtsp-server-1.0`


g++ test.cpp -L/opt/intel/openvino_2021/data_processing/gstreamer/lib/pkgconfig/../..//lib -lgstrtspserver-1.0 -lgstbase-1.0 -lgstreamer-1.0 -lgobject-2.0 -lglib-2.0 -pthread -I/opt/intel/openvino_2021/data_processing/gstreamer/lib/pkgconfig/../..//include/gstreamer-1.0 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include


export LD_LIBRARY_PATH=/home/ubuntu/gstreamer/builddir/subprojects/gstreamer/gst:/home/ubuntu/gstreamer/builddir/subprojects/gst-rtsp-server/gst/rtsp-server


g++ test.cpp -lgstreamer-1.0 -lgstrtspserver-1.0 -L/home/ubuntu/gstreamer/builddir/subprojects/gstreamer/gst -L/home/ubuntu/gstreamer/builddir/subprojects/gstreamer/libs/gst/base -lgobject-2.0 -L/home/ubuntu/gstreamer/builddir/subprojects/gst-rtsp-server/gst/rtsp-server -lgstbase-1.0 -lglib-2.0 -pthread -I/home/ubuntu/gstreamer/subprojects/gstreamer -I/home/ubuntu/gstreamer/builddir/subprojects/gstreamer -I/home/ubuntu/gstreamer/subprojects/gst-plugins-base/gst-libs -I/home/ubuntu/gstreamer/builddir/subprojects/gst-plugins-base/gst-libs -I/home/ubuntu/gstreamer/subprojects/gst-rtsp-server -I/home/ubuntu/gstreamer/subprojects/gstreamer/libs -I/home/ubuntu/gstreamer/subprojects/gst-plugins-base -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include 
