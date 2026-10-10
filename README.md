# Awesome Python Rs with stars

> Python tools, libraries, and frameworks with Rust under the hood.

## Contents

* [Arrow & Columnar Data](#arrow--columnar-data)
* [Bioinformatics & Astronomy](#bioinformatics--astronomy)
* [Cloud Storage](#cloud-storage)
* [Cryptography & Hashing](#cryptography--hashing)
* [Data Processing & DataFrames](#data-processing--dataframes)
* [Date & Time](#date--time)
* [Data Structures](#data-structures)
* [File Watching & System Utilities](#file-watching--system-utilities)
* [Finance](#finance)
* [Geospatial](#geospatial)
* [Graph Libraries](#graph-libraries)
* [HTTP Clients](#http-clients)
* [Linting, Formatting & Type Checking](#linting-formatting--type-checking)
* [Miscellaneous](#miscellaneous)
* [Package Management & Tooling](#package-management--tooling)
* [Profiling](#profiling)
* [Rust-Python Interop](#rust-python-interop)
* [Scientific Computing](#scientific-computing)
* [Search & Indexing](#search--indexing)
* [Security](#security)
* [Serialization & Parsing](#serialization--parsing)
* [Sorting](#sorting)
* [Tokenization & ML](#tokenization--ml)
* [Validation & Data Modeling](#validation--data-modeling)
* [Visualization](#visualization)
* [Web Frameworks & Servers](#web-frameworks--servers)
* [Web Scraping & HTML](#web-scraping--html)

## Arrow & Columnar Data

* [arro3](https://github.com/kylebarron/arro3) ⭐ 266 | 🐛 22 | 🌐 Rust | 📅 2026-10-01 - A minimal Python library for Apache Arrow, binding to the Rust Arrow crate.

## Bioinformatics & Astronomy

* [satkit](https://github.com/ssmichael1/satkit) ⭐ 92 | 🐛 1 | 🌐 Rust | 📅 2026-10-10 - Satellite and orbital mechanics toolkit for astrodynamics calculations including orbit propagation and coordinate transformations.
* [bed-reader](https://github.com/fastlmm/bed-reader) ⭐ 87 | 🐛 4 | 🌐 Rust | 📅 2026-08-09 - Read and write the PLINK BED format, simply and efficiently.
* [mocpy](https://github.com/cds-astro/mocpy) ⭐ 78 | 🐛 8 | 🌐 Python | 📅 2026-09-09 - Astronomical Python library for describing coverage regions on the unit sphere.
* [haem](https://github.com/BooleanCat/haem) ⭐ 17 | 🐛 6 | 🌐 Python | 📅 2026-06-29 - A Python library for working on bioinformatics problems.

## Cloud Storage

* [opendal](https://github.com/apache/opendal) ⭐ 5,410 | 🐛 356 | 🌐 Rust | 📅 2026-10-08 - Apache OpenDAL: unified data access layer for all storage services.
* [obstore](https://github.com/developmentseed/obstore) ⭐ 821 | 🐛 57 | 🌐 Python | 📅 2026-10-06 - High-throughput Python interface to S3, GCS, and Azure Storage.

## Cryptography & Hashing

* [cryptography](https://github.com/pyca/cryptography) ⭐ 7,803 | 🐛 39 | 🌐 Python | 📅 2026-10-10 - The standard Python cryptographic library, with performance-critical parts in Rust.
* [blake3-py](https://github.com/oconnor663/blake3-py) ⭐ 205 | 🐛 5 | 🌐 Python | 📅 2026-10-08 - Python bindings for the BLAKE3 cryptographic hash function.
* [johnnycanencrypt](https://github.com/kushaldas/johnnycanencrypt) ⭐ 53 | 🐛 2 | 🌐 Rust | 📅 2026-02-05 - OpenPGP library with Yubikey support.

## Data Processing & DataFrames

* [pathway](https://github.com/pathwaycom/pathway) ⭐ 62,144 | 🐛 37 | 🌐 Python | 📅 2026-10-10 - Performant Python ETL framework with a Rust runtime.
* [polars](https://github.com/pola-rs/polars) ⭐ 40,086 | 🐛 2,959 | 🌐 Rust | 📅 2026-10-10 - DataFrame library with lazy evaluation and parallel execution.
* [sail](https://github.com/lakehq/sail) ⭐ 3,424 | 🐛 308 | 🌐 Rust | 📅 2026-10-10 - Unifying stream, batch, and AI workloads with Apache Spark compatibility.
* [delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,329 | 🐛 143 | 🌐 Rust | 📅 2026-10-10 - Native Rust library for Delta Lake with Python bindings (`deltalake` on PyPI).
* [connector-x](https://github.com/sfu-db/connector-x) ⭐ 2,659 | 🐛 227 | 🌐 Rust | 📅 2026-10-10 - Fastest library to load data from databases into DataFrames.
* [datafusion-python](https://github.com/apache/datafusion-python) ⭐ 607 | 🐛 100 | 🌐 Python | 📅 2026-10-08 - Python bindings for Apache DataFusion, an in-memory query engine.
* [hudi-rs](https://github.com/apache/hudi-rs) ⭐ 280 | 🐛 91 | 🌐 Rust | 📅 2026-10-09 - Native Rust implementation for Apache Hudi with Python bindings.

## Date & Time

* [pendulum](https://github.com/python-pendulum/pendulum) ⭐ 6,678 | 🐛 266 | 🌐 Python | 📅 2026-10-08 - Python datetimes made easy; performance-critical parts rewritten from C to Rust in v3.
* [whenever](https://github.com/ariebovenberg/whenever) ⭐ 2,407 | 🐛 7 | 🌐 Python | 📅 2026-10-10 - Typed and DST-safe datetimes for Python.

## Data Structures

* [fastuuid](https://github.com/thedrow/fastuuid) ⭐ 189 | 🐛 15 | 🌐 Python | 📅 2025-10-19 - Python bindings to Rust's UUID library.
* [fastbloom](https://github.com/yankun1992/fastbloom) ⭐ 114 | 🐛 6 | 🌐 Rust | 📅 2025-09-01 - A fast bloom filter and counting bloom filter.
* [pyochain](https://github.com/OutSquareCapital/pyochain) ⭐ 77 | 🐛 22 | 🌐 Python | 📅 2026-10-09 - Iterator, sorted containers, Result, Option, ABCs and more, written in Rust, for Python.
* [rpds-py](https://github.com/crate-py/rpds) ⭐ 66 | 🐛 2 | 🌐 Rust | 📅 2026-10-06 - Python bindings to the Rust rpds crate for persistent data structures.

## File Watching & System Utilities

* [watchfiles](https://github.com/samuelcolvin/watchfiles) ⭐ 2,550 | 🐛 49 | 🌐 Python | 📅 2026-09-21 - Simple, modern, fast file watching and code reload, powered by Rust's `notify` crate.
* [cramjam](https://github.com/milesgranger/cramjam) ⭐ 128 | 🐛 9 | 🌐 Rust | 📅 2026-10-01 - Thin Python bindings to de/compression algorithms (snappy, brotli, lz4, zstd, etc.).

## Finance

* [rateslib](https://github.com/attack68/rateslib) ⭐ 365 | 🐛 24 | 📅 2026-05-20 - A fixed income library for Python using Rust extensions.
* [finalytics](https://github.com/Nnamdi-sys/finalytics) ⭐ 77 | 🐛 2 | 🌐 Rust | 📅 2026-05-01 - Investment analysis library.

## Geospatial

* [geo-index](https://github.com/kylebarron/geo-index) ⭐ 200 | 🐛 30 | 🌐 Rust | 📅 2026-09-15 - Packed, immutable, zero-copy spatial indexes.
* [tzfpy](https://github.com/ringsaturn/tzfpy) ⭐ 142 | 🐛 3 | 🌐 Python | 📅 2026-10-09 - Fast longitude/latitude to timezone name conversion.
* [utiles](https://github.com/jessekrubin/utiles) ⭐ 29 | 🐛 3 | 🌐 Rust | 📅 2026-10-07 - Fast web-map tile utilities.

## Graph Libraries

* [rustworkx](https://github.com/Qiskit/rustworkx) ⭐ 1,767 | 🐛 144 | 🌐 Rust | 📅 2026-10-09 - A high-performance Python graph library (originally created for Qiskit).

## HTTP Clients

* [rnet](https://github.com/0x676e67/rnet) ⭐ 1,485 | 🐛 9 | 🌐 Python | 📅 2026-10-10 - Asynchronous Python HTTP client powered by Rust.
* [primp](https://github.com/deedy5/primp) ⭐ 615 | 🐛 5 | 🌐 Rust | 📅 2026-09-13 - Fast HTTP client that can impersonate browsers by mimicking TLS/JA3/HTTP2 fingerprints.
* [pyreqwest](https://github.com/MarkusSintonen/pyreqwest) ⭐ 405 | 🐛 6 | 🌐 Python | 📅 2026-10-01 - Fast HTTP client built on Rust's reqwest library with async/sync support and full type safety.

## Linting, Formatting & Type Checking

* [ruff](https://github.com/astral-sh/ruff) ⭐ 49,977 | 🐛 2,220 | 🌐 Rust | 📅 2026-10-10 - An extremely fast Python linter and code formatter.
* [ty](https://github.com/astral-sh/ty) ⭐ 19,838 | 🐛 932 | 🌐 Python | 📅 2026-10-10 - An extremely fast Python type checker and language server by Astral.
* [pyrefly](https://github.com/facebook/pyrefly) ⭐ 7,072 | 🐛 713 | 🌐 Rust | 📅 2026-10-09 - A fast Python type checker and language server from Meta.
* [pylyzer](https://github.com/mtshiba/pylyzer) ⭐ 2,857 | 🐛 10 | 🌐 Rust | 📅 2025-05-10 - A fast static type checker and language server for Python, over 100x faster than Pyright.
* [rumdl](https://github.com/rvben/rumdl) ⭐ 1,562 | 🐛 29 | 🌐 Rust | 📅 2026-10-09 - A high-performance Markdown linter and formatter written in Rust.
* [zuban](https://github.com/zubanls/zuban) ⭐ 1,215 | 🐛 86 | 🌐 Rust | 📅 2026-10-10 - A high-performance Python language server and type checker with PyRight-like and Mypy-compatible modes.

## Miscellaneous

* [pycrdt](https://github.com/jupyter-server/pycrdt) ⭐ 208 | 🐛 27 | 🌐 Python | 📅 2026-10-05 - Python bindings for the Yrs Rust CRDT implementation (collaborative editing).
* [ry](https://github.com/jessekrubin/ry) ⭐ 77 | 🐛 10 | 🌐 Rust | 📅 2026-10-10 - Collection of Python bindings to Rust crates providing utilities for async HTTP, datetime, file I/O, and compression.
* [pyxel](https://github.com/kitao/pyxel) - A retro game engine for Python, with core written in Rust.

## Package Management & Tooling

* [uv](https://github.com/astral-sh/uv) ⭐ 90,575 | 🐛 2,988 | 🌐 Rust | 📅 2026-10-10 - An extremely fast Python package and project manager. 10-100x faster than pip, replaces pip-tools, poetry, pyenv, pipx, and virtualenv in a single tool.
* [prek](https://github.com/j178/prek) ⭐ 8,599 | 🐛 37 | 🌐 Rust | 📅 2026-10-10 - A fast Rust-based reimplementation of the pre-commit framework for managing Git hooks.
* [pixi](https://github.com/prefix-dev/pixi) ⭐ 7,840 | 🐛 660 | 🌐 Rust | 📅 2026-10-09 - A fast conda/pip package manager.
* [maturin](https://github.com/PyO3/maturin) ⭐ 5,832 | 🐛 55 | 🌐 Rust | 📅 2026-10-08 - Build and publish Rust-based Python packages with pyo3, cffi, and uniffi bindings.

## Profiling

* [filprofiler](https://github.com/pythonspeed/filprofiler/) ⭐ 907 | 🐛 106 | 🌐 Rust | 📅 2026-05-03 - Memory profiler for Python that identifies peak memory usage and allocation sources in data processing applications.

## Rust-Python Interop

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,393 | 🐛 305 | 🌐 Rust | 📅 2026-10-10 - A Python 3 interpreter written entirely in Rust.
* [PyO3](https://github.com/PyO3/pyo3) ⭐ 16,218 | 🐛 403 | 🌐 Rust | 📅 2026-10-09 - Rust bindings for the Python interpreter. The foundation for most projects on this list.
* [setuptools-rust](https://github.com/PyO3/setuptools-rust) ⭐ 681 | 🐛 11 | 🌐 Python | 📅 2026-10-07 - Setuptools plugin for Rust extensions.

## Scientific Computing

* [river](https://github.com/online-ml/river) ⭐ 6,120 | 🐛 87 | 🌐 Python | 📅 2026-10-07 - Online machine learning in Python; computationally heavy algorithms in Rust.
* [radiate](https://github.com/pkalivas/radiate) ⭐ 257 | 🐛 0 | 🌐 Rust | 📅 2026-10-08 - A high-performance evolution engine for genetic programming and evolutionary algorithms.
* [feos](https://github.com/feos-org/feos) ⭐ 199 | 🐛 31 | 🌐 Rust | 📅 2026-10-08 - Lightning fast thermodynamic modeling with a fully developed Python interface.
* [forust](https://github.com/jinlow/forust) ⭐ 96 | 🐛 10 | 🌐 Rust | 📅 2026-10-09 - A lightweight gradient boosted decision tree library.
* [cellular\_raza](https://github.com/jonaspleyer/cellular_raza) ⭐ 23 | 🐛 5 | 🌐 Rust | 📅 2026-10-08 - A cellular agent-based simulation framework.

## Search & Indexing

* [tantivy-py](https://github.com/quickwit-oss/tantivy-py) ⭐ 431 | 🐛 9 | 🌐 Rust | 📅 2026-10-09 - Python bindings for Tantivy, a full-text search engine library (Lucene alternative).
* [ahocorasick\_rs](https://github.com/G-Research/ahocorasick_rs/) ⭐ 234 | 🐛 15 | 🌐 Python | 📅 2026-09-07 - Fast multi-pattern string search using the Aho-Corasick algorithm, 1.5-7x faster than alternatives.
* [ruosh](https://github.com/AiDinho/ruosh) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-25 - A pythonic  full-text search library with a  Whoosh-like API, but the search engine underneath is Tantivy.

## Security

* [PySpector](https://github.com/ParzivalHack/PySpector) ⭐ 151 | 🐛 4 | 🌐 Python | 📅 2026-10-10 - A High-Performance Python/Rust Graph-Based SAST Framework.

## Serialization & Parsing

* [orjson](https://github.com/ijl/orjson) ⭐ 8,250 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - Fast, correct JSON library supporting dataclasses, datetimes, and numpy.
* [jiter](https://github.com/pydantic/jiter) ⭐ 555 | 🐛 29 | 🌐 Rust | 📅 2026-09-26 - Fast iterable JSON parser, used by pydantic and the OpenAI Python SDK.
* [ormsgpack](https://github.com/aviramha/ormsgpack) ⭐ 402 | 🐛 7 | 🌐 Rust | 📅 2026-10-10 - Fast MessagePack serialization/deserialization, derived from orjson.
* [lp\_parser\_rs](https://github.com/dandxy89/lp_parser_rs) ⭐ 5 | 🐛 2 | 🌐 Mathematical Programming System | 📅 2026-10-02 - Parser for Linear Programming files supporting IBM CPLEX, FICO Xpress, Gurobi, and Mosek formats.

## Sorting

* [natsort-rs](https://github.com/valentinstn/natsort-rs) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-05-16 - Fast natural sorting library, 5-45x faster than alternatives.

## Tokenization & ML

* [tiktoken](https://github.com/openai/tiktoken) ⭐ 19,432 | 🐛 141 | 🌐 Python | 📅 2026-08-17 - A fast BPE tokenizer for use with OpenAI's models.
* [tokenizers](https://github.com/huggingface/tokenizers) ⭐ 11,163 | 🐛 182 | 🌐 Rust | 📅 2026-10-09 - Hugging Face's fast tokenizer library with Python bindings.
* [safetensors](https://github.com/huggingface/safetensors) ⭐ 3,915 | 🐛 109 | 🌐 Rust | 📅 2026-10-06 - A safe and fast format for storing and loading tensors.

## Validation & Data Modeling

* [pydantic-core](https://github.com/pydantic/pydantic-core) ⚠️ Archived - Core validation logic for pydantic, written in Rust.
* [jsonschema-rs](https://github.com/Stranger6667/jsonschema) ⭐ 826 | 🐛 20 | 🌐 Rust | 📅 2026-10-06 - A high-performance JSON Schema validator.

## Visualization

* [rerun](https://github.com/rerun-io/rerun) ⭐ 11,574 | 🐛 1,237 | 🌐 Rust | 📅 2026-10-09 - Visualize streams of multimodal data. Built in Rust with a Python SDK.

## Web Frameworks & Servers

* [robyn](https://github.com/sansyrox/robyn) ⭐ 7,415 | 🐛 104 | 🌐 Python | 📅 2026-10-05 - A super fast async Python web framework with a Rust runtime.
* [granian](https://github.com/emmett-framework/granian) ⭐ 5,694 | 🐛 51 | 🌐 Rust | 📅 2026-10-07 - A Rust HTTP server for Python WSGI/ASGI/RSGI apps, built on Hyper and Tokio.

## Web Scraping & HTML

* [selectolax](https://github.com/rushter/selectolax) ⭐ 1,688 | 🐛 3 | 🌐 Python | 📅 2026-10-10 - Fast HTML5 parser with CSS selectors, using Rust's html5ever engine.
* [css-inline](https://github.com/Stranger6667/css-inline) ⭐ 318 | 🐛 26 | 🌐 Rust | 📅 2026-10-06 - CSS inlining implemented in Rust, for fast HTML email preparation.
* [html-py-ever](https://github.com/SimonSapin/html5ever-python) ⚠️ Archived - Fast HTML parsing and CSS selecting via html5ever.
* [markupever](https://github.com/awolverp/markupever) ⭐ 37 | 🐛 2 | 🌐 Rust | 📅 2026-10-09 - High-performance HTML and XML parser with CSS selector support built on Rust's html5ever engine.
* [html2text-rs](https://github.com/deedy5/html2text_rs) ⭐ 19 | 🐛 2 | 🌐 Rust | 📅 2026-04-23 - Python library for converting HTML to markup or plain text.

## Footnotes

### Learning Resources

* [PyO3 User Guide](https://pyo3.rs/) - Official guide for writing Python extensions in Rust.
* [maturin User Guide](https://www.maturin.rs/) - Build and publish Rust Python packages.
* [Writing Python Extensions in Rust](https://www.infoworld.com/article/3687744/how-to-write-python-extensions-in-rust-with-pyo3.html) - InfoWorld tutorial.

### Articles

* [Making Python 100x faster with less than 100 lines of Rust](https://ohadravid.github.io/posts/2023-03-rusty-python/) - Performance optimization guide.
* [Why Rust is the Future of Python Tooling](https://pythonspeed.com/articles/rust-python-tooling/) - Analysis of the Rust-Python ecosystem.

### Communities

* [PyO3 Discord](https://discord.gg/33kcChzH7f) - Official PyO3 community.
* [r/rust](https://reddit.com/r/rust) - Rust community.
* [r/Python](https://reddit.com/r/Python) - Python community.

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-10._
