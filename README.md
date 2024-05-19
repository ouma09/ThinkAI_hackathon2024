# ThinkAI_hackathon2024

## Our project MediGuider : 
- It's a user-friendly chat interface allows patients to upload blood test results and provides clear interpretations
- Assesses the urgency of the patient's condition and provides guidance on seeking immediate medical attention for urgent issues.

### Without Virtual Environment:

1. **Navigate** to your project directory using the `cd` command:
   ```bash
   cd mychatBot

2. **Install** the required dependencies using pip with the requirements.txt file:
   ```bash
   pip install -r requirements.txt

3. - **Set up the OpenAI API** by creating an OpenAI account and obtaining an API key.
   - Then, set the OPENAI_API_KEY environment variable in the main.py file by replacing "YOUR_API_KEY" with your actual API key.

4. Run the application using the python command:
   ```bash
   python main.py

### If you want to run in a virtual environment:

5. Create a virtual environment using the python -m venv command:
   ```bash
   python -m venv chatbot_venv

6. Activate the virtual environment using the appropriate command:
   ```bash
   chatbot_venv\Scripts\activate
7. Install the required dependencies within the virtual environment using pip with the requirements.txt file:
   ```bash
   pip install -r requirements.txt

8. Set up the OpenAI API as described earlier.
9. Run the application using the python command:
   ```bash
   python main.py
