# Snowflake Cortex AI & Snowpark Resume Agent

This project demonstrates an end-to-end AI-driven resume optimization workflow leveraging **Snowflake Cortex** and **Snowpark Python**.

### Key Features
- **Snowflake Cortex Integration**: Direct LLM inference using `SNOWFLAKE.CORTEX.COMPLETE` for high-performance text generation.
- **Secure Snowpark Session Management**: Python-based connectivity to Snowflake data infrastructure.
- **Production-Ready Security**: 
  - Implementation of **parameterized SQL queries** to prevent SQL Injection.
  - Complete **data sanitization** for public repository sharing.
- **Automated Logging**: Tracks LLM interactions directly into Snowflake tables for audit and fine-tuning.

### Tech Stack
- **Languages**: Python 3.9+
- **Cloud**: Snowflake (Cortex AI, Snowpark)
- **Libraries**: `snowflake-snowpark-python`# Snowflake-Cortex-AI
