FoodSense AI – Recipe Improvement Advisor
   
  FoodSense AI is a multi-agent AI system that analyzes customer food reviews and generates actionable cooking improvement suggestions for recipes.
  The system uses a structured AI workflow to transform raw review text into chef-style recommendations.

🚀 Features-
  
  🔍 Review analysis using AI
  
  😊 Sentiment detection from customer feedback
  
  🧠 Multi-agent reasoning pipeline
  
  📊 Data preprocessing for clean inputs
  
  🤖 Local LLM execution using Ollama
  
  🌐 Interactive web interface with Streamlit


🧩 System Workflow-

User Input → Data Processing → Multi-Agent AI Workflow → LLM Reasoning → Cooking Improvement Output

🤖 AI Agents

Review Analyzer Agent-
Summarizes customer reviews and extracts key food-related feedback.

Sentiment Agent-
Identifies overall sentiment (positive/neutral/negative) and highlights specific taste, texture, and seasoning issues.

Advisor Agent-

Suggests practical cooking and ingredient improvements based on detected issues.

Reporter Agent-
Converts suggestions into short, clear kitchen instructions.

Tech Stack-

Technology	     Role
Python	         Backend logic
Pandas	         Data preprocessing
Streamlit	      Web interface
LangChain	      LLM integration
LangGraph	      Multi-agent workflow
Ollama	         Local LLM runtime
Mistral / Phi	   Language model for reasoning

 
Project Structure

  agents/       → AI reasoning agents  
  graph/        → Workflow orchestration  
  utils/        → Preprocessing helpers  
  data/         → Dataset location  
  main.py       → Backend controller  
  app.py        → Streamlit UI  

 
 
Dataset
    Due to GitHub file size limits, datasets are not included in this repository.

Download datasets from the links provided in:
  data/dataset_links.txt
After downloading, place the files inside the data folder before running the project.

How to Run the Project
1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Install Ollama (for local LLM)

Download from: https://ollama.com

Then pull a model:

ollama run mistral


(You can also use a smaller model like phi)

Press Ctrl + C after the model loads.

3️⃣ Run the application

   streamlit run app.py
   Open the browser link shown in the terminal.


Project Objective
    
  This project demonstrates how multi-agent AI systems can transform unstructured customer feedback into structured, domain-specific recommendations using local language models.

Future Improvements
  
   Add more specialized agents
   Use cloud LLMs for higher accuracy
   Add recipe categorization
   Deploy on cloud platform


Author
 
 Abhijeet Phatangare

