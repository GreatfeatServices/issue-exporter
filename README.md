# issue-exported

This is strongly based on https://gist.github.com/unbracketed/3380407;
thanks to @unbracketed and the various commenters on the page.

Make sure you have `requests` and `csv` installed via pip then run it:
`python issue-exporter.py`

Exports Issues from a specified repository to a CSV file
Uses basic authentication (Github username + password) or token to retrieve Issues
from a repository that username has access to. Supports Github API v3.
