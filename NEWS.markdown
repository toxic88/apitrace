This file lists the major user visible improvments.  For a full list of changes
and their authors see the git history.


Version 3.0
===========

* Top-level `apitrace` command.

* Trace and retrace support for EGL, GLES1, and GLES2 APIs on Linux.

* Ability to trim traces.

* Basic CPU profiling when retracing.

* Basic D3D10 trace support.

* Many bugfixes.


Version 2.0
===========

* Flush/sync trace file only when there is an uncaught signal/exception,
  yielding a 5x speed up while tracing.

* Employ [snappy compression library](http://code.google.com/p/snappy/) instead
  of zlib, yielding a 2x speed up while tracing.

* Implement and advertise `GL_GREMEDY_string_marker` and
  `GL_GREMEDY_frame_terminator` extensions.

* Mac OS X support.

* Support up-to OpenGL 4.2 calls.

* Better GUI performance with very large traces, by loading frames from disk on
  demand.


Version 1.0
===========

* Qt GUI, capable of visualizing the calls, the state, and editing the state.


Pre-history
===========

* OpenGL retrace support.
