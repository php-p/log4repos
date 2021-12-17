# log4repos
Github repositories that depend on log4j. 

Use-case:
Search your proxy history for connections to any of the repos, verify if on disk and log4j version. 

Search effectiveness:

Eg.1 - Edit list to get unique users, excluding repos and domain name. 

        - Pseudo Search Example: index=proxy desthost=github.com path=<lookup definition>* | table path

            - If results, drill down on the path to confirm repo

                - Check github if updated log4j included

E.g.2 - If capability to search on disk for files from source url, try this


