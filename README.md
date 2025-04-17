# SENTIENT - Conversational Image Recognition ChatBot
Locally deployed multimodal chatbot that can be used for personal research and findings to a vast corpus of data without internet, leveraging Ollama and LangChain framework. The chatbot seamlessly handles text, images, PDFs, and audio inputs, employing advanced AI models like DeepSeek 7B, Llama 2 (7B & 13B), Mistral 7B, LLaVA, and Whisper AI for natural language understanding and multimodal data processing. It delivers accurate and context-aware responses, showcasing robust capabilities in conversational AI.


https://github.com/user-attachments/assets/906ff569-d80d-4a8b-8121-4cb97b536738





# Installation Instructions 

# PREQUISITES:

 1. Python 3.7 or higher: Ensure Python is installed on your system. You can download it from python.org.
    
 2. Ollama :
    

        (Steps to Install Ollama on Windows via WSL)
        
        - Install WSL and Set Up Ubuntu:
          (1) Open PowerShell as Administrator and run: [wsl --install]
          (2) Restart your computer if prompted.
          (3) After restarting, WSL will install Ubuntu by default.
    
        - Launch Ubuntu in WSL:
          (1) Open the Ubuntu application from the Start menu.
          (2) Set up your Unix username and password as prompted.
    
        - Update Package Lists:
          (1) In the Ubuntu terminal, run: [sudo apt update]
    
        - Download & Install Ollama: [https://ollama.com/download]
    


  4. Download & Install Docker Desktop with WSL2 integration: [https://www.docker.com/products/docker-desktop/]
     
           Download from: https://www.docker.com/products/docker-desktop
           During setup, ensure:
               - Use WSL 2 instead of Hyper-V is selected
               - Your Linux distro is selected in "Resources → WSL Integration"
           Open your WSL terminal (Ubuntu from the Start Menu)
              Run:
              docker --version
              docker run hello-world
     
          It should pull and run a test container to verify everything is working.
     




# [COMPLETE STEPS FOR WINDOWS] 
Follow these steps to set up and run the SENTIENT chatbot on your local machine: 


1. Install Python 3.7 or higher: Ensure Python is installed on your system. You can download it from python.org.

2. Download & Install Ollama using WSL:
   
        (Steps to Install Ollama on Windows via WSL)
        
        - Install WSL and Set Up Ubuntu:
          (1) Open PowerShell as Administrator and run: [wsl --install]
          (2) Restart your computer if prompted.
          (3) After restarting, WSL will install Ubuntu by default.
    
        - Launch Ubuntu in WSL:
          (1) Open the Ubuntu application from the Start menu.
          (2) Set up your Unix username and password as prompted.
    
        - Update Package Lists:
          (1) In the Ubuntu terminal, run: [sudo apt update]
    
        - Download & Install Ollama: [https://ollama.com/download]
   
  

 2. Download & Install Docker Desktop with WSL2 integration: [https://www.docker.com/products/docker-desktop/]
     
          (1) Download from: https://www.docker.com/products/docker-desktop
          (2) During setup, ensure:
               - Use WSL 2 instead of Hyper-V is selected
               - Your Linux distro is selected in "Resources → WSL Integration"
          (3) Open your WSL terminal (Ubuntu from the Start Menu)
              Run:
              docker --version
              docker run hello-world
     
          It should pull and run a test container to verify everything is working.
     


3. Enter command in IDE terminal: docker compose up
   
4. Open the app: Open 0.0.0.0:8501 in the Browser
   
5. Pull Models: Go to https://ollama.com/library and choose the models you want to use. Enter /pull MODEL_NAME in the chat bar. You need one embedding model e.g. nomic-embed-text to embed pdf files (change embedding model in config if you choose another). You also need a model which undertands images e.g. llava
   
6. Optional:
Check the config.yaml file and change accordingly to your needs.
Place your user_image.png and/or bot_image.png inside the chat_icons folder and remove the old ones.

      


# Features 

Image Upload and Analysis: Users can upload images, which the system analyzes to identify objects, scenes, and other relevant details.

Conversational Interaction: Engage in natural language conversations with the chatbot to inquire about various aspects of the uploaded image.

Multimodal Understanding: Combines visual data with textual input to provide comprehensive responses.

User-Friendly Interface: Intuitive web interface for seamless image uploading and chatting experience.


    
    
