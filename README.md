# Cloud Application for Smart Photo Album

## Description
Implemented a smart photo album web application that performs object detection on uploaded images using AWS Rekognition and searches photos using natural language through both text and voice.Constructed a REST API, used Lex to disambiguate the queries, S3 to store images and custom labels, Transcribe for speech 
to text capability and performed DevOps CI/CD using AWS Code Pipeline and Cloud Formation to stand up the entire functional stack.

## Process
1. Visit your photo Album Application using the S3 hosted URL.
2. Search photos using Natural Language via voice and text.
3. See relevant results based on what you searched for example, uttering show me cat, should retrieve and display images of cats from the album.
4. Upload new photos(with or without custom labels) and see them appear in the search results.


## Architecture
![image](https://user-images.githubusercontent.com/37374785/215332291-487c598f-8a45-4d5e-b172-6b9900f77897.png)
