<div align="center">
  <a href="https://github.com/sindresorhus/awesome#readme"><img src="https://awesome.re/badge-flat.svg" /></a>
  <a href="https://travis-ci.org/mjhea0/awesome-fastapi"><img src="https://api.travis-ci.org/mjhea0/awesome-fastapi.svg?branch=master" alt="Build Status" /></a></p>
  <a href="https://twitter.com/intent/tweet?text=Awesome%20FastAPI%20-%20a%20curated%20list%20of%20awesome%20things%20related%20to%20FastAPI%20https%3A//github.com/mjhea0/awesome-fastapi%20%23webdev">Share on Twitter</a>
  <br /><br />
  <img width="400" src="fastapi-logo.png" alt="FastAPI logo">
</div>

# Awesome FastAPI

> A curated list of awesome things related to [FastAPI](https://fastapi.tiangolo.com/).

## Contents

- [Third-Party Extensions](#third-party-extensions)
  - [Admin](#admin)
  - [Auth](#auth)
  - [Databases](#databases)
  - [Developer Tools](#developer-tools)
  - [Email](#email)
  - [Utils](#utils)
- [Resources](#resources)
  - [Official](#official-resources)
  - [External](#external-resources)
  - [Community](#community)
  - [Conferences](#conferences)
    - [Conference Videos from PyVideo.org](#conference-videos-from-pyvideoorg)
  - [Meetups](#meetups)
  - [Podcasts](#podcasts)
  - [Tutorials](#tutorials)
  - [Courses](#courses)
  - [Books](#books)
  - [Videos](#videos)
- [Hosting](#hosting)
  - [PaaS](#paas)
  - [IaaS](#iaas)
  - [Serverless](#serverless)
- [Projects](#Projects)
  - [Boilerplate](#boilerplate)
  - [Open Source Projects](#open-source-projects)

## Third-Party Extensions

### Admin

- [FastAPI Admin](https://github.com/long2ice/fastapi-admin) - Functional admin panel that provides a user interface for performing CRUD operations on your data

### Auth

- [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) - Pluggable auth that supports the OAuth2 Password Flow with JWT access and refresh tokens
- [FastAPI-Login](https://flask-login.readthedocs.io/) - Account management and authentication (based on [Flask-Login](https://github.com/maxcountryman/flask-login))
- [FastAPI-Permissions](https://github.com/holgi/fastapi-permissions) - Row-level permissions
- [FastAPI Users](https://github.com/frankie567/fastapi-users) - Account management, authentication, authorization

### Databases

#### ORMs

- [FastAPI-SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) - Simple integration between FastAPI and [SQLAlchemy](https://www.sqlalchemy.org/)
- [Tortoise ORM](https://tortoise.github.io/)
    - [FastAPI Example](https://tortoise-orm.readthedocs.io/en/latest/examples/fastapi.html)
    - [Tutorial: Setting up Tortoise ORM with FastAPI](https://robwagner.dev/tortoise-fastapi-setup/)
- [GINO](https://github.com/python-gino/gino) a lightweight asynchronous ORM built on top of SQLAlchemy core for Python asyncio
    - [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
- [ORM](https://github.com/encode/orm) - An async ORM

#### Query Builders

- [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - A wrapper around [asyncpg](https://github.com/MagicStack/asyncpg) for use with [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/)
- [Databases](https://github.com/encode/databases) -  Async SQL query builder that works on top of the [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) expression language

### Developer Tools

- [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) - Generate a mypy- and IDE-friendly API client from an OpenAPI spec
- [FastAPI-Versioning](https://github.com/DeanWay/fastapi-versioning) - API versioning
- [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) - run your Jupyter notebooks as RESTful API endpoints
- [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) - automatic [MessagePack](https://msgpack.org/) content negotiation

### Email

- [FastAPI-Mail](https://github.com/sabuhish/fastapi-mail) - lightweight mail system for sending emails and attachments (individual and bulk)

### Utils

- [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) - Opinionated set of utilities: pagination, auth middleware, permissions, custom exception handlers, MongoDB support, and Opentracing middleware
- [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) - Redis and Scheduler plugins
- [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) - Generator for creating API services
- [FastAPI Utilities](https://github.com/dmontagu/fastapi-utils) - Reusable utilities: class-based views, response inferring router, periodic tasks, timing middleware, SQLAlchemy session, OpenAPI spec simplification
- [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) - Starlette middleware for Prerender
- [SlowApi](https://flask-limiter.readthedocs.io) - Rate limiter (based on [Flask-Limiter](https://flask-limiter.readthedocs.io))

## Resources

### Official Resources

- [Documentation](https://fastapi.tiangolo.com/) - Comprehensive documentation
- [Tutorial](https://fastapi.tiangolo.com/tutorial/)
- [Source Code](https://github.com/tiangolo/fastapi) - Hosted on Github
- [Gitter Chat](https://gitter.im/tiangolo/fastapi)

### Podcasts

- [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - In this episode of [Podcast Init](https://www.pythonpodcast.com/), the create of FastAPI, [Sebastián Ramirez](https://tiangolo.com/), shares his motivations for building FastAPI and how it works under the hood
- [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855)

### Tutorials

- [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/)
- [Deploying Iris Classifications with FastAPI and Docker](https://towardsdatascience.com/deploying-iris-classifications-with-fastapi-and-docker-7c9b83fdec3a)
- [How to deploy your ConvNet classifier with Keras and FastAPI](https://www.machinecurve.com/index.php/2020/03/19/tutorial-how-to-deploy-your-convnet-classifier-with-keras-and-fastapi/)
- [Introduction to the FastAPI Python Framework](https://www.errietta.me/blog/python-fastapi-intro/)
- [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/)
- [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459)

### Talks

- [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8)
- [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA)

### Videos

- [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk)
- [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA)
- [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8)

## Hosting

### PaaS

(Platforms-as-a-Service)

- [Heroku](https://www.heroku.com/)
- [PythonAnywhere](https://www.pythonanywhere.com/details/flask_hosting)
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [Google App Engine](https://cloud.google.com/appengine/)
- [Microsoft Azure App Service](https://azure.microsoft.com/services/app-service/)

### IaaS

(Infrastructure-as-a-Service)

- [AWS EC2](https://aws.amazon.com/ec2/)
- [Google Compute Engine](https://cloud.google.com/compute/)
- [Digital Ocean](https://www.digitalocean.com/)
- [Linode](https://www.linode.com/)

### Serverless

Frameworks:

- [Zappa](https://github.com/Miserlou/Zappa)
- [Chalice](https://github.com/aws/chalice)
- [Vercel](https://vercel.com/) (formerly Zeit) ([example](https://github.com/paul121/fastapi-zeit-now))

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/) ([tutorial](https://iwpnd.pw/articles/2020-01/deploy-fastapi-to-aws-lambda), [code](https://github.com/iwpnd/fastapi-aws-lambda-example))
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)
- [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthcor/cloudrun-fastapi))

## Projects

### Boilerplate

- [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) - Full stack, modern web application generator, which includes FastAPI, PostgreSQL, Docker, Celery, Vue frontend, automatic HTTPS and more (developed by the creator of FastAPI, [Sebastián Ramírez](https://github.com/tiangolo))
- [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise)
- [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) - Skeleton app to serve machine learning models production-ready
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) - Quick deployments of spaCy models with FastAPI
- [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi)
- [openapi-python-client](https://github.com/triaxtec/openapi-python-client) - Generate modern FastAPI Python clients (via FastAPI) from OpenAPI
- [Pywork](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) generator to scaffold a FastAPI app
- [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - Docker image with Uvicorn managed by Gunicorn for high-performance FastAPI web applications in Python 3.7 and 3.6 with performance auto-tuning

### Open Source Projects

- [Bitcart](https://github.com/MrNaif2018/bitcart)
- FastAPI CRUD Example:
  - [Async flavor](https://github.com/testdrivenio/fastapi-crud-async)
  - [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync)
- [FastAPI Websocket Broadcast](https://github.com/cthwaite/fastapi-websocket-broadcast)
- [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery)
- [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc)
- [Mailer](https://github.com/rclement/mailer) - Dead-simple mailer micro-service for static websites
- [RealWorld Example App](https://github.com/nsidnev/fastapi-realworld-example-app)
- [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat)
- [Slackers](https://github.com/uhavin/slackers) - Slack webhooks API
- [TermPair](https://github.com/cs01/termpair)

---

<br>

> **NOTE**: This project is powered by **[TestDriven.io](https://testdriven.io/)**. Please support this open source project by purchasing one of our courses.
