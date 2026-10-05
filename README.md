# Awesome Python

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated list of awesome Python frameworks, libraries, tools, and resources for building production-grade systems.

---

### 🌐 Web Frameworks

* [Django](https://www.djangoproject.com/) – high-level web framework that encourages rapid development and clean, pragmatic design.
* [Falcon](https://falconframework.org/) – minimalist WSGI/ASGI library for building high-performance APIs.
* [FastAPI](https://fastapi.tiangolo.com/) – modern, fast web framework for building APIs with Python type hints.
* [Flask](https://flask.palletsprojects.com/) – lightweight WSGI micro web framework.
* [Litestar](https://litestar.dev/) – performant, flexible ASGI framework with first-class OpenAPI support.
* [Starlette](https://www.starlette.io/) – lightweight ASGI framework/toolkit used as the foundation for FastAPI.
* [Tornado](https://www.tornadoweb.org/) – web framework and asynchronous networking library.

---

### 🔌 REST & GraphQL APIs

* [Ariadne](https://ariadnegraphql.org/) – schema-first GraphQL Python library.
* [Django REST Framework](https://www.django-rest-framework.org/) – powerful and flexible toolkit for building Web APIs on top of Django.
* [djangorestframework-simplejwt](https://django-rest-framework-simplejwt.readthedocs.io/) – JWT authentication plugin for Django REST Framework.
* [FastAPI](https://fastapi.tiangolo.com/) – automatic OpenAPI/JSON Schema generation with dependency injection.
* [graphene](https://graphene-python.org/) – GraphQL framework for Python.
* [Strawberry](https://strawberry.rocks/) – code-first GraphQL library using type annotations.

---

### ⚡ Async & Concurrency

* [aiofiles](https://github.com/Tinche/aiofiles) – async file support for asyncio.
* [aiohttp](https://docs.aiohttp.org/) – async HTTP client/server framework.
* [anyio](https://anyio.readthedocs.io/) – asynchronous networking and concurrency library working on top of asyncio or trio.
* [asyncio](https://docs.python.org/3/library/asyncio.html) – standard library asynchronous I/O framework.
* [asyncpg](https://github.com/MagicStack/asyncpg) – high-performance async PostgreSQL client library.
* [trio](https://trio.readthedocs.io/) – friendly Python library for async concurrency and I/O.
* [uvloop](https://github.com/MagicStack/uvloop) – ultra fast asyncio event loop built on libuv.

---

### 📊 Data Science & Analytics

* [Arrow](https://arrow.apache.org/docs/python/) – cross-language development platform for in-memory data.
* [Dask](https://dask.org/) – parallel computing library that scales pandas, NumPy, and scikit-learn.
* [DuckDB](https://duckdb.org/docs/api/python/overview) – in-process analytical database with Python API.
* [NumPy](https://numpy.org/) – fundamental package for scientific computing.
* [pandas](https://pandas.pydata.org/) – powerful data structures for data analysis and manipulation.
* [Polars](https://pola.rs/) – lightning-fast DataFrame library written in Rust.
* [SciPy](https://scipy.org/) – fundamental algorithms for scientific computing.
* [Vaex](https://vaex.io/) – out-of-core DataFrames for big data.

---

### 🤖 Machine Learning & AI

* [CatBoost](https://catboost.ai/) – fast, scalable gradient boosting with native categorical features support.
* [Keras](https://keras.io/) – high-level neural networks API.
* [LightGBM](https://lightgbm.readthedocs.io/) – fast, distributed, high-performance gradient boosting framework.
* [ONNX Runtime](https://onnxruntime.ai/) – cross-platform ML model inferencing accelerator.
* [PyTorch](https://pytorch.org/) – open source machine learning framework.
* [scikit-learn](https://scikit-learn.org/) – simple and efficient tools for predictive data analysis.
* [TensorFlow](https://www.tensorflow.org/) – end-to-end open source ML platform.
* [Transformers](https://huggingface.co/docs/transformers/) – state-of-the-art ML for PyTorch, TensorFlow, and JAX.
* [XGBoost](https://xgboost.readthedocs.io/) – scalable and flexible gradient boosting.

---

### 🧠 LLM & GenAI Integration

* [anthropic](https://github.com/anthropics/anthropic-sdk-python) – official Python SDK for the Anthropic API.
* [Haystack](https://haystack.deepset.ai/) – end-to-end NLP framework for building production-ready AI pipelines.
* [Instructor](https://python.useinstructor.com/) – structured outputs from LLMs using Pydantic.
* [LangChain](https://python.langchain.com/) – framework for developing applications powered by language models.
* [LlamaIndex](https://www.llamaindex.ai/) – data framework for LLM-based applications.
* [Mirascope](https://mirascope.com/) – library for building LLM-powered applications.
* [openai](https://github.com/openai/openai-python) – official Python SDK for the OpenAI API.
* [Outlines](https://outlines-dev.github.io/outlines/) – guided text generation with LLMs.

---

### 🗄️ Databases & ORMs

* [Alembic](https://alembic.sqlalchemy.org/) – database migration tool for SQLAlchemy.
* [asyncpg](https://github.com/MagicStack/asyncpg) – high-performance async PostgreSQL client.
* [Beanie](https://beanie-odm.dev/) – async Python ODM for MongoDB.
* [motor](https://motor.readthedocs.io/) – async Python driver for MongoDB.
* [Peewee](http://docs.peewee-orm.com/) – small, expressive ORM.
* [psycopg](https://www.psycopg.org/) – PostgreSQL adapter for Python.
* [redis-py](https://github.com/redis/redis-py) – Python client for Redis.
* [SQLAlchemy](https://www.sqlalchemy.org/) – Python SQL toolkit and ORM.
* [SQLModel](https://sqlmodel.tiangolo.com/) – library for interacting with SQL databases using Python objects and Pydantic.
* [Tortoise ORM](https://tortoise.github.io/) – easy-to-use asyncio ORM for Python.

---

### 🚀 Caching

* [aiocache](https://aiocache.readthedocs.io/) – caching library with multiple backends for asyncio.
* [cachetools](https://cachetools.readthedocs.io/) – extensible memoizing collections and decorators.
* [diskcache](https://grantjenks.com/docs/diskcache/) – disk and file-backed cache library.
* [dogpile.cache](https://dogpilecache.sqlalchemy.org/) – caching front-end with dogpile locking.
* [redis-py](https://github.com/redis/redis-py) – Python client for Redis with full-featured caching support.

---

### 📨 Message Queues & Streaming

* [aio-pika](https://aio-pika.readthedocs.io/) – async AMQP framework built on top of aiormq.
* [aiormq](https://github.com/mosquito/aiormq) – pure Python asyncio AMQP client library.
* [Celery](https://docs.celeryq.dev/) – distributed task queue.
* [confluent-kafka](https://docs.confluent.io/kafka-clients/python/current/overview.html) – Confluent's Apache Kafka client for Python.
* [dramatiq](https://dramatiq.io/) – fast and reliable background task processing library.
* [kafka-python](https://kafka-python.readthedocs.io/) – Python client for Apache Kafka.
* [RQ](https://python-rq.org/) – simple job queues for Python.

---

### 💻 CLI Tools

* [Click](https://click.palletsprojects.com/) – composable command line interface toolkit.
* [docopt](http://docopt.org/) – Pythonic command-line interface description language.
* [prompt_toolkit](https://python-prompt-toolkit.readthedocs.io/) – library for building powerful interactive command lines.
* [Questionary](https://questionary.readthedocs.io/) – Python library for beautiful interactive prompts.
* [Rich](https://rich.readthedocs.io/) – library for rich text and beautiful formatting in the terminal.
* [Textual](https://textual.textualize.io/) – TUI (Text User Interface) framework.
* [tqdm](https://tqdm.github.io/) – fast, extensible progress bar.
* [Typer](https://typer.tiangolo.com/) – build great CLIs based on Python type hints.

---

### 🧪 Testing

* [Factory Boy](https://factoryboy.readthedocs.io/) – test fixtures replacement.
* [Faker](https://faker.readthedocs.io/) – generate fake data for testing.
* [freezegun](https://github.com/spulec/freezegun) – mock datetime for testing.
* [Hypothesis](https://hypothesis.readthedocs.io/) – property-based testing.
* [httpx](https://www.python-httpx.org/) – HTTP client with async support, used for API testing.
* [Locust](https://locust.io/) – load testing framework.
* [pytest](https://docs.pytest.org/) – full-featured testing framework.
* [pytest-asyncio](https://pytest-asyncio.readthedocs.io/) – async test support for pytest.
* [pytest-cov](https://pytest-cov.readthedocs.io/) – coverage reporting for pytest.
* [responses](https://github.com/getsentry/responses) – mock library for the `requests` library.
* [time-machine](https://github.com/adamchainz/time-machine) – travel through time in your tests.

---

### ✅ Code Quality & Type Checking

* [bandit](https://bandit.readthedocs.io/) – security linter for Python code.
* [Black](https://black.readthedocs.io/) – uncompromising Python code formatter.
* [flake8](https://flake8.pycqa.org/) – linting tool wrapping pycodestyle, pyflakes, and mccabe.
* [isort](https://pycqa.github.io/isort/) – sort Python imports.
* [mypy](https://mypy-lang.org/) – static type checker for Python.
* [pre-commit](https://pre-commit.com/) – framework for managing git pre-commit hooks.
* [pylint](https://pylint.readthedocs.io/) – source code analyzer.
* [pyright](https://github.com/microsoft/pyright) – fast type checker from Microsoft.
* [Ruff](https://docs.astral.sh/ruff/) – extremely fast Python linter and code formatter.
* [vulture](https://github.com/jendrikseipp/vulture) – find dead Python code.

---

### 🔒 Security

* [bandit](https://bandit.readthedocs.io/) – finds common security issues in Python code.
* [certifi](https://pypi.org/project/certifi/) – Mozilla's CA bundle for SSL certificate verification.
* [cryptography](https://cryptography.io/) – package for cryptographic recipes and primitives.
* [passlib](https://passlib.readthedocs.io/) – comprehensive password hashing library.
* [pip-audit](https://pypi.org/project/pip-audit/) – audit Python packages for known vulnerabilities.
* [PyJWT](https://pyjwt.readthedocs.io/) – JSON Web Token implementation.
* [pyOpenSSL](https://pypi.org/project/pyOpenSSL/) – Python wrapper around OpenSSL.
* [safety](https://pyup.io/safety/) – checks dependencies for known security vulnerabilities.

---

### 📦 Serialization & Validation

* [attrs](https://www.attrs.org/) – Python classes without boilerplate.
* [cattrs](https://cattrs.readthedocs.io/) – complex custom class converters for attrs.
* [marshmallow](https://marshmallow.readthedocs.io/) – ORM/ODM/framework-agnostic library for object serialization.
* [msgspec](https://jcristharif.com/msgspec/) – fast serialization and validation library.
* [orjson](https://github.com/ijl/orjson) – fast, correct Python JSON library.
* [protobuf](https://protobuf.dev/getting-started/pythontutorial/) – Protocol Buffers serialization.
* [Pydantic](https://docs.pydantic.dev/) – data validation using Python type annotations.
* [ujson](https://github.com/ultrajson/ultrajson) – ultra fast JSON encoder and decoder.

---

### 🌍 HTTP Clients

* [aiohttp](https://docs.aiohttp.org/) – async HTTP client/server framework.
* [grpcio](https://grpc.io/docs/languages/python/) – gRPC for Python.
* [httpx](https://www.python-httpx.org/) – fully featured HTTP client with both sync and async APIs.
* [requests](https://requests.readthedocs.io/) – simple, elegant HTTP library.
* [urllib3](https://urllib3.readthedocs.io/) – powerful HTTP client with thread safety.

---

### 🔐 Authentication & Authorization

* [authlib](https://authlib.org/) – library for building OAuth and OpenID Connect servers.
* [casbin](https://casbin.org/) – authorization library supporting ACL, RBAC, ABAC.
* [fastapi-users](https://fastapi-users.github.io/fastapi-users/) – user management for FastAPI.
* [python-jose](https://python-jose.readthedocs.io/) – JOSE (JWT, JWS, JWE, JWK) implementation.
* [python-keycloak](https://python-keycloak.readthedocs.io/) – Python package for Keycloak.

---

### 📡 Observability

* [Elastic APM](https://www.elastic.co/guide/en/apm/agent/python/current/index.html) – Python agent for Elastic APM.
* [loguru](https://loguru.readthedocs.io/) – library that aims to bring enjoyable logging to Python.
* [OpenTelemetry](https://opentelemetry.io/docs/languages/python/) – vendor-neutral observability framework.
* [prometheus-client](https://github.com/prometheus/client_python) – Prometheus instrumentation for Python.
* [py-spy](https://github.com/benfred/py-spy) – sampling profiler for Python programs.
* [pyinstrument](https://pyinstrument.readthedocs.io/) – Python profiler.
* [Sentry SDK](https://docs.sentry.io/platforms/python/) – error tracking and performance monitoring.
* [structlog](https://www.structlog.org/) – structured logging.

---

### 📚 Documentation

* [griffe](https://mkdocstrings.github.io/griffe/) – signatures and sources collector for Python.
* [MkDocs](https://www.mkdocs.org/) – static site generator for project documentation.
* [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) – Material Design theme for MkDocs.
* [pdoc](https://pdoc.dev/) – auto-generate API documentation from Python docstrings.
* [pydoc-markdown](https://niklasrosenstein.github.io/pydoc-markdown/) – generate Markdown from Python docstrings.
* [Sphinx](https://www.sphinx-doc.org/) – documentation generator.

---

### 🛠️ Package & Dependency Management

* [Hatch](https://hatch.pypa.io/) – modern, extensible Python project management.
* [pip](https://pip.pypa.io/) – standard Python package installer.
* [pip-tools](https://pip-tools.readthedocs.io/) – pin your dependencies for reproducible builds.
* [pipenv](https://pipenv.pypa.io/) – Python virtualenv management tool.
* [Poetry](https://python-poetry.org/) – dependency management and packaging tool.
* [pyenv](https://github.com/pyenv/pyenv) – manage multiple Python versions.
* [uv](https://docs.astral.sh/uv/) – extremely fast Python package and project manager.

---

### 🏗️ DevOps & Infrastructure

* [Ansible](https://docs.ansible.com/ansible/latest/dev_guide/developing_python_3.html) – IT automation platform.
* [azure-sdk-for-python](https://learn.microsoft.com/en-us/azure/developer/python/) – Azure SDK for Python.
* [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) – AWS SDK for Python.
* [docker-py](https://docker-py.readthedocs.io/) – Docker SDK for Python.
* [Fabric](https://www.fabfile.org/) – streamline use of SSH for application deployment.
* [google-cloud-python](https://cloud.google.com/python/docs) – Google Cloud client libraries.
* [Invoke](https://www.pyinvoke.org/) – task execution tool and library.
* [kubernetes](https://github.com/kubernetes-client/python) – official Kubernetes Python client.
* [Pulumi](https://www.pulumi.com/docs/languages-sdks/python/) – infrastructure as code in Python.

---

### ⚙️ Configuration Management

* [configparser](https://docs.python.org/3/library/configparser.html) – standard library INI configuration file parser.
* [dynaconf](https://www.dynaconf.com/) – configuration management with environment-based layered settings.
* [Hydra](https://hydra.cc/) – framework for elegantly configuring complex applications.
* [omegaconf](https://omegaconf.readthedocs.io/) – YAML-based hierarchical configuration system.
* [pydantic-settings](https://docs.pydantic.dev/latest/concepts/pydantic_settings/) – settings management using Pydantic.
* [python-dotenv](https://saurabh-kumar.com/python-dotenv/) – read key-value pairs from `.env` files.

---

### ⏰ Scheduling & Task Queues

* [Airflow](https://airflow.apache.org/) – platform to programmatically author, schedule, and monitor workflows.
* [APScheduler](https://apscheduler.readthedocs.io/) – advanced Python Scheduler.
* [Celery](https://docs.celeryq.dev/) – distributed task queue with scheduling support.
* [Prefect](https://docs.prefect.io/) – modern workflow orchestration.
* [Rocketry](https://rocketry.readthedocs.io/) – modern scheduling framework.
* [schedule](https://schedule.readthedocs.io/) – Python job scheduling for humans.

---

### 📄 File & Data Formats

* [lxml](https://lxml.de/) – powerful XML and HTML processing.
* [openpyxl](https://openpyxl.readthedocs.io/) – read/write Excel 2010 xlsx/xlsm/xltx/xltm files.
* [Pillow](https://python-pillow.org/) – Python Imaging Library fork.
* [pypdf](https://pypdf.readthedocs.io/) – PDF library for reading, writing and splitting PDF files.
* [python-docx](https://python-docx.readthedocs.io/) – create and update Microsoft Word files.
* [python-pptx](https://python-pptx.readthedocs.io/) – create and update PowerPoint files.
* [PyYAML](https://pyyaml.org/) – YAML parser and emitter.
* [toml](https://docs.python.org/3/library/tomllib.html) – standard library TOML parser (Python 3.11+).

---

### 🌐 Networking

* [dnspython](https://www.dnspython.org/) – DNS toolkit.
* [paramiko](https://www.paramiko.org/) – SSHv2 protocol library.
* [pyserial](https://pyserial.readthedocs.io/) – Python serial port access library.
* [pyzmq](https://pyzmq.readthedocs.io/) – Python bindings for ZeroMQ.
* [Scapy](https://scapy.net/) – packet manipulation library.
* [websockets](https://websockets.readthedocs.io/) – WebSockets client and server.

---

### 📖 Resources

**Official**
* [Python Docs](https://docs.python.org/3/) – official Python documentation.
* [PyPI](https://pypi.org/) – Python Package Index.
* [Python Enhancement Proposals](https://peps.python.org/) – PEPs index.

**Learning**
* [Real Python](https://realpython.com/) – tutorials for Python developers of all skill levels.
* [Python Weekly](https://www.pythonweekly.com/) – weekly Python newsletter.
* [PyCoder's Weekly](https://pycoders.com/) – weekly Python news and articles.

**Community**
* [Python Discord](https://pythondiscord.com/) – active Python community on Discord.
* [r/Python](https://www.reddit.com/r/Python/) – Python subreddit.
* [EuroPython](https://europython.eu/) – largest Python conference in Europe.
* [PyCon](https://pycon.org/) – Python Conference.

**Style Guides**
* [PEP 8](https://peps.python.org/pep-0008/) – Style Guide for Python Code.
* [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) – Google's Python style guide.
* [The Hitchhiker's Guide to Python](https://docs.python-guide.org/) – best practices for Python development.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[MIT](LICENSE) © [Think Cube](https://github.com/Think-Cube)
