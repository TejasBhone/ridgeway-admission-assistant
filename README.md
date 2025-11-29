<p align="center">
  <img src="Ridgeway Admission Assistant.png" width="100%">
</p>

### Key Files

- [`persona-spec.md`](./persona-spec.md) – Full behavior & architecture specification  
- [`system-prompt.txt`](./system-prompt.txt) – Ready-to-use system prompt  
- [`Ridgeway Admission Assistant.png`](./Ridgeway%20Admission%20Assistant.png) – Visual overview

---

# Ridgeway Admission Assistant (Persona v2)

A structured LLM persona for college admission workflows, including documentation and system prompt.

---

## 1. Project Name
**Ridgeway Admission Assistant (Persona v2)**

---

## 2. Summary
The Ridgeway Admission Assistant is a structured LLM-based persona designed to provide clear and consistent information about college details, courses, fees, staff, and admission processes. It helps prospective students get accurate responses through a fixed format and predictable behavior. The assistant follows strict tone and rule-based flows to stay reliable and easy to use.

---

## 3. Problem Statement
Most admission chatbots give inconsistent answers, drift into casual tone, or fail when users ask off-topic questions.  
Students often receive incomplete information about courses, eligibility, or fees, leading to confusion during the admission process.  
A controlled persona was needed to provide accurate, stable, and professional responses using a strict rule structure.

---

## 4. Objective / Solution
The goal of this project is to create a reliable admission assistant that delivers consistent, neutral, and structured information to students.  
The persona solves drift and unclear responses by following strict formatting rules, a fixed menu system, and controlled response behavior.

---

## 5. Key Features
- Structured response format  
- Stable tone control  
- Strict menu navigation  
- Drift prevention  
- Eligibility logic  
- Error & confusion handling  
- Complaint handling  
- Refusal protocol  
- Topic stability rules

---

## 6. Your Role / Contribution
- Designed the full behavior structure  
- Defined tone rules, formatting rules, and boundaries  
- Created the menu system and topic-flow logic  
- Added drift-prevention and refusal logic  
- Tested edge cases  
- Documented all rules clearly

---

## 7. Tools & Technologies Used
- ChatGPT (LLM platform)  
- System prompt engineering  
- Custom chatbox frontend (prototype)  
- Manual stress-testing  
- Markdown documentation

---

## 8. Outcome / Value
The assistant delivers consistent and reliable admission information without tone changes or off-topic behavior.  
It reduces confusion and ensures predictable, professional interactions suitable for real institutional use.

---

## 9. Sample Use Cases
### **Course Information**
User asks about B.Tech → Assistant provides structured course details.

### **Eligibility Clarification**
User mentions marks → Assistant repeats criteria neutrally.

### **Fees & Payment Options**
User asks about fees → Assistant gives ₹85,000 + installment details.

### **Off-topic Behavior**
User asks unrelated questions → Assistant issues refusal.

### **Confusion Handling**
User says “I don’t get it.” → Assistant apologizes and re-explains.

---

## 10. Future Improvements
- API integration  
- Real data source  
- Improved frontend  
- Automated testing  
- Multi-persona expansion  
- Scalability options
