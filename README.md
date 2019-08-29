# Github issues + Standuply Tasks
Integration between Github Issues and Standuply

## This is the URL for the request on Glo

```
https://gloapi.gitkraken.com/v1/glo/boards/5d67ecaac3bf7c0015ae6afe/cards
```
## This is the response from Glo Boards

``` JSON
[
  {
    "column_id": "5d67ed74c3bf7c0015ae6b20",
    "board_id": "5d67ecaac3bf7c0015ae6afe",
    "name": "Propuesta para Amigo Gutters",
    "id": "5d67ed430be081000fc71499"
  }
]
```

## JSON feed for Standuply

```JSON
{  
   "ok":true,
   "items":[  
      {  
         "id":1,
         "name":"Task 1",
         "url":"https://google.com"
      },
      {  
         "id":2,
         "name":"Task 2",
         "url":"https://bing.com"
      },
      {  
         "id":3,
         "name":"Task 3",
         "url":"https://duckduckgo.com"
      }
   ]
}
```
