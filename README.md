Raw fritzbox audio files use a modified speex codec. 

This utility has been modified as in 

https://www.ip-phone-forum.de/threads/fritz-box-anrufbeantworter-encoder-decoder.156186/

to decode fritzbox speex files



from speexdec-fb/doc/manual.pdf :

Compiling Speex under UNIX/Linux or any other platform supported by autoconf (e.g. Win32/cygwin) is as easy as typing:

% ./configure [options]

% make

% make install

The options supported by the Speex configure script are:

–prefix=<path> Specifies the base path for installing Speex (e.g. /usr)
  
–enable-shared/–disable-shared Whether to compile shared libraries

–enable-static/–disable-static Whether to compile static libraries

–disable-wideband Disable the wideband part of Speex (typically to save space)

–enable-valgrind Enable extra hits for valgrind for debugging purposes (do not use by default)

–enable-sse Enable use of SSE instructions (x86/float only)

–enable-fixed-point Compile Speex for a processor that does not have a floating point unit (FPU)

–enable-arm4-asm Enable assembly specific to the ARMv4 architecture (gcc only)

–enable-arm5e-asm Enable assembly specific to the ARMv5E architecture (gcc only)

–enable-fixed-point-debug Use only for debugging the fixed-point code (very slow)

–enable-epic-48k Enable a special (and non-compatible) 4.8 kbps narrowband mode (broken in 1.1.x and 1.2beta)

–enable-ti-c55x Enable support for the TI C5x family

–enable-blackfin-asm Enable assembly specific to the Blackfin DSP architecture (gcc only)

–enable-vorbis-psycho Make the encoder use the Vorbis psycho-acoustic model. This is very experimental and may be
removed in the future.
