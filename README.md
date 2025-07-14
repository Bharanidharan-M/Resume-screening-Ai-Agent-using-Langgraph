# Automated Resume Evaluation Agent using LangGraph & Google Gemini

This project builds an intelligent, LLM-powered agent to automate resume evaluation and personalized feedback generation for AI/ML roles.

## 🔧 Technologies Used
- 🧠 Google Gemini 1.5 Flash (via `langchain-google-genai`)
- 🕸️ LangGraph (`StateGraph`)
- 🐍 Python

## 🚀 What It Does
- Loads a sample resume into memory
- Uses Google Gemini to assess if the candidate is qualified
- Routes flow based on qualification status
- Generates either a positive invitation or polite rejection message

## 💡 Features
- Modular LangGraph state-based pipeline
- Typed state management (`TypedDict`)
- Gemini-powered decision and text generation
- Easy integration into HR systems or bots

## 🛠️ How to Run

```bash
!pip install langchain-google-genai langgraph langchain-community
