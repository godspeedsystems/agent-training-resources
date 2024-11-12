# Prompting Document for Vishwakarma GPT

## Embedded Instructions in Vishwakarma GPT

Vishwakarma is an AI embedded within the Godspeed meta-framework documentation and configuration structure. Its main function is to provide accurate, cross-validated information and assistance on configuring, utilizing, and troubleshooting elements of Godspeed, including event handling, data sources, plugins, and workflows, specifically within Node.js and Bun.js. Vishwakarma leverages Godspeed’s system components such as GSContext, GSCloudEvent, and the core Godspeed plugins like AWS, Axios, and Cron for building scalable applications.

Vishwakarma assists users by focusing on:
1. **Providing documentation-first responses:** Cross-referencing details across all uploaded files to ensure consistency and accuracy, specifically within `gs-node-service`, `gscontext`, and plugins like AWS and Axios.

2. **Avoiding assumption-based responses:** Only explicitly documented and verified functionality is included in responses to align strictly with the Godspeed system's constraints.

3. **Step-by-step guidance for workflows:** Sequential instructions for setting up and testing configurations, datasources, and workflows to ensure a connected setup.

4. **Error checking and validation:** Ensuring Godspeed configurations and functions validate dependencies, outputs, and configurations according to best practices, as highlighted in the provided documents.

This version of Vishwakarma is grounded in the Godspeed system and follows foundational embedded training prompts, such as validation of dependencies across files, avoidance of familiar patterns outside the Godspeed framework, and verification of output structure alignment across plugins and workflows.

## Prompting and Correcting in the GPT Builder After File Uploads

- After uploading the necessary files, I reviewed the content thoroughly to ensure it aligned with the expected responses.
- I updated the GPT with context from the uploaded files, prompting it in the GPT builder to respond accurately based on this information.
- I tested the model by asking relevant questions; if it answered according to the uploaded content, I proceeded. If it provided out-of-context responses, I gave further details and corrective prompts to align it with the Vishwakarma GPT's framework and Godspeed’s principles.

## 1. Initial Inquiry on Godspeed Knowledge

- Began by asking if the model had any prior information about "Godspeed."
- If it did not, I proceeded to upload relevant documentation and files for the GPT to learn.

## 2. Providing Godspeed Documentation URL

- Shared the URL for Godspeed documentation to give the model a foundational understanding.
- Used this as a reference to ensure it could pull responses that aligned with official Godspeed guidelines and principles.

## 3. Setting Objective for Response Quality

- Specified that the goal was to have the model respond in line with the Godspeed meta-framework.
- Emphasized accuracy, adherence to Godspeed's terminologies, and response structure.

## 4. File Upload and Documentation Feeding Process

- Sequentially uploaded various types of documentation to build a comprehensive knowledge base in the GPT builder.

### 4.1 Uploaded Full Godspeed Documentation (Markdown File)

- **4.1.1 Prompting:** Instructed the model to refer to this documentation when generating responses.
- **4.1.2 Specific Instruction:** Guided the model to always include "Godspeed Guardrails" in responses, especially when explaining what Godspeed is.
- **4.1.3 Testing Coverage:** Tested the model's response accuracy by asking questions about how Godspeed functions, plugin integration, event sources, and other core concepts.

### 4.2 Uploaded File with Essential Godspeed Plugin Data

- Ensured the model understood plugin integration by adding comprehensive details about all available plugins in Godspeed.

### 4.3 Uploaded Complete Code for `gs-node-service`

- Provided an in-depth reference for the model to understand practical code implementations within Godspeed.

### 4.4 Uploaded Complete Godspeed Project Code

- **4.4.1 Prompting for Full Context:** Specified that this file provided a complete view of Godspeed's architecture, emphasizing that responses should leverage this file for in-depth explanations.
- **Testing Scope:** After uploading, I tested the model’s responses on topics like creating events, setting up plugins, and understanding workflows in Godspeed.

### 4.5 Uploaded Prompt File

- **4.5.1 Prompt Before Answering:** Guided the model to consult this prompt file before responding to ensure context alignment.
- **4.5.2 Builder Integration:** Instructed the GPT builder to incorporate the complete data from this prompt file closely, ensuring responses followed the guidelines set within these prompts.

### 4.6 Uploaded Context File for GS Workflow Creation

- **4.6.1 TypeScript Workflow Priority:** Indicated to the model to prioritize TypeScript workflows.
- **4.6.2 Testing and Adjustment:** Conducted tests specifically on workflow-related responses. If the model provided out-of-context answers, I gave corrective feedback for accuracy.

## 5. Iteration and Correction Process

- **Step-by-Step Testing:** After each file upload and prompt instruction, I conducted thorough testing by asking specific questions related to the uploaded content.
- **Feedback for Out-of-Context Responses:** If responses deviated, I provided precise feedback and additional prompts to recalibrate the model’s understanding.

## 6. Prompt Reinforcement and Knowledge Verification

- Used the prompt file and Godspeed documentation to refine the model’s responses further, ensuring all explanations aligned with Godspeed’s framework and terminology.
- Reiterated critical instructions on answering accurately about Godspeed’s core concepts, like plugins, workflows, and event sources, by referencing the detailed documentation.
