# S-PDF


[Source](https://github.com/Frooodle/Stirling-PDF/blob/main/HowToUseOCR.md)

```
version: '3.3'
services:
    s-pdf:
        ports:
            - '8855:8080'
        image: frooodle/s-pdf:latest
        container_name: spdf
#        volumes:    # Tesseract OCR https://github.com/Frooodle/Stirling-PDF/blob/main/HowToUseOCR.md
#             - ./config:/location/of/trainingData


```
