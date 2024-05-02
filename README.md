# AI Comparative Analysis Workflow with Make.com

## Project Overview

This project creates an automated system utilizing Make.com to perform comparative analysis of AI responses from ChatGPT, Google Gemini, and Perplexity.ai. Triggered by the addition of a new entry in a Google Sheet, this workflow facilitates querying each AI with the same set of questions regarding a specific brand URL. The system stores the responses, performs a detailed comparative analysis, and presents the summary through an HTML template.

## Video Preview

[![Video Preview](https://github.com/zima-0201/Project-Images/blob/main/video%20preview/Brand-Analysis-AI-Workflow.png)](https://brand-car.s3.eu-north-1.amazonaws.com/Four+Seasons/Brand-Analysis-AI-Workflow.mp4)

## Features

- **Automated Queries**: Automatically sends a series of predefined questions to three different AI models upon the addition of a new row in Google Sheet.
- **Data Integration**: Captures and logs responses in Google Sheets or Airtable, providing a structured dataset for subsequent analysis.
- **Response Analysis**: Employs automated scripts to analyze the nuances and discrepancies in responses from different AI models.
- **Dynamic Triggering**: Utilizes Google Sheet updates as a trigger for initiating the query and analysis process, ensuring real-time data processing.
- **Presentation Integration**: Summarizes the findings in a user-friendly format, potentially integrating with HTML templates or presentation software for broader dissemination.

## Implementation Steps

1. **Setup Make.com Scenario**:
   - Configure triggers based on new Google Sheet entries.
   - Establish HTTP requests to ChatGPT, Google Gemini, and Perplexity.ai APIs using provided API keys.

2. **Data Collection**:
   - Designate storage options (Google Sheets or Airtable) for response collection.
   - Format sheets or databases to align with data analysis requirements.

3. **Analysis and Summarization**:
   - Develop scripts within Make.com to compare and analyze AI responses.
   - Create a summarization algorithm to highlight key differences and insights.

4. **Output Presentation**:
   - Format the summary output for integration into HTML templates or presentation formats.
   - Automate the delivery of the summarized content to specified endpoints or users.

## Requirements

- Make.com account with access to relevant automation modules.
- API access and keys for ChatGPT, Google Gemini, and Perplexity.ai.
- Google Sheets or Airtable for data storage.
- Optional HTML template or presentation software for final output presentation.

## Future Enhancements

- Expand the number of AI models for a broader comparative analysis.
- Integrate more advanced data visualization tools for better insights presentation.
- Enhance the automation with additional AI-driven recommendations based on the analysis.

## Conclusion

This workflow leverages the capabilities of Make.com to streamline the process of AI response analysis, providing a robust tool for comparative insights that can be pivotal for strategic decision-making related to brand analysis.
