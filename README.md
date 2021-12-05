# OBS Studio Gstreamer plugin

## VA-API Hardware acceleration

If VA-API hardware acceleration is required, the flatpak `org.freedesktop.Platform.GStreamer.gstreamer-vaapi`is required.

To check if the encoder or decoder has been installed you can do it by running `gst-inspect-1.0 | grep vaapi` on bash inside the Flatpak

## Notes

There are some issues with bitrate setting not being respected, which may end up producing higher bitrates than intended.
