<!--lint disable double-link-->

# Awesome FastAPI [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to FastAPI.

[FastAPI](https://fastapi.tiangolo.com/) is a modern, high-performance, batteries-included Python web framework that's perfect for building RESTful APIs.

## Contents

- [Third-Party Extensions](#third-party-extensions)
  - [Admin](#admin)
  - [Auth](#auth)
  - [Databases](#databases)
  - [Developer Tools](#developer-tools)
  - [Email](#email)
  - [Utils](#utils)
- [Resources](#resources)
  - [Official Resources](#official-resources)
  - [Podcasts](#podcasts)
  - [Articles](#articles)
  - [Tutorials](#tutorials)
  - [Talks](#talks)
  - [Videos](#videos)
  - [Courses](#courses)
- [Hosting](#hosting)
  - [PaaS](#paas)
  - [IaaS](#iaas)
  - [Serverless](#serverless)
- [Projects](#projects)
  - [Boilerplate](#boilerplate)
  - [Open Source Projects](#open-source-projects)

## Third-Party Extensions

### Admin

- [FastAPI Admin](https://github.com/long2ice/fastapi-admin) - Functional admin panel that provides a user interface for performing CRUD operations on your data.

### Auth

- [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) - Pluggable auth that supports the OAuth2 Password Flow with JWT access and refresh tokens.
- [FastAPI Login](https://github.com/MushroomMaula/fastapi_login) - Account management and authentication (based on [Flask-Login](https://github.com/maxcountryman/flask-login)).
- [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) - JWT auth (based on [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended)).
- [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) - Row-level permissions.
- [FastAPI Security](https://github.com/jmagnusson/fastapi-security) - Implements authentication and authorization as dependencies in FastAPI.
- [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) - Out-of-the-box API key security manageable through path operations.
- [FastAPI Users](https://github.com/frankie567/fastapi-users) - Account management, authentication, authorization.

### Databases

#### ORMs

- [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) - Simple integration between FastAPI and [SQLAlchemy](https://www.sqlalchemy.org/).
- [Tortoise ORM](https://tortoise-orm.readthedocs.io/en/latest/index.html) - An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django.
  - [FastAPI Example](https://tortoise-orm.readthedocs.io/en/latest/examples/fastapi.html) - An example of the Tortoise-ORM FastAPI integration.
  - [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
  - [Aerich](https://tortoise-orm.readthedocs.io/en/latest/migration.html) - Tortoise ORM migrations tools.
- [GINO](https://github.com/python-gino/gino) - A lightweight asynchronous ORM built on top of SQLAlchemy core for Python asyncio.
  - [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
- [ORM](https://github.com/encode/orm) - An async ORM.
- [ormar](https://collerek.github.io/ormar/fastapi/) - An async mini ORM for Python.


#### Query Builders

- [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - A wrapper around [asyncpg](https://github.com/MagicStack/asyncpg) for use with [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).
- [Databases](https://github.com/encode/databases) - Async SQL query builder that works on top of the [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) expression language.

#### ODMs

- [MongoEngine](http://mongoengine.org/) - A Document-Object Mapper (think ORM, but for document databases) for working with MongoDB from Python.
- [Motor](https://motor.readthedocs.io/) - Asynchronous Python driver for MongoDB.
- [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM integrated with [Pydantic](https://pydantic-docs.helpmanual.io/). 

#### Other Tools

- [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) - Convert SQLAlchemy models to [Pydantic](https://pydantic-docs.helpmanual.io/) models.
- [FastAPI-CamelCase](https://ahmednafies.github.io/fastapi_camelcase/) - CamelCase JSON support for FastAPI utilizing [Pydantic](https://pydantic-docs.helpmanual.io/).
  - [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - Accompanying blog post from the author of the extension.

### Developer Tools

- [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) - Generate a mypy- and IDE-friendly API client from an OpenAPI spec.
- [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) - API versioning.
- [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) - Run your Jupyter notebooks as RESTful API endpoints.
- [Manage FastAPI](https://github.com/ycd/manage-fastapi) - CLI tool for generating and managing FastAPI projects.
- [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) - Automatic [MessagePack](https://msgpack.org/) content negotiation.

### Email

- [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) - Lightweight mail system for sending emails and attachments (individual and bulk).

### Utils

- [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) - A simple lightweight cache system.
- [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) - Opinionated set of utilities: pagination, auth middleware, permissions, custom exception handlers, MongoDB support, and Opentracing middleware.
- [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) - Redis and Scheduler plugins.
- [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) - Generator for creating API services.
- [FastAPI Utilities](https://github.com/dmontagu/fastapi-utils) - Reusable utilities: class-based views, response inferring router, periodic tasks, timing middleware, SQLAlchemy session, OpenAPI spec simplification.
- [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) - Starlette middleware for Prerender.
- [SlowApi](https://github.com/laurents/slowapi) - Rate limiter (based on [Flask-Limiter](https://flask-limiter.readthedocs.io)).
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) - Prometheus integration for FastAPI and Starlette.
- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) - One more prometheus integration for FastAPI and Starlette.
- [Starlette-OpenTracing](https://github.com/acidjunk/starlette-opentracing) - Opentracing support for Starlette and FastApi.

## Resources

### Official Resources

- [Documentation](https://fastapi.tiangolo.com/) - Comprehensive documentation.
- [Tutorial](https://fastapi.tiangolo.com/tutorial/) - Official tutorial showing you how to use FastAPI with most of its features, step by step.
- [Source Code](https://github.com/tiangolo/fastapi) - Hosted on GitHub.
- [Gitter Chat](https://gitter.im/tiangolo/fastapi) - Chat with other FastAPI users.

### Podcasts

- [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - In this episode of [Podcast Init](https://www.pythonpodcast.com/), the create of FastAPI, [Sebastián Ramirez](https://tiangolo.com/), shares his motivations for building FastAPI and how it works under the hood.
- [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) - Nice overview of the project.

### Articles

- [Why we switched from Flask to FastAPI for production machine learning](https://towardsdatascience.com/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) - In-depth look at why you may want to move from Flask to FastAPI.

### Tutorials

- [Demystifying Authentication with FastAPI and a Frontend](https://www.strio.co/blog/authentication-guide-with-fastapi/) - Add token-based authentication.
- [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - Develop and test an asynchronous API with FastAPI, Postgres, Pytest, and Docker using Test-Driven Development.
- [Deploying Iris Classifications with FastAPI and Docker](https://towardsdatascience.com/deploying-iris-classifications-with-fastapi-and-docker-7c9b83fdec3a) - Dockerizing a FastAPI application.
- [FastAPI for Flask Users](https://amitness.com/2020/06/fastapi-vs-flask/) - Learn FastAPI with a side-by-side code comparison to Flask.
- [How to deploy your ConvNet classifier with Keras and FastAPI](https://www.machinecurve.com/index.php/2020/03/19/tutorial-how-to-deploy-your-convnet-classifier-with-keras-and-fastapi/) - Deploy a machine learning model via a web-based API.
- [Introduction to the FastAPI Python Framework](https://www.errietta.me/blog/python-fastapi-intro/) - Quick intro to FastAPI.
- [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) - Comparison of Flask vs FastAPI.
- [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/blog/2020/07/real-time-data-streaming-using-fastapi-and-websockets/) - Learn how to stream data from FastAPI directly into a real-time chart.
- [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) - Use FastAPI to quickly and easily deploy and serve machine learning models in Python as a RESTful API.

### Talks

- [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) - From the talk by Sebastian Ramirez you will learn how to easily build a production-ready web (JSON) API for your ML models with FastAPI, including best practices by default.
- [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) - This talk shows how to build a simple REST API for a database from the ground up using FastAPI.

### Videos

- [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) - A you build a web-based stock screener with FastAPI, you'll be introduced to many of FastAPI's features, including pydantic models, dependency injection, background tasks, and SQLAlchemy integration.
- [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) - Use FastAPI to build a web application programming interface (RESTful API).
- [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) - See how to do numeric validations with FastAPI.
- [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) - Build a machine learning API with FastAPI.

### Courses

- [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) - Learn how to build, test, and deploy a text summarization microservice with Python, FastAPI, and Docker.

## Hosting

### PaaS

(Platforms-as-a-Service)

- [Heroku](https://www.heroku.com/) ([Step-by-step tutorial](https://www.tutlinks.com/create-and-deploy-fastapi-app-to-heroku/), [ML model on Heroku tutorial](https://testdriven.io/blog/fastapi-machine-learning/))
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [Google App Engine](https://cloud.google.com/appengine/)
- [Microsoft Azure App Service](https://azure.microsoft.com/services/app-service/)
- [Deta](https://www.deta.sh/) ([example](https://dev.to/athulcajay/fastapi-deta-ni5))

### IaaS

(Infrastructure-as-a-Service)

- [AWS EC2](https://aws.amazon.com/ec2/)
- [Google Compute Engine](https://cloud.google.com/compute/)
- [Digital Ocean](https://www.digitalocean.com/)
- [Linode](https://www.linode.com/)

### Serverless

Frameworks:

- [Chalice](https://github.com/aws/chalice)
- [Mangum](https://mangum.io/) - Adapter for running ASGI applications with AWS Lambda and API Gateway.
- [Vercel](https://vercel.com/) - (formerly Zeit) ([example](https://github.com/paul121/fastapi-zeit-now)).
- [Zappa](https://github.com/Miserlou/Zappa)

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/) ([tutorial](https://iwpnd.pw/articles/2020-01/deploy-fastapi-to-aws-lambda), [code](https://github.com/iwpnd/fastapi-aws-lambda-example))
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)
- [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthcor/cloudrun-fastapi))

## Projects

### Boilerplate

- [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) - Full stack, modern web application generator, which includes FastAPI, PostgreSQL, Docker, Celery, Vue frontend, automatic HTTPS and more (developed by the creator of FastAPI, [Sebastián Ramírez](https://github.com/tiangolo)).
- [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) - Powerful but simple template for web APIs w/ FastAPI (as web framework) and Tortoise-ORM (for working via database without headache).
- [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) - Skeleton app to serve machine learning models production-ready.
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) - Quick deployments of spaCy models with FastAPI.
- [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) - Cookiecutter template for FastAPI projects using: Machine Learning, Poetry, Azure Pipelines and pytest.
- [openapi-python-client](https://github.com/triaxtec/openapi-python-client) - Generate modern FastAPI Python clients (via FastAPI) from OpenAPI.
- [Pywork](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) generator to scaffold a FastAPI app.
- [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - Docker image with Uvicorn managed by Gunicorn for high-performance FastAPI web applications in Python 3.7 and 3.6 with performance auto-tuning.
- [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn) - Tempate for a high-performance async REST API, in Python. FastAPI + GINO + Arq + Uvicorn (w/ Redis and PostgreSQL).
- [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) - Full stack cookiecutter boilerplate using FastAPI, TypeScript, Docker, PostgreSQL, and React.
- [FastAPI Nano](https://github.com/rednafi/fastapi-nano) - Simple FastAPI template with factory pattern architecture.

### Open Source Projects

- [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) - Organized list of projects that use FastAPI.
- [Bitcart](https://github.com/bitcartcc/bitcart) - Platform for merchants, users and developers which offers easy setup and use.
- [Dispatch](https://github.com/Netflix/dispatch) - Manage security incidents.
- FastAPI CRUD Example:
  - [Async flavor](https://github.com/testdrivenio/fastapi-crud-async)
  - [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync)
- [FastAPI Websocket Broadcast](https://github.com/cthwaite/fastapi-websocket-broadcast) - Websocket 'broadcast' demo.
- [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) - Minimal example utilizing FastAPI and Celery with RabbitMQ for task queue, Redis for Celery backend, and Flower for monitoring the Celery tasks.
- [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) - JSON-RPC server based on FastAPI.
- [Mailer](https://github.com/rclement/mailer) - Dead-simple mailer micro-service for static websites.
- [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app)
- [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app)
- [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) - A simple Redis Streams backed chat app using Websockets, Asyncio and FastAPI/Starlette.
- [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) - Generate your personal 8-bit avatars using Cellular Automata.
- [Slackers](https://github.com/uhavin/slackers) - Slack webhooks API.
- [TermPair](https://github.com/cs01/termpair) - View and control terminals from your browser with end-to-end encryption.
- [Universities](https://github.com/ycd/universities) -  API service for obtaining information about +9600 universities worldwide.
---

<br>

> **NOTE**: This project is powered by **[TestDriven.io](https://testdriven.io/)**. Please support this open source project by purchasing our FastAPI course: [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/).
