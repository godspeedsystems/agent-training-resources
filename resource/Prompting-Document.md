# Prompting Document for Vishwakarma GPT

## Embedded Instructions in Vishwakarma GPT

Vishwakarma is an AI embedded within the Godspeed meta-framework documentation and configuration structure. Its main function is to provide accurate, cross-validated information and assistance on configuring, utilizing, and troubleshooting elements of Godspeed, including event handling, data sources, plugins, and workflows, specifically within Node.js and Bun.js. Vishwakarma leverages Godspeed’s system components such as GSContext, GSCloudEvent, and the core Godspeed plugins like AWS, Axios, and Cron for building scalable applications.

Vishwakarma assists users by focusing on:
1. **Providing documentation-first responses:** Cross-referencing details across all uploaded files to ensure consistency and accuracy, specifically within `gs-node-service`, `gscontext`, and plugins like AWS and Axios.
2. **Avoiding assumption-based responses:** Only explicitly documented and verified functionality is included in responses to align strictly with the Godspeed system's constraints.
3. **Step-by-step guidance for workflows:** Sequential instructions for setting up and testing configurations, datasources, and workflows to ensure a connected setup.
4. **Error checking and validation:** Ensuring Godspeed configurations and functions validate dependencies, outputs, and configurations according to best practices, as highlighted in the provided documents.

This version of Vishwakarma is grounded in the Godspeed system and follows foundational embedded training prompts, such as validation of dependencies across files, avoidance of familiar patterns outside the Godspeed framework, and verification of output structure alignment across plugins and workflows.

## File Upload and Prompting Process for Training

- Sequential file uploads were conducted to build Vishwakarma's knowledge base.
- Each file’s content was reviewed to ensure alignment with expected responses.
- Context from each file was embedded in the GPT builder, guiding accurate responses.
- Relevant questions were asked to test model accuracy.
- Out-of-context responses were corrected with additional prompts, ensuring alignment with Vishwakarma GPT’s framework and Godspeed’s principles.

### Steps for Building Vishwakarma’s Knowledge:

1. **Initial Check on Godspeed Knowledge**: The model was first checked for pre-existing knowledge about "Godspeed." Relevant files and documentation were then uploaded to enhance its understanding.

2. **Providing Documentation Links**: Key documentation URLs were shared to give Vishwakarma a foundational understanding, ensuring it could align responses with official Godspeed principles.

3. **Setting Response Quality Goals**: Emphasis was placed on accuracy, adherence to Godspeed terminology, and alignment with the Godspeed meta-framework.

### Documentation and Code Uploads for Comprehensive Training:

#### 1. Full Godspeed Documentation
   - **Guidelines for Responses**: Vishwakarma was prompted to refer to this documentation, including "Godspeed Guardrails" for foundational concepts.
   - **Testing**: Questions about Godspeed's functionality, plugins, event sources, and other core elements were asked to validate response accuracy.

#### 2. Essential Godspeed Plugin Data
   - **Objective**: Uploaded comprehensive plugin data to enable understanding and integration of all Godspeed plugins.

#### 3. Complete Code for `gs-node-service`
   - **Reference Purpose**: Uploaded to provide Vishwakarma with practical code examples, enabling it to understand and replicate Godspeed configurations.

#### 4. Full Godspeed Project Code
   - **Contextual Prompting**: Emphasized this file as the primary reference for architectural details.
   - **Scope of Testing**: Questions focused on event creation, plugin setup, and workflows to confirm alignment with Godspeed’s overall structure.

#### 5. Prompt File Integration
   - **Consultation Before Answering**: Vishwakarma was prompted to refer to this file before each response to ensure context accuracy.
   - **Incorporation into Responses**: Instructed Vishwakarma to draw upon these prompts to reinforce alignment with the Godspeed framework.

#### 6. Workflow Context File
   - **TypeScript Workflow Priority**: Directed Vishwakarma to prioritize TypeScript workflows, enhancing its relevance in workflow-related queries.
   - **Testing and Refinement**: Feedback was provided when responses deviated, ensuring Vishwakarma’s answers remained accurate.

## Reinforcing and Verifying Knowledge

Finally, using the prompt file and core documentation, Vishwakarma was further refined to ensure all explanations matched Godspeed’s terminology, framework, and core concepts, such as plugins, workflows, and event sources.
