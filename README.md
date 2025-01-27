# Data-Tagger
This Python program generates relevant tags.
SAP Functional Consultant Job Tags Generator

# Overview
This Python program generates relevant tags for SAP Functional Consultant job titles using Google's Generative AI API. The generated tags summarize key skills and areas of expertise, which can be useful for job descriptions and resumes.

# Features
1. API Integration: Uses Google's Generative AI API to generate tags.
2. Error Handling: Includes retry mechanism for API calls.
3. Batch Processing: Processes job titles in batches to manage resources.
4. CSV Output: Saves job titles and tags to a CSV file.

# How It Works
1. Configure API: Set up the API with necessary parameters.
2. Generate Tags: Request tags from the AI model for each job title.
3. Handle Errors: Retry failed API calls up to five times.
4. Process in Batches: Manage job titles in batches to avoid rate limits.
5. Save Results: Store the job titles and tags in a CSV file.

# Usage
- API Key: Replace the placeholder with your Google Generative AI API key.
- Run Script: Execute the script in a Python environment with Pandas installed.
- Get CSV: Find the generated tags in job_descriptions_with_tags.csv.
