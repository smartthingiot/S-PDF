# S-PDF


[Source](https://github.com/Frooodle/Stirling-PDF/blob/main/HowToUseOCR.md)

```
version: '3.3'

networks:
  frontend:
    external: true
  backend:
    external: true


services:
    s-pdf:
        ports:
            - '8855:8080'
        image: frooodle/s-pdf:latest
        container_name: spdf
        restart: unless-stopped
#        volumes:    # Tesseract OCR https://github.com/Frooodle/Stirling-PDF/blob/main/HowToUseOCR.md
#             - ./config:/location/of/trainingData
        networks:
            - frontend
            - backend
```
