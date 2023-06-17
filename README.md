# GOParser
URL Parser From TEXT / JSON Build with GO

Before parsed :
```{
"1": [
    {"name": "link 1",
        "url": "https://url-for-link-1.com"},
    {"name": "link 2",
        "url": "https://url-for-link-2.com"},
    {"name": "link 3",
        "url": "https://url-for-link-3.com"}
    ],
"2": [
    {"name": "link 4",
        "url": "https://url-for-link-4.com"},
    {"name": "link 5",
        "url": "https://url-for-link-5.com"},
    {"name": "link 6",
        "url": "https://url-for-link-6.com"}
    ]   
}```

After parsed :

```
https://url-for-link-1.com
https://url-for-link-2.com
https://url-for-link-3.com
https://url-for-link-4.com
https://url-for-link-5.com
https://url-for-link-6.com```

Preview :
<img src="https://raw.githubusercontent.com/yon3zu/GOParser/main/goparser.png" height="400">
