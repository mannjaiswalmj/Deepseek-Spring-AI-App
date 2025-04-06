# 🤖 Deepseek Spring AI App

A Spring Boot application that integrates the **Deepseek Large Language Model (LLM)** using **Spring AI** and **Ollama** for running the model locally. This project demonstrates how to build an intelligent chatbot capable of processing and responding to user queries via REST APIs.

![spring-ai-deepseek-integration](https://github.com/user-attachments/assets/5900f94a-e817-43ce-8eae-9566b8ede1d8)

---

## 🚀 Features

- 🌐 RESTful API for AI interaction
- 🤖 LLM integration using **Deepseek**
- 🔄 Local model inference powered by **Ollama**
- ⚙️ Built with **Spring Boot** & **Spring AI**
- 📦 Dockerized for easy deployment

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring AI**
- **Ollama** (for local LLM serving)
- **Deepseek LLM**
- **Maven**
- **Docker**

---

## 📦 Getting Started

### ✅ Prerequisites

- Java 17+
- Maven
- Docker
- [Ollama](https://ollama.com/) installed and running locally
- Deepseek model pulled via Ollama:
  ```bash
  ollama pull deepseek
  ```

### 🔧 Run Locally

```bash
# Clone the repository
git clone https://github.com/mannjaiswalmj/Deepseek-Spring-AI-App.git
cd Deepseek-Spring-AI-App

# Run the Spring Boot application
./mvnw spring-boot:run
```

> Make sure Ollama is running and the Deepseek model is available locally.

---

## 📬 API Endpoint

### `POST /chat`

**Request Body:**
```json
{
  "message": "Tell me a fun fact about AI."
}
```

**Response:**
```json
{
  "response": "Artificial Intelligence can write poetry and code!"
}
```

---

## 📂 Project Structure

```
├── src
│   ├── main
│   │   ├── java/com/example/deepseek
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   └── config
│   │   └── resources
│   │       └── application.yml
├── Dockerfile
├── README.md
└── pom.xml
```

---

## 📘 Learn More

- [Spring AI Documentation](https://docs.spring.io/spring-ai/reference/)
- [Ollama Docs](https://ollama.com/)
- [Deepseek on Ollama](https://ollama.com/library/deepseek)

---

## 🙋‍♂️ Author

**Mann Jaiswal**  
🔗 [GitHub](https://github.com/mannjaiswalmj)  
📧 official.mannjaiswal@gmail.com

---

