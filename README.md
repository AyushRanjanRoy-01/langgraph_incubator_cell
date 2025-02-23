**Multi-Agent Startup Incubator cell**
A LangGraph-based AI system designed to analyze, refine, and critique startup ideas. This project provides an interactive Gradio application where users can input their startup ideas and receive structured feedback.

🔹 Features
**AI-Powered Agents** – Strategy, Research, Refinement, and Review agents for structured feedback.
**LangGraph Workflow** – Seamlessly orchestrates multi-step AI analysis.
**Gradio UI** – Easy-to-use web app for real-time interaction with the AI.
**Inspect under the hood** – Clearly see every stages of state, thread id, revision count etc.

📌 How It Works
The system follows a multi-stage AI workflow to refine and critique startup ideas:

1️⃣ Strategy Agent
Generates a high-level business plan based on the user’s startup idea.
Identifies Unique Selling Points (USPs), target market, and scalability potential.
2️⃣ Market Research Agent
Conducts AI-driven market research to analyze trends, competitors, and challenges.
Uses external APIs (like Tavily) to gather real-world business insights.
3️⃣ Refinement Agent
Expands and enhances the initial business plan based on market research findings.
Optimizes the value proposition and strategic direction.
4️⃣ Review Agent (Final Stage)
Provides an investor-style critique of the startup idea.
Highlights strengths, weaknesses, risks, and recommendations.
🔹 The system stops at the review stage, ensuring the final output is structured and ready for decision-making.

🚀 Running the Gradio App
🔗 Live Demo: [Click Here](https://huggingface.co/spaces/ayushroy/my-gradio-app)
📌 How to Use
Execute the notebook cells and get structured feedback on your startup idea. To use gradio App:
1️⃣ Enter your startup idea in the input box.
2️⃣ Click ‘Generate Plan’ – The AI will process your idea through different refinement stages.
![image](https://github.com/user-attachments/assets/7b3355f7-0d42-4ae1-981c-4ad6d582035b)
3️⃣ For passing to next agent / stage (strategy-> Market-> Refine -> Review) click on ‘Continue Refinement’.
4️⃣ Click on "Refresh" botton on each tab (Startegy Outline, Research Content, Startup Plan, Review) to view the content generated in each step.
![image](https://github.com/user-attachments/assets/06d9d46a-27fa-4a81-a766-49de6b67a7d8)

**🛠️ Technologies Used**
Python – AI processing
LangGraph – Multi-stage AI workflow
LangChain – LLM integrations
Gradio – Interactive UI
OpenAI GPT-4 – Core AI processing
Tavily API – Market research
