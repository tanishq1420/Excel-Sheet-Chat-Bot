# Excel-Sheet-Chat-Bot

## Setup

1. install dependencies using ```pip install -r requirements.txt```
2. create a mysql server using ```mysql -u {username} -p{password}```
3. use ```langflow run``` and open interface using the access url
4. from google sheets export file as ```.xlxs``` and copy absolute ```PATH``` of file, example - ```/Users/tanishq/Desktop/Ema/Ema.xlsx```

## Demo 

1. create new blank project in langflow and import the file ```SQL-Agent.json``` provided in the repo
2. in ```XLSXComponent``` enter ```PATH``` (of ```.xlxs``` file)
3. in ```OpenAI``` and ```ChatOpenAI``` component, enter GPT4 API key
4. in ```SQLDatabaseCreate``` enter host: ```localhost```, user: ```{username}```, password: ```{password}```
5. build the component ```SQLDatabaseCreate``` and copy the generated output database URI
<img src="1.png" alt="drawing" width="300"/>
<img src="2.png" alt="drawing" width="300"/>

6. enter the database URI in ```SQLAgent```
7. build ```Chat Output```
<img src="3.png" alt="drawing" width="300"/>

8. use the playground to interact with the chat-bot
<img src="4.png" alt="drawing" width="500"/>
<img src="5.png" alt="drawing" width="500"/>
