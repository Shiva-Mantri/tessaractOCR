## DOCUMENT INTELLIGENCE

### Reference
- Document Intelligence Workshop 2021 - https://document-intelligence.github.io/DI-2021/
- Document Intelligence Workshop 2019 - https://sites.google.com/view/di2019/home


## OCR

### Preprocessing
Ref/Credit: https://docparser.com/blog/improve-ocr-accuracy/
- Good original source image
- Resize - Scale to 300DPI
- Increase contrast
- Binarization - Convert color to black and white
- Remove background noise - So that image has just text. This includes removing scanning stains, lines and borders
- Thresholding
- Deskew/rotation

### Extraction
- Use OCR Engine to feed doc and extract text

### Improvement
- Use dictionary, spell checking to fix uncertain or missing characters/words


## USING TESSERACT OCR

### Image Pre-Processing
- https://stackoverflow.com/a/50762612/780405
  - https://medium.com/free-code-camp/getting-started-with-tesseract-part-i-2a6a6b1cf75e
  - https://medium.com/free-code-camp/getting-started-with-tesseract-part-ii-f7f9a0899b3f
- https://stackoverflow.com/a/46696775/780405
  - Apply blur to the original image.
  - Apply Adaptive Threshold.
  - Apply Sharpening effect.
 - Finally tool Documentation
  - Tesseract - https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html
  - OpenCV - https://docs.opencv.org/master/d2/d96/tutorial_py_table_of_contents_imgproc.html

## REFERENCE
- https://medium.com/better-programming/beginners-guide-to-tesseract-ocr-using-python-10ecbb426c3d
- https://nanonets.com/blog/ocr-with-tesseract/

### OCR and Dependent modules
- Central Repo - https://github.com/tesseract-ocr
- Tesseract Open Source OCR Engine - https://github.com/tesseract-ocr/tesseract
- Best (most accurate) trained LSTM models - https://github.com/tesseract-ocr/tessdata_best
- Trained models with support for legacy and LSTM OCR engine - https://github.com/tesseract-ocr/tessdata

### Windows GUI Tool
- https://goinggnu.wordpress.com/2020/05/23/tesseract-ocr-gui-for-windows/
  - https://github.com/Parathantl/tesseract_gui
    
### OCR - Python - Reference

