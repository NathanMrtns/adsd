#Python Simple Server and Robot Client - ADSD
Simple python server and a robot client created for ADSD(AVALIAÇÃO DE DESEMPENHO DE SISTEMAS DISCRETOS) course at UFCG.

## Usage

This simple app returns the following stats about the server:
 - Command [POST(write) - GET(read)]
 - Server response time
 - DB response time
 - CPU usage %

Server and Robot Behavior:
 - Server just receives and respond the requests
 - This robot's behavior depends of the number of iterations, there are 2 options:
     - Requests are sent at 10 requests/minute
     - Requests are sent at 250 requests/minute
