# NANON96 - RAG And MCP Session

Repository for NANOG96  - RAG / MCP Workshop Session
John Capobianco 

## Getting Started

1. Git - Please ensure you have Git installed on your machine. You can download it from [git-scm.com](https://git-scm.com/).

2. Python - Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

3. wsl - If you are using Windows, please ensure you have WSL2 installed. You can follow the instructions [here](https://docs.microsoft.com/en-us/windows/wsl/install).

4. Ubuntu - If you are using WSL2, please ensure you have Ubuntu installed. You can follow the instructions [here](https://docs.microsoft.com/en-us/windows/wsl/install).

6. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/automateyournetwork/NAF_AC4
   ```

7. Virtual Environment - It's a good practice to create a virtual environment for your Python projects. You can do this using the following command:
   
   ```bash
   python -m venv venv
   ```

8. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

9. Install VS Code - If you haven't already, download and install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/).

10. Export enviroment variable 

```bash
export OPENAI_API_KEY="Key Provided By John"
```

11. Install Required Packages - Use the following command to install the required packages:
    ```bash
    (venv)% cd NAF_AC4
    (venv)NAF_AC4 %python3 -m pip install -r requirements.txt
    (vent)NAF_AC4 npm install -g @toon-format/cli
    ```

12. Open the project in Visual Studio Code:
    ```bash
    code .
    ```

13. Cisco DevNet Always On 9k - Get credentials for the Always On Cisco 9k

https://devnetsandbox.cisco.com/DevNet/catalog/Cat9k-Always-On_cat9k-always-on

Update your testbed.yaml files

## RAG Lab Instructions - 

Setup your venv, install requirements.txt, run the labs - change directory in to Lab01, Lab02, Lab03 etc and run the respective python files.

Some labs will be streamlit apps - run them with streamlit run app.py

## MCP Lab Instructions -

Change into the Lab01, Lab02 etc directories and run the respective python files. First run the server to start it up, stop the server, then run the client to connect to the server and execute commands.

## Testbed.yaml File

You should have a devnet sandbox for the always on 9k update your testbed.yaml file with the correct credentials and URL and such. Test SSH connectivity with pyats before running the MCP labs.

IF you want more advanced lab environment you can try the CML reserverable lab; generate crypto keys on the 4 devices; and update your testbed.yaml file with the correct IP addresses and credentials.
