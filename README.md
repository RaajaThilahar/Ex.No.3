# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### NAME : A.VIJAY
### DATE : 28.08.2025                                                                         
### REGISTER NUMBER : 212223080055

### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting  

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type
Procedure:
1.	Define the Scenario and Use Case:
Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.
Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.


Main Objectives:

•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

•	Prompt: “What features can be incorporated into the automation system to optimize production and reduce downtime?” Generated Ideas:
•	Sensors for real-time monitoring of equipment performance.
•	Predictive maintenance alerts to anticipate equipment failures.
•	Energy usage optimization by automating the switching of machines on/off based on demand.
•	Cloud-based dashboards for remote monitoring and control of machinery.

Persona and Context Prompts:

•	Prompt: “What should the user interface and control system convey to the operators and managers?” Generated Context:
•	The user interface should be intuitive and provide real-time data on machine performance, energy usage, and alerts.
•	The system should convey reliability and ease of use, with minimal training required for operators.
### Output
 
# Case Study 1: Designing a Customer-Support Chatbot with Prompting Strategies

## Introduction

The goal is to design an **AI-powered chatbot** that assists customers in resolving issues related to **product troubleshooting, order tracking, and general inquiries**. The chatbot must remain **conversational, efficient, and user-friendly**. Prompt engineering plays a crucial role in ensuring that the model understands customer intent and responds appropriately. This case study explores **three prompting patterns** applied to the same scenario.

---

## 1. Straightforward Prompts

**Description:**
A direct approach where the user’s query is answered without additional structure. This is the most basic form of prompting, good for simple, well-defined queries.

**Example Prompt:**

* *User:* “My order hasn’t arrived yet. Can you help me track it?”
* *Chatbot Prompt (to LLM):*
  “You are a customer support assistant. A user wants to track their order. Provide a helpful and polite response.”

**Expected Response:**
“Sure! Could you please provide your order number so I can look it up for you?”

**Strengths:**

* Fast and simple.
* Works well for single-turn questions.

**Weaknesses:**

* Lacks structure for complex, multi-step interactions.
* May require more clarification rounds.

---

## 2. Tabular Format Prompting

**Description:**
The chatbot is guided to output information in a **structured table**. This ensures clarity and easy readability, especially for troubleshooting or product comparison tasks.

**Example Prompt:**

* *User:* “I’m facing issues with my wireless headphones.”
* *Chatbot Prompt (to LLM):*
  “You are a support assistant. Summarize troubleshooting steps for wireless headphones in a clear table with columns: Issue, Possible Cause, Solution.”

**Expected Response (Chatbot):**

| Issue                | Possible Cause          | Solution                               |
| -------------------- | ----------------------- | -------------------------------------- |
| No sound             | Bluetooth not connected | Re-pair headphones with device         |
| Distorted audio      | Low battery             | Charge headphones fully                |
| Left ear not working | Hardware fault          | Contact support or request replacement |

**Strengths:**

* Highly readable and structured.
* Ideal for troubleshooting and FAQs.

**Weaknesses:**

* Less conversational tone.
* May feel robotic if overused.

---

## 3. Preceding Question Prompting

**Description:**
The chatbot **asks clarifying questions first** before giving the final answer. This ensures accuracy and improves user satisfaction in multi-turn conversations.

**Example Prompt:**

* *User:* “My order hasn’t arrived.”
* *Chatbot Prompt (to LLM):*
  “You are a helpful assistant. Before giving the answer, always ask clarifying questions to gather required details.”

**Expected Response (Chatbot):**
“I’m sorry to hear that your order hasn’t arrived yet. Could you please share your order number and the date of purchase so I can check the status for you?”

**Strengths:**

* Builds conversational flow.
* Ensures responses are accurate and context-aware.

**Weaknesses:**

* Adds extra steps, which may frustrate users seeking quick answers.

---

## Comparison of Prompting Methods

| Prompting Method             | Best Use Case                        | Pros                           | Cons                                       |
| ---------------------------- | ------------------------------------ | ------------------------------ | ------------------------------------------ |
| Straightforward Prompting    | Quick answers, FAQs                  | Simple, fast                   | May lack depth, poor in multi-turn queries |
| Tabular Format Prompting     | Troubleshooting, structured info     | Clear, easy to read, organized | Less conversational                        |
| Preceding Question Prompting | Order tracking, personalized queries | More accurate, builds rapport  | Can feel slower due to extra questioning   |

---

## Conclusion

By using **different prompting strategies**, the chatbot can handle diverse scenarios effectively:

* **Straightforward prompts** for FAQs and quick answers.
* **Tabular prompts** for structured troubleshooting and comparisons.
* **Preceding question prompts** for order tracking and complex problem resolution.

Combining these strategies allows for a **balanced, customer-friendly AI chatbot**

# Result:
    The project was completed successfully within the deadline

