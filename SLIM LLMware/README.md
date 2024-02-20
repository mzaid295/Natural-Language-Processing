# NLP Tasks On Local Machine

SLIMs are Structured Language Instruction Models, which are small, specialized 1B parameter LLMs, finetuned to generate structured outputs (Python dictionaries, JSON and SQL) that can be handled programmatically, and stacked together in multi-step, multi-model Agent workflows - all running on a local CPU.



## Features

The app supports the following tasks with text input:

- Sentiment Analysis
- Emotion Detection
- Generate Tags
- Identify Topics
- Perform Intent
- Get Ratings
- Get Category
- Perform Named Entity Recognition (NER)
- Perform Natural Language Inference (NLI)

## Installation

Make sure to install the required Python packages before running the app:

```bash
pip install llmware
pip install streamlit
```

## Running the App

To run the app on your local machine, execute the following command in your terminal:

```bash
streamlit run app.py
```

Replace `app.py` with the actual name of your Streamlit app file.

## Usage

1. Open the app in your web browser after running the above command.
2. Enter text for the desired NLP task in the provided input box.
3. Click the corresponding button to perform the selected task.
4. View the results displayed on the app interface.

## Dependencies
- [llmware](https://huggingface.co/llmware/)
- [streamlit](https://streamlit.io/)

Make sure to have these dependencies installed to run the app successfully.

## Screenshot
![NLP Stremlit App](https://github.com/mzaid295/Natural-Language-Processing/blob/main/SLIM%20LLMware/StreamLit_App.JPG)
![Generate Tags](https://github.com/mzaid295/Natural-Language-Processing/blob/main/SLIM%20LLMware/Generate_Tags.JPG)
![Identify Topics](https://github.com/mzaid295/Natural-Language-Processing/blob/main/SLIM%20LLMware/Identify_Topics.JPG)

## License

This project is licensed under the [MIT License](LICENSE.md).

Feel free to explore and enhance the functionalities of the SLIM Models Streamlit app!
```
