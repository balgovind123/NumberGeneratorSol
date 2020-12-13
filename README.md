# NumberGeneratorSol
Qns:-
Write a spring boot application that generates a sequence of numbers in the decreasing order till 0. Simulate that the function to generate a  number takes a random time – say between 10 to 30 seconds .
Steps:-
Run as a spring boot application
Postman Request Bodies:-
1.
POST /api/generate HTTP/1.1
Host: localhost:8080
Content-Type: application/json
Cache-Control: no-cache
Postman-Token: e7d61881-5ae3-80d6-6cfa-de43e149ae8f

{"goal":"10","step":"2"}
2.
POST /api/bulkGenerate HTTP/1.1
Host: localhost:8080
Content-Type: application/json
Cache-Control: no-cache
Postman-Token: 4fe85467-cd0a-4fbb-8bcd-eed074815d0d

[{"goal":"10","step":"2"},
{"goal":"100","step":"3"}]
3.
GET /api/task/{uuid}?action=number HTTP/1.1
Host: localhost:8080
Content-Type: application/json
Cache-Control: no-cache
Postman-Token: 15c003cc-068c-4d6a-fbc2-9a3834286a06
4.
GET /api/task/{uuid}/status HTTP/1.1
Host: localhost:8080
Content-Type: application/json
Cache-Control: no-cache
Postman-Token: b6cb7987-739e-2b8c-d25a-cbf6b27dcd86
