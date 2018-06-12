# Quickstart Google Calendar Auth

This is based upon [the google web quickstart](https://developers.google.com/calendar/quickstart/js)
and [signin server side flow guide](https://developers.google.com/identity/sign-in/web/server-side-flow).
The trick is to call requestOfflineAccess() instead of signin().
Clear documentation was hard to find on the outset.

# To run

## Add credentials

download credentials from the Google API Project Dashboard as in
[the google web quickstart](https://developers.google.com/calendar/quickstart/js),
and remane `config.json` in this project.  See the config.example.json as an example.

This is just a demo so we'll use an easy server.
Make sure you have python installed on your machine and from the project root run (python 2):

    python -m SimpleHTTPServer 8000

Or for python 3:

    python -m http.server 8000


