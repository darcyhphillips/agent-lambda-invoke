<!-- DOCUMENTATION -->
## Documentation

AWS documentation [is available here](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html).

Langchain agent documentation [can be found here](https://python.langchain.com/docs/modules/agents/tools.html).

Create your OpenAI key [here](https://openai.com/) by using the **Getting Started** button.

YouTube inspiration:
[Create Custom Tools for Chatbots in LangChain — LangChain #8](https://www.youtube.com/watch?v=q-HNphrWsDE&list=PLRmfjgxkmfP0q6vBXZUFTzMX7RbKjDzAg&index=2&t=975s&pp=gAQBiAQB)
[Building Custom Tools and Agents with LangChain (gpt-3.5-turbo)](https://www.youtube.com/watch?v=biS8G8x8DdA&list=PLRmfjgxkmfP0q6vBXZUFTzMX7RbKjDzAg&index=3&pp=gAQBiAQB)


<!-- WHAT IS DOES -->
## What does this agent do?

This [Langchain](https://docs.langchain.com/docs/) agent is used to accomplish the same things as this [AWS Lex project](https://github.com/darcyhphillips/lex-ops-fw-tasks) without using Lex. 


<!-- GETTING STARTED -->
## Getting Started

1. To get started use the agent-lambda-invoke.ipynb notebook.

2. Create a keys.py file and define the following variables
```
apikey=''
aws_access_key_id=''
aws_secret_access_key=''
``` 

3. Replace the following lines in lambdaHTTPS.py
```
security_group_id = "" # add SG Id
cidr = "" # add CIDR
```

4. Replace the following lines in lambdaRMQ.py
```
security_group_id = ""# add SG Id
```
