AiAgentMasterclass
AiAgentMasterclass is a Python-based project that integrates OpenAI's language models with Asana task management. The agent acts as a personal assistant, helping users manage tasks in Asana through a conversational interface.

Features
Task Management: Create tasks in Asana with specified names and due dates.
AI Interaction: Engage in a conversation with the AI to manage tasks effectively.
Tool Integration: The AI can invoke predefined functions to perform actions, such as creating tasks.
Requirements
Python 3.7+
An OpenAI API key
An Asana API access token
Installed Python packages: asana, openai, python-dotenv
Installation
Clone the Repository:

git clone https://github.com/yourusername/AiAgentMasterclass.git
cd AiAgentMasterclass
Set Up a Virtual Environment:

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies:

pip install -r requirements.txt
Configure Environment Variables: Create a .env file in the project root and add the following:

OPENAI_API_KEY=your_openai_api_key
ASANA_ACCESS_TOKEN=your_asana_access_token
ASANA_PROJECT_ID=your_asana_project_id
OPENAI_MODEL=gpt-4o  # Optional: specify the model
Usage
Run the Agent:

python agent.py
Interact with the AI:

The agent will prompt you to chat. Type your requests or commands.
To quit, enter q.
Code Overview
agent.py: Main script containing the logic for interacting with OpenAI and Asana.
create_asana_task: Function to create tasks in Asana.
prompt_ai: Handles the AI's response and manages tool calls.
get_tools: Defines available tools for the AI.
main: Entry point for running the agent.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.