# NumberGeneratorSol
Qns:-
Write a spring boot application that generates a sequence of numbers in the decreasing order till 0. Simulate that the function to generate a  number takes a random time – say between 10 to 30 seconds .<br />
Steps:-<br />
Run as a spring boot application<br />
Postman Request Bodies:-<br />
1.<br />
POST /api/generate HTTP/1.1<br />
Host: localhost:8080<br />
Content-Type: application/json<br />
Cache-Control: no-cache<br />
Postman-Token: e7d61881-5ae3-80d6-6cfa-de43e149ae8f<br />
<br />
{"goal":"10","step":"2"}<br />
2.<br />
POST /api/bulkGenerate HTTP/1.1<br />
Host: localhost:8080<br />
Content-Type: application/json<br />
Cache-Control: no-cache<br />
Postman-Token: 4fe85467-cd0a-4fbb-8bcd-eed074815d0d<br />
<br />
[{"goal":"10","step":"2"},<br />
{"goal":"100","step":"3"}]<br />
3.<br />
GET /api/task/{uuid}?action=number HTTP/1.1<br />
Host: localhost:8080<br />
Content-Type: application/json<br />
Cache-Control: no-cache<br />
Postman-Token: 15c003cc-068c-4d6a-fbc2-9a3834286a06<br />
4.<br />
GET /api/task/{uuid}/status HTTP/1.1<br />
Host: localhost:8080<br />
Content-Type: application/json<br />
Cache-Control: no-cache<br />
Postman-Token: b6cb7987-739e-2b8c-d25a-cbf6b27dcd86<br />
