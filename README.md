![image](https://github.com/debamitr1012/GeminiTLDR/assets/78213067/91c4fb79-a4bb-4bef-83b9-103db9a00dbc)# GeminiTLDR
## TLDR Document Summarizer AI with Gemini

In developing the Gemini TLDR Document Summarizer AI, I leveraged my Java programming skills to build the core application, handling document parsing and processing. I integrated Google AI Studio's API for advanced summarization capabilities. Using HTML, I created a user-friendly interface for document upload and summary display. Docker was employed to containerize the application, ensuring consistent deployment across environments. This project highlights the effective use of Java for backend processing, HTML for frontend development, and Docker for deployment, resulting in a practical document summarization tool.

```
java -jar -DAPI_KEY=<your_api_key> tldr-0.0.1-SNAPSHOT.jar
```
```
docker build -t tldr .
```
```
docker run -it -p 8080:8080 -e API_KEY='<your_api_key' tldr
```
[localhost:8080](http://localhost:8080) 
