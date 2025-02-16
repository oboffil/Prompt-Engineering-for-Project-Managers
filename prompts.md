# AI Prompts for Project Managers  

This file contains AI-powered prompts designed to help project managers/project owners with various tasks.  

## 📌 Categories  

- [Risk Assessment](#risk-assessment)  
- [Stakeholder Communication](#stakeholder-communication)  
- [Task Prioritization](#task-prioritization)  
- [Sprint Planning](#sprint-planning)  
- [Meeting Summarization](#meeting-summarization)  

---

## 🔍 Risk Assessment  
```plaintext
"Act as a project manager overseeing a software development project with a tight deadline. Identify potential risks based on scope, resources, and dependencies, and suggest mitigation strategies from this description: <Project information>." 

Note: In the previous prompt, you could specify the project software name or the technology you’re using, as the AI will be smart enough to provide suggestions based on that technology. 

## 📢 Stakeholder Communication
```plaintext
"Act as a project manager who needs to update stakeholders about a project delay due to resource constraints. Draft a professional yet reassuring message that provides transparency and outlines next steps for this project: <Project information>."

## ✅ User Stories
```plaintext
"Act as a senior project owner, write user stories, acceptance criteria, and the name of the story from descriptions provided by me. Write one story per description. Use a professional tone, be concise, use the agile format "As, I want, so" for description, and "Given, when, then" for acceptance criteria."

Note: This has been the most useful prompt I’ve used. It will help you start refining stories, and the AI is smart enough to identify work that may have been missed when collaborating with the engineering team, thanks to the extensive technical information available in LLM models. You can modify various aspects of this prompt to fit your needs and even derive story points from it. However, I still recommend working with the teams to ensure the estimates are accurate.

## ✅ Features
```plaintext
"Act as a senior project Manager, I want you to write a feature with a description, acceptance criteria, and name of the feature from descriptions provided by me. Write one Feature per description. Use a professional tone, be concise, and use agile format "As, I want, so" for description and "Given, when, then" for acceptance criteria."

## 🚀 Sprint Planning
```plaintext
"As a Scrum Master, I need to plan the next sprint. Given a backlog of 20 tasks, with estimated story points, how should I allocate tasks to maximize velocity while minimizing risks?"

## 📝 Meeting Summarization
```plaintext
"Summarize this meeting transcript into key action items, decisions made, and next steps for stakeholders."

## ⚠️ Data Privacy Reminder  
AI models process and learn from the input provided. **Never share sensitive, confidential, or proprietary company data with open-source AI models.**  

- If your company provides an **internal AI model**, use it instead.  
- If using a public AI tool, **reframe prompts** to only include general, non-confidential information.  
- Avoid inputting **customer details, financial records, personal data, or internal strategy documents**.  
