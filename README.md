# Udacity FSND - HTTP and Web Servers

* Welcome to our course on HTTP and Web Servers! In this course, you'll learn how web servers work. You'll write web services in Python, and you'll also write code that accesses services out on the web

## Instructions
* Install `Git Bash`
* Install python3 - Run Python 3 from terminal `C:/Users/Christiaan/AppData/Local/Programs/Python/Python36-32/python`

#### Python 3.6 .exe Location
* `C:/Users/Christiaan/AppData/Local/Programs/Python/Python36-32`

* Install `Nmap` and `ncat`(https://nmap.org/dist/nmap-7.30-setup.exe).

====================================

### Exercise: Running your first web server
* The Python http.server module can run a built-in web server on your computer.
Open up a terminal; `cd` to a directory that has some files in it — maybe a directory containing some text files, HTML files, or images — then run `python3 -m http.server 8000` in your terminal.

```python
C:/Users/Christiaan/AppData/Local/Programs/Python/Python36-32/python -m http.server 8000
```
* Now try accessing http://localhost:8000/ from your browser.
* In the terminal, you can use the `host` or `nslookup` program to look up hostnames in DNS. 
`nslookup www.google.com`

### Exercise: Send a request by hand
* While running web server, on a terminal use `ncat 127.0.0.1 8000` to connect your terminal to the demo server.
Then type these two lines:
```
GET / HTTP/1.1
Host: localhost
```