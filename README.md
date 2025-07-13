# Step by Step Guide to Running LangSmith Experiment with DeepEval


This is a notebook guide that illustrates how to incorporate the opensource deepeval package in running LangSmith Evaluations. 



## Environment Setup 

### Clone the repo
```
git clone https://github.com/catherine-langchain/langsmith-deepeval-guide.git
```

### API Keys

* If you don't have an OpenAI API key, you can sign up [here](https://openai.com/index/openai-api/), or adapt the sample code to use your preferred model. 
* Generate a LangSmith API key in your LangSmith instance. 

### Set Environment Variables

* Create a `.env` file in the root directory:
```shell
# Copy the .env.example file to .env
cp .env.example .env
```
If you are on a self-hosted instance, change the default `LANGSMITH_ENDPOINT` accordingly. 
