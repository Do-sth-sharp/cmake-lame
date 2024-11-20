# cmake-lame
Use CMake to compile LAME library.

## Platform support
- Windows (MSVC)
- Windows (MinGW)
- Linux (GCC)

## Target support
### Windows
- lame.exe - OK (Without NASM and libsndfile)
- mp3x.exe - ERROR (No GTK Lib)
- mp3rtp.exe - OK (Without NASM and libsndfile)
- lame_enc.dll - OK (Without NASM and libsndfile)
- mp3lame.dll - OK (Without NASM and libsndfile)
- mp3lame-static.lib - OK (Without NASM and libsndfile)
### Linux
- lame - OK (Without NASM and libsndfile)
- mp3x - ERROR (No GTK Lib)
- mp3rtp - OK (Without NASM and libsndfile)
- lame_enc.so - NOT SUPPORTED (Windows only)
- mp3lame.so - OK (Without NASM and libsndfile)
- mp3lame-static.a - OK (Without NASM and libsndfile)
