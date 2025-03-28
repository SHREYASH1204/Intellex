# 🚀 AlgoForge - Intelligent Document Assistant

<div align="center">

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.31.0-FF4B4B.svg)
![LangChain](https://img.shields.io/badge/LangChain-0.1.0-FF6B6B.svg)

</div>

## 📝 Overview

AlgoForge is an intelligent document assistant platform designed specifically for interns and IT professionals. It leverages cutting-edge AI technology to provide interactive document analysis, comprehension, and documentation generation capabilities. The platform supports various document formats including PDFs and presentations, with role-based access control for enhanced security.

## ✨ Key Features

- 🤖 **AI-Powered Document Analysis**: Utilizes LLaMA 3.3 70B model for intelligent document processing
- 📚 **Multi-Format Support**: Handles PDFs, presentations, and other document types
- 🔒 **Role-Based Access Control**: Secure access management for interns and IT heads
- 🎯 **Interactive Q&A**: Natural language interface for document queries
- 📊 **Documentation Generation**: Automated documentation creation
- 🔊 **Text-to-Speech**: Audio playback of responses
- 🖼️ **Visual Context**: Displays relevant document pages alongside responses

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JS
- **Backend**: Python
- **AI/ML**: 
  - LangChain
  - HuggingFace Embeddings
  - LLaMA 3.3 70B (via ChatGroq)
- **Document Processing**: PyMuPDF (fitz)
- **Vector Database**: FAISS
- **Text-to-Speech**: gTTS

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SHREYASH1204/Intellex.git
cd AlgoForge
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file in the root directory with the following:
```
GROQ_API_KEY=your_groq_api_key
```

### Running the Application

1. Start the Streamlit server:
```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

## 📁 Project Structure

```
AlgoForge/
├── app.py                 # Main application file
├── documents/            # Document storage directory
├── frontend/            # Frontend assets
├── requirements.txt     # Project dependencies
└── .env                # Environment variables
```

## 🔐 Access Control

The platform implements a hierarchical access control system:

- **IT Heads**: Full access to all documents and administrative features
- **Interns**: Access to assigned documents based on permissions

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) for the beautiful UI framework
- [LangChain](https://www.langchain.com/) for the AI/ML infrastructure
- [LLaMA](https://ai.meta.com/llama/) for the powerful language model
- [FAISS](https://github.com/facebookresearch/faiss) for efficient similarity search

## 📞 Support

For support, please open an issue in the GitHub repository or contact the development team.

---

<div align="center">
Made with ❤️ by the AlgoForge Team
</div>

The below is the link to the video of the project :
https://drive.google.com/file/d/1Bv2-ueE--G32h9UDbozPDFAlLbaeYVYW/view?usp=sharing
