https://github.com/HandBrake/HandBrake/issues/5003
rm -rf build
./configure --build=debug --force --disable-xcode --optimize=none --debug=max --enable-x265 --enable-fdk-aac --enable-libdovi
make -j16 -C debug