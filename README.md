# flask-tutorial-asr2021

## Flask 
[Flask](https://flask.palletsprojects.com/en/2.0.x/) is web application framework written in Python. It gives all the functionallity for implemeting a web applications. We can develop Application Programming Interface (API) for ML using the Flask. And we can do inference through browser.Your users will need to access your data in real time, such as for display on another website or as part of an application.

## Related terminology
- HTTP (Hypertext Transfer Protocol) is the protocol for commnuicating with the API. Two important methods used to interact with the API are GET, which pulls data from a server, and POST, which pushes new data to a server.
- URL (Uniform Resource Locator) - An address for a resource on the web, such as https://programminghistorian.org/about. A URL consists of a protocol (http://), domain (programminghistorian.org), and optional path (/about). A URL describes the location of a specific resource, such as a web page.

## Installation
```python
python --version
pip --version
python3.x -m pip install flask
```

HTTP Methods
- Get
  - get data from server. to send data from the application to the user
- POST
  - create data. to receive data from a user
- PUT
- DELETE

Links: https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask
