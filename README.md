# PROJECT BY: SYEDA UMAIMA TAMKEEN

## Project Summary: AI-Powered Resume Parser using NLP

This project presents a fully functional AI-powered resume parser system capable of extracting structured information from resumes using Natural Language Processing (NLP) and machine learning techniques. The parser identifies key entities such as name, email, skills, and work experience, enabling recruiters to filter and assess candidates more efficiently.

---

## Techniques Implemented:

- **Text Preprocessing**  
  - Tokenization, lowercasing, punctuation removal  
  - Stopword elimination using SpaCy  
  - Regular expressions for email and phone number extraction  

- **Named Entity Recognition (NER)**  
  - SpaCy’s pretrained models for recognizing names, organizations, and roles  

- **Regex Parsing**  
  - Extraction of structured fields like emails, phone numbers, and years of experience  

- **PDF Parsing Libraries**  
  - PyPDF2 and PDFMiner for reading and processing resumes in PDF format  

- **Data Structuring**  
  - Output is converted into a clean, structured **JSON format** compatible with applicant tracking systems

---

## Evaluation Metrics:

- **Entity Matching Accuracy**: Assessed precision of extracted entities (Name, Email, Skills, Experience)  
- **Manual Validation**: Results were manually reviewed for correctness against 15 sample resumes  
- **Field-wise Accuracy Report**: Reported on detection reliability for each key entity

---

## Results & Insights:

- Achieved high precision in **email and name** detection using regex and NER  
- Skills and experience sections were effectively captured from varying formats  
- JSON output format met the schema specification required by the task  

---

## Strengths:

- Compatible with PDF resumes and scalable for other formats like DOCX/TXT  
- Structured modular approach – clean separation of parsing logic and UI  
- Accurate field extraction across multiple resume templates  
- Easy-to-integrate output format for HR systems  

---

## Conclusion:

This resume parser provides a reliable and scalable solution for automated candidate screening. It streamlines recruitment workflows by enabling the rapid extraction of meaningful information from resumes. The combination of NLP, NER, and regular expressions ensures both flexibility and precision, fulfilling the project requirements effectively and laying the groundwork for further integration with AI-based scoring or recommendation systems.
