# QuizMorph: AI-Powered Academic Companion

**QuizMorph** is an AI-powered tool designed to revolutionize learning and assessment by:  
1️⃣ **Summarizing academic notes** to condense key concepts effectively.  
2️⃣ **Generating MCQs** tailored to the summarized content for efficient self-evaluation and assessments.  

---

## 🛠️ Features  
- **AI-Powered Summarization**: Leveraging NLP models to extract key concepts from academic notes.  
- **MCQ Generation**: Automatically creates multiple-choice questions relevant to the content.  
- **User-Friendly Interface**: Upload your notes, get summaries, and download MCQs seamlessly.  
- **Highly Accurate and Tailored Content**: Integrated with **Google Mini 1.5 Pro** for precise and efficient processing.  

---

## 🔧 Tech Stack  
- **Backend**: Python 🐍, Natural Language Processing (NLP) libraries, transformers.  
- **Frontend**: A clean and intuitive web interface using Flask 🌐.  
- **Deployment**: Flask-based integration for easy deployment and usage.  

---

## 🚀 How to Run QuizMorph  

Follow these steps to set up and run **QuizMorph**:  

### 1. Clone the Repository  
Clone the project repository to your local machine:  
```bash  
git clone https://github.com/your-username/QuizMorph.git  
cd QuizMorph
```
### 2.  Set Up Environment
Install the required dependencies using pip:
```bash
pip install -r requirements.txt  
```
### 3. Configure API Key

Add your Google API key to the project:

1. Create a `.env` file in the root directory.  
2. Add your API key to the file:  

```plaintext
GOOGLE_API_KEY=your_google_api_key_here
```
### 4. Run the Application

Start the application:

```bash
python app.py
```
The application will start on http://127.0.0.1:5000/. Open this URL in your browser to use QuizMorph.

## 📂 File Structure
```plaintext
QuizMorph/  
├── app.py                # Main application logic  
├── templates/            # HTML templates for the UI  
├── static/               # Static assets (CSS, JS)  
├── uploads/              # Uploaded files directory  
├── results/              # Generated MCQ files directory  
├── .env                  # Environment file for API key  
├── requirements.txt      # Python dependencies  
└── README.md             # Documentation
```
## 📝 How It Works  

1. **Upload Notes**  
   Upload your academic notes in **PDF, DOCX, or TXT** format.  

2. **Summarization**  
   The system extracts key concepts using **AI-based NLP algorithms**.  

3. **MCQ Generation**  
   Automatically generates **MCQs** tailored to the summarized content.  

4. **Download Results**  
   Get your **summarized content and MCQs** in **TXT or PDF** format.

## 🤝 Contribution  

Contributions are welcome! If you have ideas or improvements, feel free to **fork the repository**, make changes, and **submit a pull request**.  

