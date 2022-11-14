# TPA-5

**POST Create New Todo**
```
http://localhost:5000/api/task
```

**BODY** raw
```
{
    "task":"task 1",
    "active":"true"
}
```

**GET Get All Todos**
```
http://localhost:5000/api/task
```


**GET Get Todo By Id**
```
http://localhost:5000/api/task/6372617228d5f3e39aa05493
```


**PUT Update Todo By Id**
```
http://localhost:5000/api/task/6372617228d5f3e39aa05493
```
**BODY** raw
```
{
    "task":"task 3",
    "active":"false"
}
```

**DELETE Delete Todo By Id**
```
http://localhost:5000/api/task/6372617228d5f3e39aa05493
```
