# SocialSecure
---
An API to identify hated content
- Use anywhere you want
- Single API for 4 types of data identification
   - Text
   - Image
   - Video
   - Audio
---
Idea is to reduce hated content which plays with the Sentiments of People through Social Media.
---
### Tech Stack
- Django Rest Framework
- BERT Model (for Text Analysis)
- VGG16 for Image Classification
- DB Spectrogram for Audio Analysis or Audio to Text then Text Analysis
---
To run this project locally use following instrucitons
1. Install Django and Django restframe work
    ```
    pip install django
    pip install djangorestframework
   ```
2. Run the server
```
    python manage.py runserver
```
