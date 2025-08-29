# Celebrity-Info-Finder-with-Gemini-AI-LangChain-Chains-Memory-
A Streamlit app powered by LangChain and Google Gemini 1.5 Flash that finds information about celebrities, their date of birth, and major world events around their birth year using a multi-step conversational chain with memory.



# Celebrity Info Finder (Gemini + LangChain + Memory + Streamlit)

This project is a simple **AI-powered Streamlit application** that demonstrates how to build a multi-step conversational pipeline using **LangChain** and **Google's Gemini 1.5 Flash model**.

The app allows users to enter the name of any celebrity and then automatically:
1. Generates a short description about the celebrity.
2. Finds the celebrity’s date of birth.
3. Lists 5 major world events that happened around the time of their birth.

---

## 🚀 Features
- **Streamlit UI** for interactive input/output.
- **LangChain SequentialChain** to connect multiple prompts in order.
- **ConversationBufferMemory** to maintain context between chains.
- Powered by **Google Gemini 1.5 Flash** for fast and smart responses.

---

## ⚙️ How It Works
1. User enters a celebrity name.
2. `Chain1` → Fetches information about the celebrity (`output: person`).
3. `Chain2` → Uses that info to find their date of birth (`output: dob`).
4. `Chain3` → Generates 5 major events around the celebrity's birth year (`output: description`).
5. All results are displayed together in the Streamlit app.

---

## 🛠️ Tech Stack
- **Python**
- **Streamlit**
- **LangChain**
- **Google Generative AI (Gemini 1.5 Flash)**
- **dotenv** for API key management

---
