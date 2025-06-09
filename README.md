# 🎨 AI Advertisement Generator

An AI-powered tool that automatically generates visual advertisements from business descriptions. Perfect for small businesses, freelancers, and marketers!

![Example Ad](https://via.placeholder.com/800x400?text=Sample+Ad+Output) *(Replace with your sample ad image)*

## ✨ Features

- **Text-to-Ad Generation**: Convert short business descriptions into complete ads
- **AI-Powered Components**:
  - GPT-2 for creative captions
  - Stable Diffusion for high-quality images
- **Perfect Alignment**: 
  - Images generated without embedded text
  - Captions professionally aligned below images
- **Fallback System**: Automatic placeholder generation if AI fails

## 🛠️ Tech Stack

| Component          | Technology Used         |
|--------------------|-------------------------|
| Natural Language   | Hugging Face GPT-2      |
| Image Generation   | Stable Diffusion v1.4   |
| Image Processing   | PIL/Pillow              |
| Font Handling      | Google Fonts (Roboto)   |

## 🚀 Quick Start

1. **Prerequisites**:
   ```bash
   pip install torch transformers diffusers pillow
