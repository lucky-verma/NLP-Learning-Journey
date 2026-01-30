# NLP Learning Journey

A personal repository documenting explorations and hands-on projects in Natural Language Processing (NLP), featuring implementations of state-of-the-art models like BLIP-2 for vision-language tasks.

## Features

- **BLIP-2 Vision-Language Demo**: Interactive Streamlit app for image captioning, visual Q&A, and chat-based prompting
- **DPO (Direct Preference Optimization)**: Placeholder for preference learning experiments
- **Practical NLP Examples**: Hands-on implementations of modern NLP techniques

## Quick Start

```bash
git clone https://github.com/lucky-verma/NLP-Learning-Journey.git
cd NLP-Learning-Journey
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run BLIP-2/app.py
```

## Project Structure

```
NLP-Learning-Journey/
├── BLIP-2/                 # Vision-language model demo
│   └── app.py              # Streamlit app using Salesforce/blip2-opt-2.7b
├── DPO/                    # Direct Preference Optimization (WIP)
├── .github/                # CI workflows
├── requirements.txt        # Project dependencies
└── README.md
```

## Tech Stack

- **Language**: Python 3.8+
- **Deep Learning**: PyTorch, Hugging Face Transformers
- **Web Framework**: Streamlit
- **Models**: BLIP-2 (Salesforce/blip2-opt-2.7b)

## BLIP-2 Demo Features

- **Image Captioning**: Generate captions for uploaded images
- **Visual Question Answering**: Ask questions about images
- **Chat-based Prompting**: Interactive dialogue about visual content

## License

MIT License
