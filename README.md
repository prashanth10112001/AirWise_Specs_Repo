# AirWise: Reproducibility Materials

This repository provides supplementary materials for the paper:

"AirWise: LLM-Powered Smart Air Quality Monitoring and Automated Appliance Control"
Submitted to AIEI 2026.

## Repository Structure

### 1_Sensors_Used

Contains the exact hardware sensor models deployed in the system, including
measurement range, accuracy, and sampling specifications.

### 2_Prompt_and_Output

Contains:

- The verbatim LLM prompt used in experiments
- The JSON output schema enforced before actuation
- Representative LLM outputs from real-world IAQ scenarios

LLM Model Used:
Gemini 2.5 Flash (cloud-hosted)

All LLM outputs were validated against a JSON schema and safety constraints prior to appliance control.
