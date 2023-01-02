# Developing a Simple Webserver

# AIM:

Name: KOUSALYA A 22008930

# DESIGN STEPS:

### Step 1:

HTML content creation is done

## Step 2:

Design of webserver workflow

## Step 3:

Implementation using Python code

## Step 4:

Serving the HTML pages.

## Step 5:

Testing the webserver

# PROGRAM:
```
class HelloHandler(BaseHTTPRequestHandler):
    def do_GET(self):
        self.send_response(200)
        self.send_header('Content_type','text/html; charset=utf-8')
        self.end_headers()
        self.wfile.write(content.encode())


    server_address = ('',80)
    httpd = HTTPServer(Server_address, HelloHandler)
    httpd.serve_forever()
    ```


# OUTPUT:

# RESULT:

