ChatGPT-Clone
==============================
You.com ChatGPT Clone client - Google on steroids

Getting Started
------------
Download / clone the github repository

You can use this client like this:
```python
from ..you_client import ask

response = ask("Hello World !")
print(response)
```
Response example:
```json
 {
    "response": "Hello World is an iconic phrase that is often used as the first program many computer science students create It is also an online gift store in Philadelphia a magazine issue a repository on GitHub an example Express app a minimal Docker example a language learning program and an enrichment program taught by software engineers AI architects data scientists and educators.", 
    "links": null, 
    "extra": null
}

```

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── you_client
    │   └── __init__.py    <- You.com client
    │
    ├── requirements.txt   <- PIP - modules used in the project that are not pre-installed (pip install -r requirements.txt)
    │
    ├── testing          
    │   └── main.py        <- python test file

--------

<p><small>Project based on the <a target="_blank" href="https://you.com/search?q=who+are+you&tbm=youchat">you.com/chat api</a>.</small></p>
