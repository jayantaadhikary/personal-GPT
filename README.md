# Personal-GPT

Use OpenAI chatGPT on your own data

### Installation

Install the packages

`pip install langchain chromadb openai tiktoken`

Create a constants.py file and add your own OpenAI API key there, eg - APIKEY = " "

Place your own data as a txt file in the data folder or modify the data.txt in there.

## Example

Checking on myResume.txt file

``` > python chatgpt.py "summarize my resume"
summarize my resume

Jayanta Adhikary is a skilled Information Technology student with a Bachelor's degree from Sikkim Manipal Institute of Technology. He has practical experience as an Information Systems Trainee at Indian Oil Corporation Limited, where he implemented the LDAP protocol and developed a mock frontend using ReactJS. Jayanta has proficiency in various programming languages such as Python, JavaScript, Java, and SQL. He is also skilled in frameworks/libraries like ReactJS, React Native, and NodeJS. Additionally, Jayanta has excellent interpersonal skills, including time management, teamwork, and communication. He has completed projects using React Native and Firebase, demonstrating his expertise in front-end development and real-time database management.```
