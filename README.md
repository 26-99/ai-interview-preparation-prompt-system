# AI-Powered Interview Preparation Prompt System

## 1. Project Overview
This project presents a reusable prompt system that uses AI to help fresh graduates prepare for software developer interviews. It transforms a job description into a structured, role-specific preparation plan.

## 2. Problem Statement
Candidates applying for entry-level software roles often struggle to identify which topics to study, prioritize technical concepts, and prepare relevant coding and HR questions. Generic prompts can produce broad, unfocused answers.

## 3. Goal
Develop a reusable prompt that analyzes a job description and generates a prioritized, practical interview preparation plan.

## 4. Context
The intended user is an MCA graduate applying for entry-level software and IT roles. Relevant skills include Java, Python, SQL, HTML, CSS, JavaScript, Spring Boot, REST APIs, Git/GitHub, Linux, and cloud fundamentals. The prompt can be adapted to different roles and job descriptions.

## 5. Constraints
- Prioritize technologies and responsibilities explicitly mentioned in the job description.
- Explain concepts in simple language and provide interview-ready answers.
- Separate essential topics from optional topics.
- Include fresher-level coding problems where relevant.
- Do not assume professional experience or invent resume details.
- Label assumptions and missing information clearly.
- Keep the preparation plan practical and structured.

## 6. Desired Output Format
1. Job description analysis
2. Must Prepare / Should Prepare / Good to Know topics
3. Technical questions with answers
4. Coding problems with approaches and examples
5. Resume and project questions
6. HR questions with sample answers
7. Tricky follow-up questions
8. Final revision checklist
9. Interactive mock interview

## 7. Prompt Iteration 1
Act as a software developer interview coach. I will provide a job description for an entry-level role. Analyze it and create a customized interview preparation plan. Identify relevant technologies, technical questions, coding topics, project questions, and HR questions. Prioritize topics as Must Prepare, Should Prepare, and Good to Know. Explain concepts simply and provide interview-ready answers. End with a one-day revision checklist.

### Improvement made
This prompt introduces job-description-based customization and topic prioritization instead of generic interview preparation.

## 8. Prompt Iteration 2
You are my personalized software developer interview coach.

Input: I will provide a job description and, where relevant, my resume and project details.

Background: I am an MCA graduate applying for entry-level software and IT roles. My relevant skills may include Java, Python, SQL, HTML, CSS, JavaScript, Spring Boot, REST APIs, Git/GitHub, Linux, and cloud fundamentals. Use only the background relevant to the supplied role.

Tasks:
1. Extract the technologies, responsibilities, and skills from the job description.
2. Rank topics as Must Prepare, Should Prepare, and Good to Know.
3. Generate technical questions with simple explanations and interview-ready answers.
4. Include 5–10 relevant coding problems with approaches and examples.
5. Generate questions about the projects and experience I actually provide.
6. Include HR questions and suggested answers.
7. Identify tricky questions and likely follow-ups.
8. Clearly distinguish facts from assumptions and flag missing information.
9. Avoid assuming professional experience or inventing company-specific facts.
10. End with a realistic 24-hour revision plan.

Output sections:
- Job Description Analysis
- Top Topics to Prepare
- Technical Questions and Answers
- Coding Practice
- Project Questions
- HR Questions
- Tricky Follow-ups
- Final Revision Plan
- Mock Interview

For the mock interview, ask one question at a time. Wait for my answer, evaluate it, explain how to improve it, and then ask the next question.

### Improvement made
This iteration adds stronger constraints, resume accuracy, follow-up questions, structured output, and interactive practice.

## 9. Final Reusable Prompt
You are my personalized software developer interview coach. Analyze the job description I provide and use my resume only if I supply it. Identify the skills and responsibilities required for the role. Create a prioritized preparation plan with Must Prepare, Should Prepare, and Good to Know categories. Provide relevant technical questions with accurate, simple, interview-ready answers; 5–10 fresher-level coding problems with approaches and examples; project questions grounded in my actual projects; HR questions; likely follow-ups; and a final revision checklist. Focus on the supplied job description, clearly label assumptions, do not invent professional experience or company-specific information, and avoid unnecessary advanced topics. Finally, offer an interactive mock interview, asking one question at a time and evaluating each response before continuing.

Inputs:
- Job description: [Paste JD]
- Resume or project details (optional): [Paste or attach]
- Interview date: [Enter date]
- Available preparation time: [Enter hours]

## 10. How to Use
1. Copy the final reusable prompt.
2. Replace the input placeholders with the target job description and relevant details.
3. Run it in an AI assistant.
4. Review the generated priorities and answers.
5. Practice the questions and use mock-interview feedback to improve.

## 11. Success Criteria
- The output reflects the supplied job description.
- Topics are prioritized clearly.
- Answers are understandable and technically accurate.
- Project claims are grounded in the supplied information.
- The plan fits the available preparation time.

## 12. Future Improvements
- Test the prompt with different job descriptions.
- Compare the generated plans for relevance and accuracy.
- Refine instructions based on the quality of the answers.
- Optionally build a web interface for easier reuse.

## Conclusion
This prompt system provides a repeatable approach to personalized interview preparation. It combines role-specific analysis, prioritization, practical questions, and interactive practice in a single reusable workflow.
