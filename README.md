# MONTY-Custom-AI-ChatBot
MONTY → My Open Network for Talking to You

Overview

Monty is a Python-based AI chatbot built using Hugging Face models. It evolves from GPT-2 → DialoGPT → Falcon-7B, showing improved conversational quality and response refinement. Designed for backend AI experimentation on Google Colab with GPU support.

Features

-Multi-stage chatbot development for progressive improvements

-Context-aware conversation handling

-Tuned parameters for natural responses

-Fully Python-based, no front-end required

Model Evolution

-GPT-2: Initial setup, basic conversation

-DialoGPT-medium: Better context retention and dialogue coherence

-Falcon-7B-Instruct: High-quality, detailed, human-like responses

EXAMPLE USAGE
User: Hello Monty, how are you?
Monty: I'm feeling good! Ready to help you with your questions today.

User: Tell me something interesting about space.
Monty: Did you know that there are more stars in the universe than grains of sand on all the beaches on Earth?

User: Can you give me advice on staying motivated?
Monty: One way to stay motivated is to set small, achievable goals and celebrate each success...


Technical Notes

-Environment: Google Colab (T4 GPU recommended)

-Models: Hugging Face Transformers (GPT2LMHeadModel, DialoGPT, Falcon-7B)

-Quantization: 4-bit or 8-bit to save GPU memory

-Attention Masks: Used to prevent input repetition and improve reliability

Sampling Parameters:

-Temperature: 0.8

-Top-k: 50

-Top-p: 0.95

Known Limitations

-Falcon-7B responses can be slow on Colab (~15 minutes runtime for extended sessions)

-Occasional incoherent or repetitive outputs

-Some context may be lost over long multi-turn conversations

Credits / References

-Hugging Face Transformers: https://huggingface.co/transformers

-GPT-2 Model: https://huggingface.co/gpt2

-DialoGPT-medium: https://huggingface.co/microsoft/DialoGPT-medium

-Falcon-7B-Instruct: https://huggingface.co/tiiuae/falcon-7b-instruct
