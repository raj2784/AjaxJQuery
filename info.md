    Value State Description

    0 UNSENT  Client has been created. open() not called yet.

    1 OPENED  open() has been called.

    2 HEADERS_RECEIVED  send() has been called, and headers and status are available.

    3 LOADING Downloading; responseText holds partial data.

    4 DONE  The operation is complete.

    Ref for above: https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState

    HTTP response status codes

    HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses    	   are grouped in five  classes:

    Informational responses (100 – 199)

    Successful responses (200 – 299)

    Redirection messages (300 – 399)

    Client error responses (400 – 499)

    Server error responses (500 – 599)

    Ref for above : https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
