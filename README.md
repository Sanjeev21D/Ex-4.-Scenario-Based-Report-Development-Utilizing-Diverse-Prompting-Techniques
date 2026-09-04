# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim: 
To design and test prompts using diverse AI prompting techniques (zero-shot, few-shot, role-based, and chain-of-thought) to build an AI-powered customer support chatbot for a retail business, and to document the prompts, outputs, and results.
## Algorithm: 
1. Define the chatbot's purpose — handling customer inquiries, order tracking, returns, and complaints.
2. Identify common customer scenarios in a retail environment.
3. Select different prompting techniques to compare (zero-shot, few-shot, role-based, chain-of-thought).
4. Write a tailored prompt for each technique targeting the same scenario.
5. Run each prompt on an AI model (e.g., ChatGPT/Gemini/Claude) and record the response.
6. Evaluate each output for accuracy, tone, and helpfulness.
7. Capture screenshots of each output as evidence.
8. Compare results across techniques and note which performed best.
9. Summarize findings in the Result section.
## Prompt:
**1. Zero-Shot Prompt**
"You are a customer support chatbot for a retail store. A customer asks: 'My order hasn't arrived yet, it's been 5 days.' Respond appropriately."

**2. Few-Shot Prompt**
"Here are examples of chatbot responses to customer complaints:
Q: 'My product arrived damaged.' A: 'I'm sorry to hear that! We'll arrange a free replacement right away.'
Q: 'I want to cancel my order.' A: 'No problem, I've cancelled your order and initiated a refund.'
Now respond to: 'My order hasn't arrived yet, it's been 5 days.'"

**3. Role-Based / Persona Prompt**
"Act as a friendly and empathetic retail customer support agent named Maya. A customer says their order hasn't arrived in 5 days. Respond in Maya's voice."

**4. Chain-of-Thought Prompt**
"A customer says their order hasn't arrived in 5 days. Think step by step: (1) acknowledge the issue, (2) apologize, (3) check possible delay reasons, (4) offer a solution, (5) close politely. Then write the final response."
## Output:
**1. Zero-Shot Output:**
"I'm really sorry for the delay with your order! I understand how frustrating that can be. Let me check the status for you — could you please share your order number? In the meantime, I'll also flag this with our logistics team to see if there's a delay on their end. We'll make sure this gets resolved as quickly as possible."

**2. Few-Shot Output:**
"I'm sorry to hear your order hasn't arrived yet! Let me look into this for you right away. Could you share your order ID so I can track its current status? If there's been an unexpected delay, we'll either expedite the shipping or offer you a refund/replacement, whichever you prefer."

**3. Role-Based Output (Maya):**
"Hi there! This is Maya from customer support. I completely understand how annoying it is to wait for a package that's already 5 days late — I'd feel the same way! Let me pull up your order details right now and see what's going on. While I check, is it alright if I also apply a small discount on your next purchase as an apology for the wait?"

**4. Chain-of-Thought Output:**
"Thank you for letting us know about this issue.
1. I completely understand your frustration — 5 days is longer than expected.
2. I sincerely apologize for the inconvenience this has caused.
3. Delays like this can happen due to courier backlogs, incorrect address details, or high demand periods.
4. To resolve this, I'll track your shipment right now and if it's still delayed, I'll arrange either express redelivery or a full refund — your choice.
5. Thank you for your patience, and I'll follow up with an update within the next few hours."
## Result:
The experiment successfully demonstrated how different prompting techniques affect chatbot responses in a retail customer support context. Chain-of-thought and role-based prompts produced more structured and empathetic replies, while zero-shot prompts gave quicker but less personalized answers. This confirms that prompt design directly impacts the quality of AI-generated support responses.
