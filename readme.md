How to set this up:

to setup ubuntu:
-set up wsl (windows subsystem for linux)
-install ubuntu (wsl.exe --install ubuntu)

in ubuntu:
-install cmake (apt-get install cmake)
-install g++ (apt-get install build-essential) to test if installed correctly (g++ -version)
-install sndfile lib using
apt-get install libsndfile-dev
-install lame development tools using
apt-get install lame
apt-get install libmp3lame-dev (lame development tools)
-go to code directory
-make a new folder and name it 'build' (mkdir build)
-cd to build (cd build)
-cmake to build (cmake ..)
-run this command to compile and execute the code (make)
-then encode the files inside a folder using this command (./encoder <path-to-wav-files>) example: CINEMO_LOG=debug ./encoder ../wavfiles
