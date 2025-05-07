# 📄 Document Reader & Comparator

## 🚀 Overview
This is a web application that allows users to upload documents, extract tabular data, and compare different documents. The application focuses on comparing numerical data and tables between documents, with exact matching (no rounding). All processing is done in real-time without storing any data. The primary use case is comparing advice of delivery documents and receipts.

---

## 🛠️ Tech Stack
### **Frontend:**
- **Next.js** – Fast, modern React framework for UI.
- **Tailwind CSS** – For a clean and simple design.
- **Minimal external libraries** – Focus on native functionality.

### **Backend:**
- **FastAPI** – Modern, fast Python backend.
- **LangChain** – For document processing and AI-powered analysis.
- **OpenAI API (GPT-4)** – For intelligent table extraction and document comparison.

---

## 📌 Current Features
### **Implemented:**
✅ Backend API setup with FastAPI
✅ Document processing service with LangChain integration
✅ PDF processing using GPT-4 for intelligent table extraction
✅ Standardized response format for all document types
✅ Error handling for file processing
✅ Support for specific table format with columns:
   - Registration Number
   - Product Name
   - Unit of Measurement
   - Quantity
   - Unit Price (without VAT)
   - Total Value
   - VAT Value

### **Ready for Testing:**
1. PDF Upload and Processing:
   - Upload PDF files containing single tables
   - Automatic table extraction using GPT-4
   - Validation of table structure and data
3. Error Handling:
   - File type validation
   - Processing error handling
   - Format validation

### **To Be Implemented:**
1. Frontend Development:
   - [ ] Single-page UI with file upload
   - [ ] Document comparison interface
   - [ ] Error display components
   - [ ] Loading states and progress indicators

2. Document Comparison:
   - [ ] Product matching by ID/name
   - [ ] Numerical data comparison
   - [ ] Difference highlighting system
   - [ ] Missing/extra product handling

3. User Experience:
   - [ ] Frontend validation
   - [ ] User feedback system
   - [ ] Clear error messages
   - [ ] Processing status indicators

---

## 🏗️ Project Structure
```
/your-project
│── frontend
│
│── backend
│    
│
│── README.md (this file)
```

## 📖 Testing Guidelines
### **PDF Processing:**
1. Prepare PDF files with tables matching the expected format
2. Test file upload endpoint
3. Verify table extraction accuracy
4. Check error handling for invalid formats

### **API Testing:**
1. Test file upload endpoints
2. Verify response formats
3. Test error handling
4. Check file type validation

