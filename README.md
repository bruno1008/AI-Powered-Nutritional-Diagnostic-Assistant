# AI-Powered Nutritional Diagnostic Assistant

## Overview

This project is an advanced virtual assistant that leverages the ChatGPT-3.5-turbo model to support nutritional diagnosis. It combines machine learning techniques with a custom-built database of diseases, symptoms, and nutritional goals, while utilising speech recognition for seamless patient-physician interaction capture.

## Key Features

- **ChatGPT-3.5-turbo Integration**: Enhanced natural language processing
- **Custom Health Database**: Comprehensive collection of diseases, symptoms, and nutritional goals
- **Speech Recognition**: Effortless recording of patient-physician dialogues
- **Softmax Algorithm**: Accurate probabilistic diagnosis
- **User-Friendly Interface**: Designed for healthcare professionals

## Installation

To install the required dependencies, run:

```bash
!pip install openai
```

Ensure you have the latest version of the `openai` library:

```bash
!pip install --upgrade openai
```

## Usage

To start the application, execute:

```python
python main.py
```

You'll be greeted with a "Welcome to Nutri!" message, followed by a prompt from the Nutritionist.

## How It Works

1. Speech recognition captures patient-physician interactions.
2. The system matches patient inputs against the custom database.
3. A softmax algorithm determines the most probable diagnosis.
4. The tool provides a draft diagnostic based on probabilistic analysis.

## Target Users

This tool is designed for medical professionals and nutritionists, offering valuable support in assessing and managing patients' nutritional health.

## Known Issues and Limitations

- The current version may encounter rate limit errors if the API quota is exceeded. Ensure you have sufficient API quota before use.
- Error handling for API-related issues needs improvement to enhance user experience.

## Contributing

Contributions to improve the software are welcome. Before submitting changes:

1. Ensure you have the latest version of the `openai` library installed.
2. Test your changes thoroughly to avoid introducing new issues.
3. Follow the existing code style and structure.

For questions or contributions, please contact: brunolopessousa23@gmail.com

## Disclaimer

This software is intended to support, not replace, professional medical advice. Always consult with a qualified healthcare provider for medical diagnoses and treatment.

## Future Improvements

- Implement robust error handling for API-related issues.
- Optimise API usage to prevent rate limit errors.
- Enhance the user interface for a more intuitive experience.
- Expand the health database for more comprehensive diagnoses.
- Implement user authentication for secure access.
