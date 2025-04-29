# IT 359 Project
This project demonstrates how a reverse shell payload can be created using msfvenom and embedded into a Microsoft Word macro as a proof-of-concept for educational and defensive security purposes. The objective is to simulate a common attack technique used by threat actors to gain unauthorized access to a target system, with the ultimate goal of understanding how such threats operate, how to identify them, and how to effectively defend against them.   

By following the steps outlined in this project, readers will gain insight into:  
  
How attackers craft and deliver malicious payloads using social engineering.  
How Microsoft Office macros can be exploited for code execution.  
Techniques for detecting and mitigating macro-based malware threats in enterprise environments.   
Data (like text from Magic cards) is transformed into these vectors using a process involving tokenization (splitting text into smaller units) and embedding (converting tokens into numerical representations using pre-trained models)    
When you query, the same vectorization process is applied to your query, and the resulting query vector is compared to the vectors in the database to find the most similar ones.      
Technologies used will include Weaviate(built in AI and machine learning integration), OpenAI, python, node.js and next.js    

# Day One: I have no idea what I am doing!  
The project I am trying to follow isn't very beginner friendly, so I am doing a lot of research via notebook LM and youtube videos to figure out a list of things.  
- First I made a weaviate account and collected both the api key and the URL.
- Next I got an API key from Open AP.
