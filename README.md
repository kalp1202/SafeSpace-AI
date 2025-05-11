🧠 SafeSpaceAI: Your Personal AI Therapist

    Empathetic. Accessible. Private.
    SafeSpaceAI is a web-based therapy assistant designed to provide real-time, compassionate mental health support using cutting-edge large language models.

🧩 Problem Statement

Mental health care is often:

    Inaccessible or unaffordable

    Lacking personalization

    Hard to navigate, especially for those unfamiliar with the system

SafeSpaceAI aims to address this by offering:

    Real-time emotional support

    Speech or text-based interactions

    Adaptive, empathetic responses based on the user’s emotional context

🌟 Key Features

    🔐 Google OAuth Login for secure and easy access

    🎤 Speech-to-Text Support for voice-based interaction

    🤗 LLM-backed Therapy using a fine-tuned Gemma 3 12 billion parameters model

    🌐 Deployed on Hugging Face + Render.io

    📈 Fine-tuned using LoRA for emotion-sensitive responses

🏗️ System Architecture

![image](https://github.com/user-attachments/assets/9b768454-16a9-4d66-929f-85d25bb5b3f2)


Workflow:

    👤 User logs in via Google OAuth on the Node.js website.

    🎙️ User chooses voice or text interaction.

    🧠 Voice input is converted to text using SpeechRecognition (Webkit-based).

    📤 Input is passed to a Gradio interface hosted on Hugging Face.

    🧬 The fine-tuned Gemma-12B model processes the input and generates a response.

    🧾 Response is sent back to the frontend for display.

🧠 The Model Behind It: Gemma 3

    Lightweight, dialogue-optimized, and open-source — from Google.

Why We Chose Gemma 3:

    🪶 Lightweight: Ideal for fast inference on web.

    🧵 Instruction-tuned and chat-optimized.

    🔧 Easily fine-tuned with LoRA.

    🌍 Open-source with community and documentation support.

    🛡️ Built with responsible AI practices.

🧪 Fine-Tuning Details

Component	Details
Base Model	Gemma 3 (12B parameters) from Hugging Face
Technique	LoRA (Low-Rank Adaptation)
Dataset	Curated prompts + mental health and empathy-focused conversations
Platform	Hugging Face Notebooks
Objective	Empathetic response generation for diverse emotional states

📹 Video Demo

https://github.com/user-attachments/assets/a8b44848-a747-4ede-9158-aad53b59bfe3

P.S.: The video has no sound included but the website does output in different voices which you can select from the dropdown menu.

🚧 Challenges Faced

    Limited LoRA support for Gemma on Hugging Face

    Cross-platform integration between Node.js, Gradio, and Webkit

    Real-time deployment and latency tuning for web deployment

🔮 Future Scope

    📊 User Dashboard with sentiment trends & journaling insights

    🌐 Multilingual and Inclusive Support

    📚 Broader Dataset Coverage for diversity and inclusion

    📱 Mobile App for Android/iOS support

🌐 Project Links

    💬 Chatbot Website: https://theribot.onrender.com/

    🤗 Hugging Face Space (Gradio UI): https://huggingface.co/spaces/made1570/TestingModelAPI

    🧠 Fine-Tuned LLM (Gemma 3): https://huggingface.co/adarsh3601/my_gemma3_pt

📚 References

    🤗 Hugging Face: https://huggingface.co

    🧠 Gemma LLM by Google: https://ai.google.dev/gemma

    🎛️ Gradio Framework: https://www.gradio.app

    🚀 Render Deployment Platform: https://render.com

    🔐 Google Developers Console (OAuth): https://console.developers.google.com

    🎙️ Web Speech API (MDN Docs): https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API

    🧬 Keras Documentation: https://keras.io

    🧑‍💻 GitHub Docs: https://docs.github.com

