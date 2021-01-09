# Number Plate Recognition
Number Plate Recognition using Tesseract OCR

Usage:
```
python3 ocr.py --image [path] --preprocess[type of preprocessing (optional)]
```
e.g.
```
python3 ocr.py --image plate4-uk.jpg --preprocess thresh
```

## Results
- `plate1.png`: number not found
- `plate2.png`: number `ARS I986` found, CORRECT
- `plate3-uk.jpg`: number not found
- `plate4-uk.jpg`: number partially found, `A6BA`

## References
- https://www.pyimagesearch.com/2020/09/21/opencv-automatic-license-number-plate-recognition-anpr-with-python/
- https://www.geeksforgeeks.org/license-plate-recognition-with-opencv-and-tesseract-ocr/

## Development
Currently only the helper functions are tested, using pytest.
* `python3 -m venv venv`
* `source venv/bin/activate`
* `pip3 install -r requirements.txt`