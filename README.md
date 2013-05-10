Nagios plugin to check web page load time, response size and HTTP status

    $ /usr/local/nagios/libexec/check_pageresponse http://github.com
    OK - 200 OK 10.4KB in .745s | contentlength=10.4 loadtime=.745

* Header redirects are followed

* Max timeout is 5 seconds

* A 2.5 second load time will generate a WARNING

* Non 20x and 30x HTTP codes will generate a WARNING
