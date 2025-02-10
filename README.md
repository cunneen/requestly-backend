## Requestly Backend (Apache-Licensed fork)

Forked for posterity.

This is a fork of [requestly-backend][1], with this (forked) repository's `main` branch diverging at the parent of commit [`0585a40`][2] where [the license was changed from Apache to AGPL][2].

**Note: I haven't yet determined the prerequisites or required `.env` file contents to run this. PR's are welcome.**

[1]:https://github.com/requestly/requestly-backend
[2]:https://github.com/requestly/requestly-backend/commit/0585a40ebdac75bc0fd6ed1d486315fdfe05f3ab

### Original Instructions

To test locally, create the required `.env` files and run

`docker compose --env-file ./app.env up --build`
