# README.md

## Project Overview

This project is an email generator web app powered by OpenAI's GPT technology. The application allows users to quickly generate professional emails based on their input and seamlessly integrate with Gmail for sending the generated emails.

## User Interface

The user interface of the email generator web app is straightforward and user-friendly. Here’s how it works:

1. **Describe the Email**: Start by describing the kind of email you want to be written. This can include the tone, purpose, and any specific details you want the email to cover.

2. **Specify Keywords and Word Count**: Provide a few key phrases or words that you want included in your email along with the desired word count.

3. **Generate Email**: Click the “Generate Email” button. The app will use the provided information to generate a complete email.
<img width="629" alt="image" src="https://github.com/davidliuzw/spamwebapp/assets/79090372/640b9528-7d94-42ae-bb5f-6f2be8828876">

4. **Review the Output**: If you are satisfied with the generated email, you can proceed to the next step. If not, you can modify your inputs and regenerate.
<img width="668" alt="image" src="https://github.com/davidliuzw/spamwebapp/assets/79090372/0f574cf6-8473-4e98-8ad0-872d80e0eea7">

5. **Send the Email**: Click the “Click me to send the email” button at the bottom of the page. This action will redirect the page to Gmail with the generated email pasted in the body, ready for you to review and send.
<img width="676" alt="image" src="https://github.com/davidliuzw/spamwebapp/assets/79090372/2307dce2-b8d4-4e28-b9ed-79baa5806f12">

## Technologies Used

### Programming Language
- **Python 3.8**

### Dependencies
- **Streamlit**: Used for building the interactive web application.
- **OpenAI**: Powers the GPT model for generating email content.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open your web browser and navigate to the URL provided by Streamlit after running the application.
2. Follow the user interface steps to generate and send your email.

## Contributing

We welcome contributions to improve the email generator web app. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
