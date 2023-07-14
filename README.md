# python-fingerprint-recognizer
its just recognize you fingerprint  using python by dreadraze

Requirements:
- NumPy<!-- 
    for arrays as image objects
-->
- SKimage <!-- 
    for image proceesing
-->
- OpenCV2<!-- 
    for image recoginition
-->
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install Numpy
```
```bash
python -m pip install -U scikit-image
```
```bash
pip install opencv-python
```

Works by extracting minutiae points using harris corner detection.
Usage:

1. Place 2 fingerprint images that you want to compare inside the database folder 
2. Pass the names of the images as arguments in the console

NOTE: the fingerprints must be in the `/database` folder
## indocker
```shell
docker build -t <name_of_your_choice> .

docker run -it <name_of_your_choice> <fingerprint_1> <fingerprint_2>
```


## Credits

Special thanks to https://github.com/Utkarsh-Deshmukh/Fingerprint-Enhancement-Python for providing a library used to enhance the fingerprint picture.


## License

MIT License

Copyright (c) 2023 ARUN KUMAR.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
