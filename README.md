# genai-application-kepco
UET x KepcoKDN project applying learned Generative AI concepts (Oct 2024) - by Ba-Hoang-Long Nguyen (longnbh)

## Image Content Analysis and Enhancement from Social Media for Improved Communication Efficiency

### Project Goal
This project aims to optimize images from social media posts using Generative AI. The system will identify topics, analyze, and enhance images, then suggest improvements to boost user engagement.

### Technology and APIs Used
- **BLIP and GPT-2 Image Captioning Model from Replicate**: Recognizes and generates captions for image content.
- **Stable Diffusion from Replicate**: Enhances and optimizes image colors.

### Setup
1. **Install the required libraries** from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
- `replicate`: Python library for connecting and utilizing AI models on the Replicate platform.
- `requests`: Library for sending HTTP requests, supports image download from URLs.
- `pillow`: Library for image processing, allows loading and saving images.
2. **Sign up for an account on Replicate and obtain an API Key**
- Log in to your Replicate account and go to the Account settings to obtain your API Key.
- Place the API Key in the `main.py` file in the variable `replicate_api_token`.

### Usage
To run the application, follow these steps:
1. Run image analysis: Analyze and identify image content to generate captions.
2. Run image enhancement: Enhance image colors and details to optimize the content.
   ```bash
   python main.py # Run this in Terminal
The enhanced image will be saved in the directory with the name `enhanced_image.jpg`

### Note
- Billing setup is required on Replicate to run the model and see desired results(Due to time and budget constraints, I have not tested it yet).
