xcorder
=======

X Window Recording Tool

ffmpeg configuration
--------------------
The ffmpeg build configuration requires the following for xcorder to work properly:
> `--extra-libs=-lasound` or `--enable-libpulse`

and

> `--enable-x11grab`
