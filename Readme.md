# Cold Email Generator

This Cold Email Generator application generates professional cold emails based on a job posting URL. By entering a job link, the app extracts relevant job details and matches them with your portfolio to create personalized cold emails that highlight your relevant skills and experience.

## Features

- **Automated Job Matching**: Extracts job details from a URL and identifies relevant skills.
- **Personalized Portfolio Integration**: Matches job-required skills with links in your portfolio.
- **Cold Email Generation**: Automatically generates a cold email with the extracted job details and matching portfolio links.
- **User-Friendly Interface**: Built with Streamlit to provide an interactive and intuitive experience.

## Technologies Used

- **Langchain**: Provides the language model to extract job details and generate emails.
- **Streamlit**: Builds the web application for easy access and interaction.
- **Python dotenv**: Manages environment variables securely.
- **WebBaseLoader**: Loads job details from a URL, used to extract job information.
- **Custom Modules (`chains`, `portfolio`, and `utils`)**: Organizes functionality for generating emails, querying portfolio links, and text cleaning.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- [Streamlit](https://docs.streamlit.io/library/get-started/installation)
- [Langchain](https://python.langchain.com/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sush0677/cold-email-generator.git
   cd cold-email-generator
