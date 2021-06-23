# lrzsz
Mirrors of https://www.gnu.org/software/lrzsz/

## Compile installing

```
cd lrzsz
git checkout 0.12.20

# Make compiling
sudo chmod +x configure mkinstalldirs
sudo ./configure --prefix=$(pwd)
sudo make && install

# Show compiled binary files.
ls -al ./bin/
```
