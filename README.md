# AWS XML Transformer & AI-Powered XML Editor

An event-driven cloud automation project for XML data transformation and natural language-based XML editing, developed during my Cloud Developer internship at NTT DATA.

## Project Overview

This project combines AWS cloud services, infrastructure automation, and generative AI to simplify XML data processing and reduce manual editing efforts.

The project consists of two main components that can operate independently.

## 1. AWS XML Transformer

An automated XML transformation pipeline built using AWS services and XSLT.

### Architecture

```mermaid
flowchart LR
    A[XML File Upload] --> B[Amazon S3]
    B --> C[Amazon SQS]
    C --> D[AWS Lambda]
    D --> E[XSLT Transformation]
    E --> F[Transformed XML]
```

### Key Features

- Event-driven cloud architecture
- Automated XML file processing
- XML transformation using XSLT
- Infrastructure as Code with AWS CloudFormation
- Serverless processing with AWS Lambda

## 2. AI-Powered XML Editor

A Streamlit application that enables users to modify XML data through natural language instructions.

### Key Features

- GPT-powered XML editing
- Natural language command processing
- Automated XML modifications
- Interactive XML preview
- User-friendly interface

### Example Use Case

User instruction:

> Change the price of all items in category A to 10.

The application processes the instruction and updates the corresponding XML data.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application and backend development |
| AWS S3 | File storage |
| AWS SQS | Message queuing |
| AWS Lambda | Serverless processing |
| AWS CloudFormation | Infrastructure automation |
| XML & XSLT | Data transformation |
| Streamlit | User interface |
| GPT | Natural language processing |

## My Contributions

- Developed an event-driven XML processing workflow using AWS services.
- Implemented XML transformation logic using Python and XSLT.
- Worked with CloudFormation for infrastructure automation.
- Developed a GPT-powered XML editing interface using Streamlit.
- Combined cloud automation and generative AI to simplify data processing workflows.

## Skills Demonstrated

- Cloud Computing
- Serverless Architecture
- Event-Driven Systems
- Infrastructure as Code
- Python Development
- Generative AI Integration
- XML Data Processing

## Developer

Eda Yaygılı – Software Engineer
