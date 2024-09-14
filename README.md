# ComedyWriter AI

ComedyWriter AI is a Streamlit-based application that helps aspiring comedians and writers create and refine comedy bits. It uses advanced language models to generate ideas, provide feedback, and offer guidance on various comedy techniques.

## Features

- Interactive chat interface for comedy writing assistance
- Support for multiple AI models (OpenAI and Ollama)
- Customizable comedy categories and focus areas
- Conversation saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/ComedyWriterAI-Streamlit100.git
   cd comedywriter-ai
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3. Enter your name and start interacting with the ComedyWriter AI!

## Customization

- Modify the `COMEDY_CATEGORIES` list in `app.py` to add or remove comedy categories
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
