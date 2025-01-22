# AI_Agents
Smart-Med AI Driven Chatbot using Agentic RAG

The main goals of the “Smart Med” project are to enhance customer satisfaction in the sphere of health care, inform patients about their state, suggest specialists depending on the symptoms, and book an appointment. It is this project’s goal to embrace Agentic RAG, while utilizing AI tools to increase patients involvement, lesson the workload and finally, enhance health for the patients.

Smart Med’s multi-agent system is realized based on a Retrieval-Augmented Generation (RAG) structure, where diversified agents can help in the efficient and effective handling of user queries. Every agent is built to perform a specific role and has its own functionality which makes responses polished and context-specific. The details of each of the following agents are stated as follows.

A. SQL Agent
The SQL Agent pulls data of healthcare providers such as availability, specialization and experience of individual doctors. It is built using LangChain that translates users’
questions to formatted SQL queries, which query a doctor’s database for more information. The agent is secure in the access it provides to the authenticated healthcare data in that it only retrieves information that is sanctioned for access due to patient and provider privacy.

B. General Chatbot Agent
The General Chatbot Agent serves as a health information provider as well as a referral service in that it provides the name of a specialist depending with the symptoms disclosed by the ‘patient’. Built using LangChain and the Gemini 1.5 Flash model, it processes inquires and responds with symptombased suggestions through natural language processing. As compared to other agents developed earlier, this agent has integrated symptom-to-specialist mapping to provide a precise advice on the type of specialist required for the patient.

C. Appointment Booking Agent
The Appointment Booking Agent is responsible for doctor appointments. After a patient has decided to book an appointment, this agent checks for the availability of the doctors and schedule the appointment in the database. It resends the confirmation to the patient, and this makes the entire confirmation easy and fast.
