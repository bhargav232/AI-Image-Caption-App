**AI Image Captioning App**

**Overview**

The AI Image Captioning App allows users to search large image datasets by inputting captions, retrieving images, and providing caption recommendations. It features secure authentication with JWT and SHA256 hashed passwords. Cloud services like AWS S3, EC2, and Azure are utilized, with the Hugging Face ViT-GPT2 model generating captions.

**Features**

Image Captioning: Upload images to S3 and generate captions using ViT-GPT2.
Search: Retrieve images by typing captions.
Security: JWT authentication, SHA256 hashed passwords with salt.
Cloud Integration: AWS S3 for storage, EC2 for backend processing, and Azure services.
Database: MongoDB for storing image URLs and captions.

**Technologies**

Backend: Express.js, Node.js, Flask
Database: MongoDB
Cloud: AWS S3, EC2, Azure
AI Model: Hugging Face ViT-GPT2

**Installation**

Clone the Repo: git clone https://github.com/yourusername/ai-image-captioning-app.git && cd ai-image-captioning-app
Setup Python: virtualenv venv && source venv/bin/activate && pip install -r requirements.txt
Set Environment Variables: Create a .env file with your AWS, MongoDB, and JWT credentials.
Install Node.js Dependencies: cd backend && npm install
Run the App:
Flask: flask run
Node.js: cd backend && npm start

This is a group project for the course COEN6313 (Programming on Cloud).
