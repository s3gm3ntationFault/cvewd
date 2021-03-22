# cvewd

Welcome to CVE WatchDog.

The goal of this project is to develop a tool to automaticaly diagnose our machines.

There will be three base components:

* Package detector:
    Get all the packages installed on the system and its version.

* CVE Fetcher:
    Retrieve data from CVE data feeds on demand and periodically.

* CVE Analyser:
    Cross package detector data with CVE fetcher.

On the first versions of the project the CVE Analyser will only alert the
system administrator when a vulnerability is found. On further versions
the system will attempt to automatically hint with a solution if any or even
attemp to fix it automatically.
