# Personal-GPT

Use OpenAI chatGPT on your own data

### Installation

Install the packages

`pip install langchain chromadb openai tiktoken`

Create a constants.py file and add your own OpenAI API key there, eg - APIKEY = " "

Place your own data as a txt file in the data folder or modify the data.txt in there.

## Example

Checking on myResume.txt file

``` >python gpt.py "what is my email in resume"
what is my email in resume
Based on the information provided in the resume, your email address is adhikaryjayanta@outlook.com.
```
