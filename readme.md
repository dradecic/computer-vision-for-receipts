# Computer Vision for Document AI
<a style="float:left;" href="https://www.neos.hr/news-neos/"><img src="https://img.shields.io/badge/Neos-32b5c4.svg?style=for-the-badge"/></a>
<a style="float:left;" href="https://hr.linkedin.com/company/neos-hr/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a style="float:left;" href="https://twitter.com/neos_hr"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>
<a style="float:left;" href="https://www.facebook.com/neos.hr"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
<br>
<br>
<br>
A case study if Computer Vision applied to receipt detection. Examples in Python implemented in OpenCV and Tesseract OCR.
<br>
To get started, ensure you have Tesseract-Lang installed on your machine.
<br>
Then, install the required packages from the file (preferably inside a virtual environment):
<br><br>

```
pip install -r requirements.txt
```

Activate the environment and you're ready to go!
<br><br>
<img src="data/banner.jpeg" width=600>

## Content
<hr>

    ├── data
    │   ├── example1.jpg         <- First receipt image
    │   ├── receipt.jog          <- Second receipt image
    │   └── banner.jpeg          <- Banner for this project
    │
    ├── LICENSE
    ├── README.md
    │
    ├── 001_ReadReceipts.ipynb   <- Jupyter notebook for processing receipt image and reading all text from it
    ├── 002.ExtractData.ipynb    <- Jupyter notebook for area detection and purchased item extraction
    └── requirements.txt         <- All Python libraries that notebooks depend on

## Resources
<hr>
- [Blog-post-TBA](https://neos.hr)<br>
- [Oracle Cloud Vision](https://www.oracle.com/artificial-intelligence/vision/#rc30p2)
