# EX01 Developing a Simple Webserver
## Date:18/09/2025

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
~~~
<!DOCTYPE html>
<html>
<head>
  <title>TCP Protocol Explanation</title>
  <style>
    table {
      border-collapse: collapse;
      width: 80%;
      margin: 20px auto;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #333;
      padding: 10px;
      text-align: left;
    }
    th {
      background-color: #4CAF50;
      color: white;
    }
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    caption {
      font-size: 20px;
      margin: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <table>
    <caption>TCP Protocol Explanation</caption>
    <tr>
      <th>Feature</th>
      <th>Explanation</th>
    </tr>
    <tr>
      <td>Full Form</td>
      <td>Transmission Control Protocol</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Connection-oriented protocol</td>
    </tr>
    <tr>
      <td>Connection Setup</td>
      <td>Uses a 3-way handshake to establish a reliable connection before data transfer.</td>
    </tr>
    <tr>
      <td>Reliability</td>
      <td>Ensures reliable data delivery with error checking and retransmission of lost packets.</td>
    </tr>
    <tr>
      <td>Data Transfer</td>
      <td>Breaks data into segments, numbers them, and ensures they arrive in order.</td>
    </tr>
    <tr>
      <td>Flow Control</td>
      <td>Uses sliding window protocol to prevent sender from overwhelming receiver.</td>
    </tr>
    <tr>
      <td>Error Control</td>
      <td>Uses checksums to detect errors and acknowledgments (ACKs) for successful delivery.</td>
    </tr>
    <tr>
      <td>Applications</td>
      <td>Used in applications like HTTP, HTTPS, FTP, SMTP, and Telnet.</td>
    </tr>
    <tr>
      <td>Port Numbers</td>
      <td>Uses port numbers (e.g., HTTP – 80, HTTPS – 443, FTP – 21).</td>
    </tr>
  </table>

</body>
</html>
~~~
## OUTPUT:
<img width="1920" height="870" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/70155077-22f8-47e3-b0a5-3db083132bd7" />

<img width="1466" height="450" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/caae134c-c506-470e-ab5b-3bb9d222c18f" />

## RESULT:
The program for implementing simple webserver is executed successfully.

