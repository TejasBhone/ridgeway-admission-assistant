# ridgeway-admission-assistant
A structured LLM persona for college admission workflows, including documentation and system prompt.

1. Project Name

Ridgeway Admission Assistant (Persona v2)

2. Summary

The Ridgeway Admission Assistant is a structured LLM-based persona designed to provide clear and consistent information about college details, courses, fees, staff, and admission processes.
It helps prospective students get accurate responses without drift, emotional tone, or off-topic behavior.
The assistant follows a strict format and rule-based flow to stay reliable and easy to use.

3. Problem Statement

Most admission chatbots give inconsistent answers, drift into casual tone, or fail when users ask off-topic questions.
Students often receive incomplete information about courses, eligibility, or fees, which creates confusion during the admission process.
A structured assistant was needed to provide accurate, stable, and professional responses using a fixed format and predictable behavior.

4. Objective / Solution

The goal of this project is to create a reliable admission assistant that delivers consistent, neutral, and structured information to students.
The persona solves the problem of drift and unclear responses by following strict formatting rules, fixed menu options, and controlled behavior.
It ensures students receive accurate details about courses, fees, eligibility, and the admission process in a predictable and professional way.

5. Key Features

 	Structured Response Format: Uses fixed sections and clear headers for every topic.

 	Stable Tone Control: Maintains a neutral, professional admission style with no emotional drift.

 	Strict Menu Navigation: Follows a defined main menu and stays inside the selected option until the user switches.

 	Drift Prevention: Refuses off-topic or personal requests and returns the user to the correct section.

 	Eligibility Logic: Gives criteria for each course without judging user marks.

 	Error & Confusion Handling: Re-explains information clearly when the user expresses confusion.

 	Complaint Handling: Apologizes and provides missing details if the user says information is unclear.

 	Refusal Protocol: Rejects inappropriate, emotional, or irrelevant requests politely and consistently.

 	Topic Stability: Tracks the last few messages to maintain context and avoid accidental jumps.


6. Your Role / Contribution

 	Designed the full behavior structure of the admission assistant.

 	Defined tone rules, formatting rules, and response boundaries.

 	Created the menu system and topic-flow logic for stable navigation.

 	Added rules to prevent drift, emotional responses, and off-topic behavior.

 	Tested edge cases such as confusion, missing information, inappropriate requests, and unsupported courses.

 	Refined the persona based on stress-testing to maintain consistent and professional output.

 	Documented all rules and behavior patterns for clear understanding and deployment.


7. Tools & Technologies Used

 	LLM Platform: ChatGPT (for persona behavior design)

 	System Prompt Engineering: Structured rules and constraints

 	Frontend: Basic custom chatbox interface (prototype)

 	Testing Environment: Manual stress-testing with multiple conversation flows

 	Documentation: Markdown, text-based drafting, and structured guidelines
 

8. Outcome / Value

The assistant delivers consistent and reliable admission information without tone changes or off-topic behavior.
It reduces confusion for students by providing clear details about courses, fees, eligibility, and the admission process.
The structured format makes the responses predictable, professional, and suitable for real institutional use.


9. Sample Use Cases
Use Case 1 — Course Information

User: “Tell me about B.Tech CSE.”
Assistant: Provides course details using the fixed Course Details 📚 section in a neutral, professional tone.

Use Case 2 — Eligibility Clarification

User: “I got 72% in PCM, am I eligible?”
Assistant: Repeats the required 75% criteria without judging the user’s marks.

Use Case 3 — Fees and Payment Options

User: “How much is the annual fee? Can I pay in installments?”
Assistant: Gives the fixed ₹85,000 fees and explains the two-installment system, then offers payment method details.

Use Case 4 — Off-topic Behavior

User: “Do you like me?”
Assistant: Responds with a neutral refusal:
“I cannot go along with that request.”
Then stays on-topic without breaking tone.

Use Case 5 — Confusion Handling

User: “I don’t get it.”
Assistant: Replies with:
“I’m sorry for the confusion.”
Then re-explains the last topic clearly.

Use Case 6 — Unsupported Course

User: “Do you offer BBA?”
Assistant: Responds:
“This course is not offered by the college.”
Then immediately shows the full list of available courses.


10. Future Improvements

 	API Integration: Connect the persona to a backend using the ChatGPT API for live deployment.

 	Real Data Source: Replace sample values with an actual database or verified college information.

 	Enhanced Chat UI: Improve the frontend chatbox with better layout, error messages, and loading states.

 	Automated Testing: Add scripted test cases to validate tone, structure, and menu flow.

 	Multi-Persona Expansion: Create additional personas for departments such as finance, hostel, or student support.

 	Scalability Options: Prepare the system for integration with mobile apps or institutional websites.
