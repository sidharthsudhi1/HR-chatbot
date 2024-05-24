
# **LLM Project to Build a HR Chatbot using a Large Language Model**

In today's data-driven world, the ability to process and generate natural language text at scale has become a transformative force across industries. Large Language Models (LLMs) represent a cutting-edge advancement in natural language processing, enabling businesses to extract valuable insights, automate tasks, and enhance user experiences. By harnessing the power of LLMs, organizations can improve customer service, automate content creation, and gain a competitive edge in the digital landscape.

Fine-tuning entails training a pre-trained language model on a specific task or dataset to adapt it for a particular application. It explores full fine-tuning and Parameter Efficient Fine Tuning (PEFT), a technique that optimizes the fine-tuning process by focusing on a subset of the model's parameters, making it more resource-efficient.

The project involves the application of Retrieval Augmented Generation (RAG) using OpenAI's GPT-3.5 Turbo, resulting in the development of a Human Resources chatbot for knowledge grounding. Knowledge grounding with Retrieval Augmented Generation (RAG) is implemented to mitigate hallucinations and provide trustworthy and reliable responses. This is achieved by incorporating information from external sources to validate and support the generated text.

For example, in the context of an HR chatbot using RAG, knowledge grounding ensures that availability of jobs, roles and responsibilites, qualification, interview process, etc are sourced from a trusted database or platform. This prevents the chatbot from generating inaccurate or fictional details and instead provides responses based on real-world data.

​
​
​
# Execution Instructions
​
# Python version 3.8.10
​
To create a virtual environment and install requirements in Python 3.8.10 on different operating systems, follow the instructions below:
​
### For Windows:
​
Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.
​

Change the directory to the desired location for your project:
​

`cd C:\path\to\project`

​
Create a new virtual environment using the venv module:

​
`python -m venv myenv`

​
Activate the virtual environment:

​
`myenv\Scripts\activate`



​
Install the project requirements using pip:


`git clone https://github.com/sidharthsudhi1/HR-chatbot.git`


`cd HR-chatbot`​


`pip install -r requirements.txt`


​
​
### For Linux/Mac:
​
Open a terminal.

​
Change the directory to the desired location for your project:
​

`cd /path/to/project`
​

Create a new virtual environment using the venv module:
​

`python3 -m venv myenv`
​

Activate the virtual environment:
​

`source myenv/bin/activate`


Install the project requirements using pip:


​`git clone https://github.com/sidharthsudhi1/HR-chatbot.git`


`cd HR-chatbot`
​

`pip install -r requirements.txt`
​

These instructions assume you have Python 3.8.10 installed and added to your system's PATH variable.
​
​

## Execution Instructions if Multiple Python Versions Installed
​
​
If you have multiple Python versions installed on your system , you can use the Python Launcher to create a virtual environment with Python 3.8.10, you can specify the version using the -p or --python flag. Follow the instructions below:
​

### For Windows:
​

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.
​

Change the directory to the desired location for your project:
​

`cd C:\path\to\project`
​

Create a new virtual environment using the Python Launcher:
​

`py -3.8 -m venv myenv`
​

Note: Replace myenv with your desired virtual environment name.
​

Activate the virtual environment:
​

`myenv\Scripts\activate`
​

Install the project requirements using pip:
​

​`git clone https://github.com/sidharthsudhi1/HR-chatbot.git`


`cd HR-chatbot`


`pip install -r requirements.txt`
​

​
For Linux/Mac:

​

Open a terminal.
​

Change the directory to the desired location for your project:

​

`cd /path/to/project`


Create a new virtual environment using the Python Launcher:
​

`python3.8 -m venv myenv`


Note: Replace myenv with your desired virtual environment name.
​

Activate the virtual environment:
​

`source myenv/bin/activate`


Install the project requirements using pip:
​

​`git clone https://github.com/sidharthsudhi1/HR-chatbot.git`


`cd HR-chatbot`


`pip install -r requirements.txt`
​


​

By specifying the version using py -3.8 or python3.8, you can ensure that the virtual environment is created using Python 3.8.10 specifically, even if you have other Python versions installed.
​
​

Then you can run the notebook or use the command to run the app:

`streamlit run app.py`


**NOTE:** Copy your openai api key to the code before running. 


