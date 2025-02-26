

# Google Docs Markdown Converter

## Description
This script converts a markdown-formatted meeting note into a structured Google Docs document using the Google Docs API. It parses markdown syntax and applies proper formatting (headings, bullets, checkboxes) in the created document.

## Setup Instructions
1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. **Upload `client_secret.json`**: Obtain your Google OAuth client secret JSON file and upload it to `/content/` in Google Colab.

3. **Install Required Libraries** (in Colab or locally):
   ```python
   !pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
   ```

## Dependencies
- Python
- Google Colab (or local execution)
- Google APIs Client Library
- Google Authentication Libraries

## How to Run in Colab
1. Open Google Colab and upload the script.
2. Upload `client_secret.json` to authenticate with Google Docs API.
3. Run the script cells sequentially.
4. Follow the authentication steps in the Colab output to grant necessary permissions.
5. Upon successful execution, the script will generate a Google Doc and output the document link.

## Output
- A Google Docs document with formatted meeting notes.
- A link to the generated document printed in the console.

