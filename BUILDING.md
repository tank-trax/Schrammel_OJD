### Linux ###

```
git clone https://github.com/tank-trax/Schrammel_OJD.git
cd Schrammel_OJD
git checkout linux
git submodule update --init --recursive
bash Patches.sh
cmake -DCMAKE_BUILD_TYPE=Release -B build
cmake --build build -j4
```
