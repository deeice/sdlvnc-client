sdlvnc-client
=============

A frugal sdlvnc client for the zipit z2 based on the sdlvnc TestVNC.c code

This VNC client is specially tailored for the zipit z2.  It starts up in the console to get config info, and then switches to fullscreen SDL once the connection is made.  It supports panning and zooming, which are critical on the 320x240 pixel zipit screen.  It's also somewhat frugal with the memory, only allocating what's needed based on the size of the remote framebuffer.

