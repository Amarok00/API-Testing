# API-Testing
Run:

`$ (sudo) python3 httpd.py [host, positional argument (default - localhost)] [-p, --port (default: 8080)] [-r, --root (defaults to CWD)] [-w, --workers  (default: 3)] [-t, --timeout (default: 3.0)] [-l, --log (defaults to None)] [-v, --level , int from 0 to 40 (defaults to INFO)]`

* Running on port 80 may ask a super user privileges
* if a logfile provided with -l (--log), log messages would go into it instead of stdout

Test page:

<http://localhost/httptest/wikipedia_russia.html>

All tests of httptest.py completed successfully.
