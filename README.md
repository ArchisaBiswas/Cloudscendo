# Cloudscendo  
**Emotion-Based Music Recommendation Web Application Using AWS**

Cloudscendo is a cloud-powered web application designed to deliver personalized music recommendations based on real-time emotion detection. By integrating facial emotion recognition with intelligent search capabilities, Cloudscendo creates a unique, mood-responsive listening experience tailored for every user.

## Motivation:

Cloudscendo aims to:
- Enhance user engagement with emotion-aware content.
- Demonstrate the power of cloud-based AI/ML services.
- Showcase real-world integration of AWS for intelligent, scalable applications.

## Features:

- Emotion Detection: Capture user emotion using facial recognition powered by AWS Rekognition.
- Intelligent Song Matching: Match emotions to music using AWS Kendra with a Spotify Data-Set.
- Interactive Music Playback: Display matched tracks using the YouTube API in a responsive carousel format.
- Cloud-Hosted Backend: Built on Amazon Web Services (AWS) infrastructure for scalability and performance.
- Python & Flask Integration: Developed using the Flask framework with Boto3 SDK for seamless AWS service interaction.


## Technologies Used:

| Technology           | Purpose                                      |
|----------------------|----------------------------------------------|
| AWS Rekognition      | Detects user emotion from uploaded images    |
| AWS Kendra           | Performs semantic search on song database    |
| Flask                | Backend web Frame-Work                        |
| Boto3                | Python SDK to interact with AWS services     |
| YouTube API          | Embeds and displays music videos             |
| Spotify Data-Set      | Emotion-to-song mapping Data-Set (via Kaggle) |


## How It Works:

1. **Image Upload**: User captures or uploads an image via the frontend.
2. **Emotion Recognition**: AWS Rekognition processes the image and detects the primary emotion.
3. **Music Recommendation**: AWS Kendra queries a curated music Data-Set for songs that match the detected emotion.
4. **Content Delivery**: Matched tracks are displayed to the user in a carousel using the YouTube API.


## Data-Set:

- **Source**: Kaggle Spotify Data-Set.
- **Content**: Song metadata categorized by mood/emotion (e.g., happy, sad, calm, energetic).
- **Usage**: Natural Language Processing used for the search via AWS Kendra.


## Cloud Infrastructure:

The backend is hosted entirely on Amazon Web Services, leveraging its:
- Reliability
- Scalability
- Real-time processing capability
- Security features for safe image handling and user data


## Thank You.
