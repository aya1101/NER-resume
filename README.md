# NER-resume
This project aims to build and train a NER model specifically designed for resume parsing, where the goal is to extract structured information from resumes to aid in automated recruitment and HR applications. 

**--- Approach ---**  
To achieve high accuracy in entity recognition, using a Bidirectional Long Short-Term Memory (BiLSTM) network combined with a Conditional Random Field (CRF) layer.  

**--- Dataset ---**   
The model is trained on the Resume NER dataset from Kaggle, which contains labeled resumes with annotated entities such as:  
- Names (candidate names)  
- Skills (technical and soft skills mentioned)  
- Education (universities, degrees, and certifications)  
- Experience-related entities (company names, job titles, dates)  
The structure of dataset includes:     
- Content  
- Annotation:   
  + Entity  
  + Start point  
  + End point  
