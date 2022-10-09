# Virtual Miniatures Painting Center

VMPC (Virtual Miniatures Painting Center) is an application intended for people who paint miniatures and more.
It contains a list of products (paints) from various manufacturers and allows you to find replacements.

# Quick start

As long as the application is in the preparation and development phase, you can use it locally on your computer. In the future, the application will be launched in the public domain.

## Requirements

To run the application, you should have the following components on your system:

- docker
- docker-compose

## Preparation

1. Download source code:
   - this repository [[click]](https://github.com/virtual-miniatures-painting-center/contenerized-structure/archive/refs/heads/master.zip)
   - api's repository [[click]](https://github.com/virtual-miniatures-painting-center/api/archive/refs/heads/master.zip),
   - frontend's repository [[click]](https://github.com/virtual-miniatures-painting-center/frontend/archive/refs/heads/master.zip).
2. Extract downloaded archives.
3. Rename '.env.template' file to '.env' inside each of downloaded repositories.
   - _For api and frontend they are in the docker directory._
   - _You can edit variables values if you want._
4. Build images described in `docker-compose.yml` (this repository).

## Run

1. Run containers described in `docker-compose.yml` (this repository).
2. Navigate to [localhost](http://localhost) in your web browser.
