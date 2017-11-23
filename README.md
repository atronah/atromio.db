atromio Database
=================

Project to development database structure for 
[atromio](https://github.com/atronah/atromio).



Why separately?
---------------

The main reason for the separation app and database repositories is the need to always have access to all dB migrations,
even if app repo was rolled back.