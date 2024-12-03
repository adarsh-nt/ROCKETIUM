# ROCKETIUM
# CreateAiVerse

*CreateAiVerse* is an AI-powered platform designed to revolutionize ad creation. Built with *Streamlit*, this platform helps users generate text-to-image ads, create engaging video advertisements, and develop comprehensive campaign strategies—all using advanced AI tools like AWS Stability API, GPT API, and various multimedia processing libraries.

## Features

### 1. *IdeaToAd*
- *Transform Text to Image*: Generate up to 15 unique text-to-image ads based on user-defined prompts such as brand name, content, color schemes, and target audience.
- *Customizable Prompts*: Users can specify various parameters, such as the number of images to generate and the overall aesthetic.
- *Powered by AWS Stability API*: Leverages cutting-edge AI models to create visually appealing posters and advertisements.

### 2. *AdMotion*
- *Convert Images to Video: Takes the generated images from **IdeaToAd* and stitches them into seamless videos, with each image serving as a frame in the video.
- *Dynamic Audio: Adds audio to the video using tools like **Pydub, **AudioSegment, and **CV2*, ensuring a dynamic and engaging multimedia experience.
- *Customizable*: Users can control the video creation process, including image duration, transitions, and audio tracks.

### 3. *AdBot*
- *AI-Generated Campaign Strategies: Utilizes **GPT API* to craft innovative marketing strategies, brand slogans, and campaign ideas.
- *Content Generation*: Helps users generate creative content for social media, posters, and video captions based on the campaign's objectives and target audience.
- *Automated*: Easily generate content that aligns with the overall brand voice, messaging, and vision.

## Future Scope

- *Improved Content Optimization*: Integrating advanced NLP models to ensure generated content is contextually relevant, grammatically correct, and aligned with brand identity.
- *Seamless Flow in Campaigns*: Enhanced features for ensuring a cohesive narrative across all generated ads and videos. Storyboarding and content validation tools will help create campaigns that are well-structured and easy to follow.
- *Personalization*: Future versions will incorporate AI-powered tools that allow users to personalize ads based on user preferences, trends, and demographics.
- *Real-Time Collaboration*: Plans to integrate collaboration tools for teams to work together in real-time, making the ad creation process smoother and more efficient.

### Required Libraries:
- *Streamlit*
- *boto3* (for AWS)
- *cv2* (OpenCV)
- *Pydub*
- *AudioSegment*
- *PIL* (Pillow)
- *openai* (for GPT API)
- *tempfile*

## Usage

1. *IdeaToAd*: Enter the brand name, content, color schemes, and target audience to generate up to 15 ads. Customize the number of images to be created and download them as individual image files.
   ![IMG-20241202-WA0014](https://github.com/user-attachments/assets/1b0947b1-df0f-4538-b785-8c2b676a69b0)
2. *AdMotion*: Upload the generated images and create a video by selecting image duration, transition effects, and audio. Download the video after rendering.
https://github.com/user-attachments/assets/da35ad57-99ba-4027-9be1-45fc0772c3af
4. *AdBot: Provide details about your campaign, and **AdBot* will generate campaign ideas, slogans, and content tailored to your brand’s objectives.
![IMG-20241202-WA0015](https://github.com/user-attachments/assets/e2fec24f-f395-409f-bd0d-45875cb042ca)
