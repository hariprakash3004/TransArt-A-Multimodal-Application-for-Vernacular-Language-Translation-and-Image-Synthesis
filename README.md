### TransArt - Multimodal Application 🚀🚀🚀

**TransArt seamlessly transcribes audio, translates it into multiple languages, and generates stunning visuals based on the content. Additionally, it offers an interactive chatbot for engaging conversations and image generation, all in one platform.**

### Installation

To install the required dependencies, run:

    - pip install -r requirements.txt

### Features

       **- 🎙 Audio Transcription & Translation:** 
                    Convert speech into text using Whisper and translate from Tamil to English with Google Translator.

              
  
      **- 🎨 AI-Generated Images:** 
                    Generate stunning images using Stable Diffusion based on translated text or user prompts.
  
      **- 🎛 Intuitive Gradio Interface:** 
                    A user-friendly interface with multiple interactive tabs for seamless functionality.

### Models & APIs Used

       **- Stable Diffusion XL (stabilityai/stable-diffusion-xl-base-1.0):** For generating images from text prompts.
  
       **- Groq API:** This is for audio transcription and chatbot interaction.
  
                      - Whisper model (whisper-large-v3) for Tamil audio transcription.

       **- Google Translator:** This is for translating Tamil to English.
  
### Development Steps

**1. Imported Libraries and Set Up Environment**

Integrated essential libraries such as gradio, whisper, GoogleTranslator, and StableDiffusionXLPipeline.
Configured API keys for Hugging Face and Groq for seamless model integration.

**2. Created Audio Processing Function**

Developed process_audio to handle audio uploads.
Transcribed speech using Whisper.
Translated Tamil to English using GoogleTranslator.
Enabled optional image generation based on translated text.

**3. Implemented Image Generation from Prompts**

Designed generate_image_from_prompt to generate images using a custom Stable Diffusion model based on user-provided text prompts.

**4. Designed Gradio Interface**

Utilized gr.Blocks() to create a well-structured UI with multiple tabs:

       - 🎙 Audio to Text Tab: Transcribe and translate audio, with an option to generate images.

       - 🖼 Prompt to Image Tab: Generate images based on user-entered text prompts.
   
**6. Customized the App UI**

Applied custom CSS styling to enhance the app’s appearance, including background colors, button styles, and text formatting.

**7. Launched the Application**

Deployed the Gradio app, making it accessible for live testing and demonstrations.

### How to Use

      - Upload an audio file to transcribe and translate speech into English.

      -Generate AI-powered images from text or translated speech.


![Screenshot 2025-01-30 201421](https://github.com/user-attachments/assets/06d8b205-00e1-4e53-8784-4b23869b4829)

![Screenshot 2025-01-30 201618](https://github.com/user-attachments/assets/0a12fe36-c610-4745-9020-4bad33c88e74)

![Screenshot 2025-01-30 202017](https://github.com/user-attachments/assets/fd03a803-fd11-498d-8503-c012213183a2)

![Screenshot 2025-01-30 202126](https://github.com/user-attachments/assets/4f776704-b244-4dc4-b6e8-0f777457abe6)

**🎯 Built with:** Python | Gradio | Whisper | Stable Diffusion | Hugging Face | Groq API

**🚀 Contributors:** HARIPRAKASH .N

📢 Feedback & Contributions Welcome!

### Contact

For any questions or inquiries, feel free to contact me at **hariprakash3004@gmail.com**.
