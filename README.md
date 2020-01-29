# Rendertron + Docker

To get started:

* Clone repo
* Build image - `docker build -t rendertron:<version>`
* Create container - `docker create -p 3000:3000 rendertron:<version>`
* Run container - `docker start <container name> -a`

Render pages using the following URL `/render/<url to render>`
