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

[MIT](https://choosealicense.com/licenses/mit/)
