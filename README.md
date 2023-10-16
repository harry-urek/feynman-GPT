# Feynman-GPT
An Open Source LLM &amp; Web Scrapper based tool to Study and Do research about any Topic



### Description of I want it to be
 
    App which helps you do whatever chatgpt does but without paying for it and is more user friendly Research oriented rather than spouting alot of nonsense for no reason and is able to run on your local machine .
    Main goal is feed it any pdf and get full summarry about every Topic almost like your Toper friend during exams.


## TECH STACK
- LangChain
- Vectore Store
- Web Scrapper
- Api support Through FastAPI
- Easy Frontend UI maybe maybe Streamlit or Chainlit (idk rn)
- CTransformer for quantized model acces and CPU runtime
- LLAMA-2 might try other models main goal is to get fast Result on less powerful machines


## TO-DO
- [ ] Make A pdf Upload and feed to LLm to learn using Recursive chains
- [ ] Implement it using FastApi 
- [ ] Add Vectore Store and Redis-Chaching
- [ ] If possible only use Redis-Vector Store or Try SurrealDb for caching and 
- [ ] Dockerize it for easy run on local Systems
- [ ] get pdf from user and List of Topics related to that pdf &amp; run Web Scrappers to get more info from web and then feed it into vectore store for better and detailed Qs and As of that Topic

## GOALS
- [ ] Make it Open Source and try to use only FOSS
- [ ] User freindly and Topic Oriented Results
- [ ] Able to run on CPU with 8 gigs
- [ ] Add Web Scrapper to get data about specific topic and feed it to LLM for better detailed results
- [ ] Allow it use other models too like serge chat
- [ ] Make it more Ed-Tech oriented rather than chatbot oriented