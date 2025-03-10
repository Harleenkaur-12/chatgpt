# OpenAI API Project Setup

## Step-by-Step Installation

1. **Check Python Installation**
   ```bash
   python --version  # Should show Python 3.8 or higher
   ```
   If not installed, download from https://python.org

2. **Set Up Project**
   Open command prompt and run:
   ```bash
   cd c:\Users\harle\Desktop\Ai
   ```

3. **Create Virtual Environment**
   ```bash
   python -m venv venv
   ```

4. **Activate Virtual Environment**
   ```bash
   # On Windows:
   venv\Scripts\activate
   
   # You should see (venv) at the start of your command line
   ```

5. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

6. **Configure API Key**
   - Get your API key from https://platform.openai.com/api-keys
   - Open `.env` file
   - Replace `sk-your-actual-api-key-here` with your actual API key

7. **Run the Program**
   ```bash
   python main.py
   ```

## Common Issues:
- "Command not found": Make sure you're in the correct directory
- "ModuleNotFoundError": Check if you activated the virtual environment
- "Invalid API key": Verify your API key in the .env file
