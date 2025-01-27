Here's a detailed for setting up and running **DeepSeek R1** locally with all the mentioned resources and instructions:

---

# **DeepSeek R1: Local Setup Guide**

DeepSeek R1 is a powerful open-source AI model capable of performing reasoning, coding, and math tasks, comparable to OpenAI o1 and Claude 3.5 Sonnet. This guide will help you set up DeepSeek R1 locally on your machine for free and with complete privacy.

---

## **Step 1: Download and Install Ollama**

Ollama is a tool for running AI models locally on your machine.  

### **Download Ollama**
- [Download for Mac, Windows, or Linux](https://ollama.com/download)  
- Refer to the image below for downloading Ollama:  
  ![Download Ollama](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(3).png)  

### **Install Ollama**
- Follow the installation instructions based on your OS.  
- Example for installation:  
  ![Installing Ollama](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(12).png)  

---

## **Step 2: Pull and Run the DeepSeek R1 Model**

### **Choose Model Size**  
DeepSeek R1 offers multiple sizes based on your hardware capability:  
- **1.5B (Smallest)**: `ollama run deepseek-r1:1.5b`  
- **8B**: `ollama run deepseek-r1:8b`  
- **14B**: `ollama run deepseek-r1:14b`  
- **32B**: `ollama run deepseek-r1:32b`  
- **70B (Largest)**: `ollama run deepseek-r1:70b`  

Start with a smaller model to test performance.  

### **Run the Command**
Open your terminal and run the following command:
```bash
ollama run deepseek-r1:8b
```

Refer to the image for downloading progress:  
![Downloading DeepSeek](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%202025-01-28%20022516.png)  

### **Download Progress**
It will download the model. Wait until it reaches 100%:  
![Download Progress](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(6).png)  
![Download Complete](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(11).png)  

---

## **Step 3: Install Chatbox**  

Chatbox is a clean, privacy-focused desktop interface for interacting with AI models.

### **Download Chatbox**  
- [Chatbox Official Site](https://chatboxai.app)  
- Example for downloading on Windows:  
  ![Chatbox Download](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(9).png)  

---

## **Step 4: Configure Chatbox**  

1. Open Chatbox and navigate to **Settings**.  
2. Set the **Model Provider** to **Ollama**.  
3. Configure the API Host to `http://127.0.0.1:11434`.  

Refer to the image below for configuration details:  
![Chatbox Configuration](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(7).png)  

---

## **Step 5: Run the Model and Interact**

- After completing the setup, you can start interacting with the model via Chatbox.  
- Example of asking a question and receiving an answer:  
  ![Model Interaction](https://github.com/dhiraj7kr/Images/blob/main/DeepSeekAI/Screenshot%20(8).png)  

---

## **Additional Notes**

- Ensure you have sufficient GPU resources for larger models (32B and 70B).  
- For any issues, check the logs in Ollama or the Chatbox troubleshooting guide.  

---

Enjoy using **DeepSeek R1** for your AI tasks! Let us know if you have any feedback or questions. 🚀
