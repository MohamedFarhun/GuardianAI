

## Introduction
GuardianAI is a rule-based chat prototype designed to ensure ethical and legal compliance when using generative AI tools in the workplace. It integrates real-time monitoring, risk-based alerting, and dynamic rule adjustment to maintain high standards of AI governance.

## Features
- **Document Analysis**: Upload policy documents to analyze and extract compliance rules automatically.
- **Real-Time Monitoring**: Monitor interactions with AI in real-time to ensure compliance with established rules.
- **Risk-Based Alerting**: Set risk thresholds and receive alerts when interactions potentially breach these thresholds.
- **Admin Controls**: Administrators can review and adjust monitoring rules and risk thresholds as needed.

## Installation
To run GuardianAI on your local machine, you will need Python and several dependencies installed.

### Prerequisites
- Python 3.8+
- pip

### Setting Up a Virtual Environment
For Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
For macOS and Linux:

bash
python3 -m venv venv
source venv/bin/activate
Installing Dependencies
Install all required packages with pip:

bash
pip install -r requirements.txt
Running the Application
Once the environment is set up and all dependencies are installed, you can run the application using:

bash
streamlit run app.py
Usage
After launching the application, you will be prompted to upload a document. The system will analyze the document, extract compliance-related rules, and allow you to interact with a chatbot that respects these rules.

Upload a Document: Supported formats include TXT, PDF, DOCX, and PPTX.
Set Risk Thresholds: Adjust the risk thresholds to tailor the monitoring to your organizational needs.
Interact with Chatbot: Ask questions or provide scenarios to the chatbot to test compliance with your rules.
Contributing
Contributions to GuardianAI are welcome! Please refer to the contributing guidelines before making pull requests.

### License
GuardianAI is released under the MIT License. See the LICENSE file for more details.

### Contact
For support or to contact the developers, please send an email to mohamedfarhun.it20@bitsathy.ac.in

Acknowledgments
Thanks to everyone who has contributed to the development of GuardianAI, especially those in the open-source community who make their tools and libraries freely available.

### Explanation

- **Introduction**: Briefly describes what the project is about and its purpose.
- **Features**: Outlines key features of the application.
- **Installation**: Provides detailed instructions on how to set up and run the application.
- **Usage**: Explains how to use the application effectively.
- **Contributing**: Invites contributions, assuming you have guidelines for this.
- **License**: Specifies the type of license under which the project is released.
- **Contact**: Provides a way for users to get in touch with the developers.
- **Acknowledgments**: A space to thank contributors and acknowledge dependencies or third-party services.

Make sure to customize the content as per your project’s specifics and to check all commands and instructions for accuracy.
