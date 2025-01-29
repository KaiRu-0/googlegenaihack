AI Teaching Assistant for Data Structures
This is a Streamlit app powered by Google Gemini that helps users learn Data Structures and Algorithms, focusing on sorting algorithms using the Socratic method.

Features
Socratic Teaching: The assistant guides users through sorting algorithms by asking probing questions.
Chat History: Save, load, and delete chat history.
Voice & Text Input: Interact through typing or voice.
Sorting Algorithm Visualizations: View videos and explanations for Bubble Sort, Merge Sort, Quick Sort, and Heap Sort.
Setup
Install dependencies:

bash
Copy
Edit
pip install streamlit google-generativeai dotenv streamlit-mic-recorder pytube streamlit-player Pillow
Set up your .env file with your Google Gemini API key:

makefile
Copy
Edit
GEMINI_API_KEY=your-api-key-here
Run the app:

bash
Copy
Edit
streamlit run app.py
Contact
Feel free to reach out for any issues!
