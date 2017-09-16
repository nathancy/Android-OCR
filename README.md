### TextBuddy Android App

[![Video](http://img.youtube.com/vi/B7KG6iZU-ek/0.jpg)](https://www.youtube.com/watch?v=B7KG6iZU-ek)


TextBuddy is an Optical Character Recognition (OCR) application to simplify your life by providing the ability to convert any hard copy text into a digital file. Instantly scan desired text through the camera to the smartphone clipboard for use in any other external third-party app like messaging or email. Easily convert scanned text images or snippets of word fragments into word documents without the hassle of manually writing or typing words again.

### Motivation

The motivation behind this project was to integrate optical character recognition technology into an Android app with the ability to convert images and photographs into editable and searchable text. Instead of having to manually copy down words on paper or type text to a word document, one would be able to instantly convert fragments of text from a picture and have it automatically converted into a digital file such as a word document. In addition, one would be able to transform text in handwritten or printed text form to a digital file where it can be easily manipulated. Then one would be able to share the captured snippets through SMS or any other third-party application such as email.

### Implementation

The application utilizes the Tesseract Open Source OCR Engine which is essentially a large library that contains a set of Android APIs for image processing. The Tesseract engine has the capability of converting a wide range of image formats to text through trained data language files. The engine scans each character through the camera and converts it into a digital representation. Although the engine is fairly accurate at recognizing and converting printed documents, the engine loses accuracy if scanned on handwritten words. Through the OCR engine, we implemented character recognition with features such as window size adjustment, real-time character recognition, camera autofocus, mean-confidence prediction, and time-to-convert prediction. 

### Developers Guide

To build and run the app in Android Studio:
1. Check out project from Version control -> Github
2. Use default gradle wrapper. If you get the error: "SDK location not found. Define location with sdk.dir in the local.properties file or with an ANDROID_HOME environment variable.", close the import project. Then press "Open an existing Android Studio project" and browse to where you selected to import. 
