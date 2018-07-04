# corsproxy
Proxies requests and adds CORS headers.

````
Usage: corsproxy [OPTIONS]

Options:
  -a, --addr string                Address to listen on (default ":8000")
  -b, --header-blacklist strings   Headers to remove from the request and response
  -h, --help                       Show this message
  -r, --max-redirects int          Maximum number of redirects to follow (default 10)
  -t, --timeout int                Request timeout (default 15)

Run the server and go to it in a web browser for API documentation.
````