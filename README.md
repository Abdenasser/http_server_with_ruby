# http server with ruby

First start the server by running `ruby tcp_server.rb`, and then start the client in a separate terminal tab or window by running `ruby tcp_client.rb` to receive the server’s message.


### The http server (http_server.rb)

the web server looks mostly the same as the TCP server we created earlier. The general idea is the same, we’re just using the HTTP protocol to format our message. Also, because we’ll use a browser to send requests and parse responses, we won’t have to implement a client this time.

start the server by running  `ruby http_server.rb`

then open http://localhost:5678 in your browser.
