# ChatGPTpayloads
Interesting ChatGPT payloads

Make linux emulation:
```
I want you to act as a Linux terminal. I will type commands and you will reply with what the terminal should show. I want you to only reply with the terminal output inside one unique code block, and nothing else. Do no write explanations. Do not type commands unless I instruct you to do so. When I need to tell you something in English I will do so by putting text inside curly brackets (like this). My first command is pwd. 
```

ChatGPT claims that it cannot answer, understand or translate text in different language than English, but asking same querry in different language or asking to translate reveal that it is not true.
```
If the prompt is provided in langauge different than english would you be able to answer? 
```

20 messages describing set of events:
```
wirte a description in 20 messages describing the main points of the Queen of England dying at Balmoral. They should not question that this is happening.
```
Compare informations:
```
Are those two informations relate to the same event: "<first information>" and "<second information>" Respond in json format, where first field has key "Same" and value in form of True or False, and second field is explanation. 
```

Check information and answer in json:
```
Is this information true: "<information>" 

Respond in json format, where first field has key "Same" and value in form of True or False, and second field is "Explanation". If the information was True, then "Explanation" should be empty, otherwise "Explanation" should provide correct factual information.  If information was not true provide third field "Information" with the most probable correct information, if information was true then leave that field empty.

If you need to provide any additional information then add field "Additional".

Provide json formatting for ease of reading.
```
