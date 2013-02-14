A Server Logfile Parser with Error Reporting
=================================

A simple Bash script that you can run e.g. daily via Cron to grab the current access.log from your webserver, parse it and find HTTP error codes to report them.

The script can be run from any *NIX machine under your control, be it a monitoring or development server or even your own laptop. 

All you need is SSH authentication via keyfiles and standard tools like mail etc. The script itself is decently commented and should provide ample information on what you need to configure and how to run it.