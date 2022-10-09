# CMAKE
Download 
```
wget https://github.com/Kitware/CMake/releases/download/v3.23.0/cmake-3.23.0.tar.gz
```
Remember to get the latest version, do not just blindly copy and paste!

Extract the archive contents using the following command.
```
tar -zxvf cmake-{version number}.tar.gz
```

Next, move CMake to the /opt/ location.
```
sudo mv cmake* /opt/
```
Now CD into the directory that was extracted.
```
cd /opt/cmake-{version number}
```
In the next part, you will Bootstrap script. If you encounter any issues, make sure the further-up dependencies are installed.
```
./bootstrap
```
The Bootstrap script may take a few minutes.

Then do
```
make
cd
cd /usr/local/bin 
sudo cp cmake /usr/bin/
cmake --version
```


