# How to run?

### STEPS:


### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.11 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app/main.py
```

Now,
```bash
open up you local host and port
```



1) custom docs
2) extract data
3) chunking operation
4) embedding model
4) vector embedding
5) vector database (knowledge base)====== {cromadb, pinecone}
6) retuns rankoutput/ response if k = 3 it will return 3 responses
7) giving context and query to the LLM and finally giving the response to the user


a) python
b) flask (front-end)
c) LLM 
d) vector db
e) S3 bucket
f) CICD (deployment)

