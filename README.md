## _About / Sobre _
[Linkedin Profile](https://www.linkedin.com/in/juan-pablo-perez-a862bb54/)

## _Papers & How-to _ > [[papers]]


## _Proyectos _


* Acceso a Proyectos Activos en Github [[proyectos]]
* Acceso a Forks Activos [[forks]]





[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

devops_tools es un compendio de herramientas / scripting/ proyectos reunidos para ayudar a la tarea
del DevOps /DevSecOps diariamente.

- Multiplataforma
- Automática
- ✨ Magica ✨

## Features - Características

- Fácil e intuitiva a la hora de agregar herrramientas nuevas
- Secuencial en el orden de instalaciones
- Multiplataforma de aplicación generalizada.

> testing new current features
> Windows / Linux OS 


## Installation

devops_tools requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and Dev Dependencies and start the server.

```sh
cd devops_tools
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Devops_tools is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin           | README                                    |
| ---------------- | ----------------------------------------- |
| Dropbox          | [plugins/dropbox/README.md][PlDb]         |
| GitHub           | [plugins/github/README.md][PlGh]          |
| Google Drive     | [plugins/googledrive/README.md][PlGd]     |
| OneDrive         | [plugins/onedrive/README.md][PlOd]        |
| Medium           | [plugins/medium/README.md][PlMe]          |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Devops_tools uses Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

## Docker

devops_tools is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd devops_tools
docker build -t <youruser>/devops_tools:${package.json.version} .
```

This will create the devops_tools image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of devops_tools.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=devops_tools <youruser>/devops_tools:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [git-repo-url]: <https://github.com/pro-public/devops_tools.git>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>


