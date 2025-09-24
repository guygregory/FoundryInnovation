# Foundry Innovation

This repository contains demonstration notebooks showcasing Azure AI Foundry capabilities including browser automation, web search, model routing, and GPT audio features.

## Setup

### Prerequisites
- Python 3.7 or higher
- Azure OpenAI and Azure AI Foundry access

### Installation

1. Clone the repository:
```bash
git clone https://github.com/guygregory/FoundryInnovation.git
cd FoundryInnovation
```

2. Install the required Python packages:
```bash
pip install -r requirements.txt
```

3. Configure your environment variables by copying the sample file:
```bash
cp .env.sample .env
```

4. Edit the `.env` file with your Azure credentials and endpoints.

## Demo Notebooks

- **demo-browser-automation.ipynb**: Demonstrates browser automation using Azure AI Foundry Agent Service
- **demo-websearch.ipynb**: Shows web search capabilities in the Responses API
- **demo-model-router.ipynb**: Demonstrates model routing functionality
- **demo-gpt-audio.ipynb**: GPT-Audio sample for generating spoken announcements

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.