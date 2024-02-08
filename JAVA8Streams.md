# Java8 Streams API Interview Quetions

### Table of Contents
| No. | Questions |
|---- | ---------
|1 | [What is Stream API?](# What is Stream API)|


  1. ### What is Stream API?
     Stream API used for ***processing collections of objects***
     Functionality:
     Operations: It offers a rich set of operations like filtering, mapping, reducing, sorting, etc., allowing you to manipulate and analyze data efficiently.
     Pipelining: Operations can be chained together, forming a pipeline that processes the data step-by-step. This makes code more readable and avoids nested loops.
     Intermediate and Terminal Operations: Intermediate operations transform the stream itself, while terminal operations produce a result from the stream, forcing its evaluation
     
     |Feature	|Intermediate Operations|	Terminal Operations|
     | Purpose|	Transform the stream  |	Produce a final result|
     |Output	|Another stream	|Value or Collection|
     |haining	|Can be chained	Cannot be chained
     |Examples |	filter, map, distinct, sorted	|count, forEach, collect, min, max|
