# Snowflake Cortex AI Career Agent: Dynamic Resume Optimization

A production-grade conversational AI agent built on **Snowpark Python** and **Snowflake Cortex AI**. This project demonstrates advanced data engineering practices and LLM integration within a secure cloud data ecosystem.

### 🌟 Core Capabilities
- **Rolling Memory Architecture**: Implemented an automated summarization logic to maintain context continuity while optimizing token usage and performance—managed natively within Snowflake tables.
- **Enterprise-Grade Security**: 
    - Full **Data Sanitization** to protect internal infrastructure details.
    - Implementation of **Parameterized SQL Queries** (Bind Variables) to eliminate SQL Injection risks.
- **Native AI Integration**: Leverages `SNOWFLAKE.CORTEX.COMPLETE` with **Claude Sonnet (`claude-sonnet-4-6`)** for state-of-the-art reasoning without data exfiltration.
- **Session Persistence**: Features a robust session management system to list, resume, and track multiple optimization projects across different users.

### 🛠 Tech Stack
- **Cloud Data Platform**: Snowflake (Snowpark, Cortex AI)
- **AI Model**: Claude Sonnet (`claude-sonnet-4-6`)
- **Programming**: Python 3.9+, Snowflake SQL
- **Framework**: Object-Oriented Design (OOD) for modularity.
