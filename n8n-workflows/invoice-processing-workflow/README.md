#Invoice Processing Workflow

**Description**
This workflow is triggered when a new file is created in drive. The file is then downloaded, extracted and fed into an information extractor. The information extracted is then fed into a database to update it. Using the information an email is also crafted using an LLM and the to the recipient of the email

**Nodes Used**
- Google Drive trigger
- Google Drive Download a file
- Extract form File
- Information Extractor: Model: OpenRouter: Model- Meta-llama
- Google sheets
- Gemini
- Gmail
  

