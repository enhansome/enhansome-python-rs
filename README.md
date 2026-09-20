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

* [arro3](https://github.com/kylebarron/arro3) ⭐ 265 | 🐛 32 | 🌐 Rust | 📅 2026-09-18 - A minimal Python library for Apache Arrow, binding to the Rust Arrow crate.

## Bioinformatics & Astronomy

* [satkit](https://github.com/ssmichael1/satkit) ⭐ 90 | 🐛 10 | 🌐 Rust | 📅 2026-09-19 - Satellite and orbital mechanics toolkit for astrodynamics calculations including orbit propagation and coordinate transformations.
* [bed-reader](https://github.com/fastlmm/bed-reader) ⭐ 85 | 🐛 4 | 🌐 Rust | 📅 2026-08-09 - Read and write the PLINK BED format, simply and efficiently.
* [mocpy](https://github.com/cds-astro/mocpy) ⭐ 78 | 🐛 8 | 🌐 Python | 📅 2026-09-09 - Astronomical Python library for describing coverage regions on the unit sphere.
* [haem](https://github.com/BooleanCat/haem) ⭐ 17 | 🐛 6 | 🌐 Python | 📅 2026-06-29 - A Python library for working on bioinformatics problems.

## Cloud Storage

* [opendal](https://github.com/apache/opendal) ⭐ 5,387 | 🐛 338 | 🌐 Rust | 📅 2026-09-19 - Apache OpenDAL: unified data access layer for all storage services.
* [obstore](https://github.com/developmentseed/obstore) ⭐ 812 | 🐛 56 | 🌐 Python | 📅 2026-09-15 - High-throughput Python interface to S3, GCS, and Azure Storage.

## Cryptography & Hashing

* [cryptography](https://github.com/pyca/cryptography) ⭐ 7,776 | 🐛 35 | 🌐 Python | 📅 2026-09-20 - The standard Python cryptographic library, with performance-critical parts in Rust.
* [blake3-py](https://github.com/oconnor663/blake3-py) ⭐ 203 | 🐛 7 | 🌐 Python | 📅 2026-09-09 - Python bindings for the BLAKE3 cryptographic hash function.
* [johnnycanencrypt](https://github.com/kushaldas/johnnycanencrypt) ⭐ 53 | 🐛 2 | 🌐 Rust | 📅 2026-02-05 - OpenPGP library with Yubikey support.

## Data Processing & DataFrames

* [pathway](https://github.com/pathwaycom/pathway) ⭐ 62,258 | 🐛 37 | 🌐 Python | 📅 2026-09-20 - Performant Python ETL framework with a Rust runtime.
* [polars](https://github.com/pola-rs/polars) ⭐ 39,809 | 🐛 2,888 | 🌐 Rust | 📅 2026-09-20 - DataFrame library with lazy evaluation and parallel execution.
* [sail](https://github.com/lakehq/sail) ⭐ 3,381 | 🐛 285 | 🌐 Rust | 📅 2026-09-20 - Unifying stream, batch, and AI workloads with Apache Spark compatibility.
* [delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,315 | 🐛 167 | 🌐 Rust | 📅 2026-09-20 - Native Rust library for Delta Lake with Python bindings (`deltalake` on PyPI).
* [connector-x](https://github.com/sfu-db/connector-x) ⭐ 2,648 | 🐛 217 | 🌐 Rust | 📅 2026-09-20 - Fastest library to load data from databases into DataFrames.
* [datafusion-python](https://github.com/apache/datafusion-python) ⭐ 605 | 🐛 99 | 🌐 Python | 📅 2026-09-19 - Python bindings for Apache DataFusion, an in-memory query engine.
* [hudi-rs](https://github.com/apache/hudi-rs) ⭐ 279 | 🐛 84 | 🌐 Rust | 📅 2026-09-18 - Native Rust implementation for Apache Hudi with Python bindings.

## Date & Time

* [pendulum](https://github.com/python-pendulum/pendulum) ⭐ 6,674 | 🐛 253 | 🌐 Python | 📅 2026-09-19 - Python datetimes made easy; performance-critical parts rewritten from C to Rust in v3.
* [whenever](https://github.com/ariebovenberg/whenever) ⭐ 2,403 | 🐛 7 | 🌐 Python | 📅 2026-09-19 - Typed and DST-safe datetimes for Python.

## Data Structures

* [fastuuid](https://github.com/thedrow/fastuuid) ⭐ 189 | 🐛 14 | 🌐 Python | 📅 2025-10-19 - Python bindings to Rust's UUID library.
* [fastbloom](https://github.com/yankun1992/fastbloom) ⭐ 114 | 🐛 6 | 🌐 Rust | 📅 2025-09-01 - A fast bloom filter and counting bloom filter.
* [pyochain](https://github.com/OutSquareCapital/pyochain) ⭐ 73 | 🐛 15 | 🌐 Python | 📅 2026-09-20 - Iterator, sorted containers, Result, Option, ABCs and more, written in Rust, for Python.
* [rpds-py](https://github.com/crate-py/rpds) ⭐ 64 | 🐛 2 | 🌐 Rust | 📅 2026-09-19 - Python bindings to the Rust rpds crate for persistent data structures.

## File Watching & System Utilities

* [watchfiles](https://github.com/samuelcolvin/watchfiles) ⭐ 2,537 | 🐛 53 | 🌐 Python | 📅 2026-09-18 - Simple, modern, fast file watching and code reload, powered by Rust's `notify` crate.
* [cramjam](https://github.com/milesgranger/cramjam) ⭐ 127 | 🐛 10 | 🌐 Rust | 📅 2026-09-11 - Thin Python bindings to de/compression algorithms (snappy, brotli, lz4, zstd, etc.).

## Finance

* [rateslib](https://github.com/attack68/rateslib) ⭐ 359 | 🐛 24 | 📅 2026-05-20 - A fixed income library for Python using Rust extensions.
* [finalytics](https://github.com/Nnamdi-sys/finalytics) ⭐ 75 | 🐛 2 | 🌐 Rust | 📅 2026-05-01 - Investment analysis library.

## Geospatial

* [geo-index](https://github.com/kylebarron/geo-index) ⭐ 200 | 🐛 30 | 🌐 Rust | 📅 2026-09-15 - Packed, immutable, zero-copy spatial indexes.
* [tzfpy](https://github.com/ringsaturn/tzfpy) ⭐ 142 | 🐛 3 | 🌐 Python | 📅 2026-09-19 - Fast longitude/latitude to timezone name conversion.
* [utiles](https://github.com/jessekrubin/utiles) ⭐ 29 | 🐛 4 | 🌐 Rust | 📅 2026-09-18 - Fast web-map tile utilities.

## Graph Libraries

* [rustworkx](https://github.com/Qiskit/rustworkx) ⭐ 1,758 | 🐛 136 | 🌐 Rust | 📅 2026-09-18 - A high-performance Python graph library (originally created for Qiskit).

## HTTP Clients

* [rnet](https://github.com/0x676e67/rnet) ⭐ 1,444 | 🐛 12 | 🌐 Rust | 📅 2026-09-18 - Asynchronous Python HTTP client powered by Rust.
* [primp](https://github.com/deedy5/primp) ⭐ 602 | 🐛 3 | 🌐 Rust | 📅 2026-09-13 - Fast HTTP client that can impersonate browsers by mimicking TLS/JA3/HTTP2 fingerprints.
* [pyreqwest](https://github.com/MarkusSintonen/pyreqwest) ⭐ 402 | 🐛 8 | 🌐 Python | 📅 2026-09-10 - Fast HTTP client built on Rust's reqwest library with async/sync support and full type safety.

## Linting, Formatting & Type Checking

* [ruff](https://github.com/astral-sh/ruff) ⭐ 49,702 | 🐛 2,184 | 🌐 Rust | 📅 2026-09-20 - An extremely fast Python linter and code formatter.
* [ty](https://github.com/astral-sh/ty) ⭐ 19,723 | 🐛 917 | 🌐 Python | 📅 2026-09-18 - An extremely fast Python type checker and language server by Astral.
* [pyrefly](https://github.com/facebook/pyrefly) ⭐ 6,990 | 🐛 711 | 🌐 Rust | 📅 2026-09-20 - A fast Python type checker and language server from Meta.
* [pylyzer](https://github.com/mtshiba/pylyzer) ⭐ 2,854 | 🐛 10 | 🌐 Rust | 📅 2025-05-10 - A fast static type checker and language server for Python, over 100x faster than Pyright.
* [rumdl](https://github.com/rvben/rumdl) ⭐ 1,510 | 🐛 27 | 🌐 Rust | 📅 2026-09-18 - A high-performance Markdown linter and formatter written in Rust.
* [zuban](https://github.com/zubanls/zuban) ⭐ 1,197 | 🐛 82 | 🌐 Rust | 📅 2026-09-20 - A high-performance Python language server and type checker with PyRight-like and Mypy-compatible modes.

## Miscellaneous

* [pyxel](https://github.com/kitao/pyxel) ⭐ 17,877 | 🐛 10 | 🌐 Rust | 📅 2026-09-16 - A retro game engine for Python, with core written in Rust.
* [pycrdt](https://github.com/jupyter-server/pycrdt) ⭐ 205 | 🐛 26 | 🌐 Python | 📅 2026-09-14 - Python bindings for the Yrs Rust CRDT implementation (collaborative editing).
* [ry](https://github.com/jessekrubin/ry) ⭐ 76 | 🐛 9 | 🌐 Rust | 📅 2026-09-18 - Collection of Python bindings to Rust crates providing utilities for async HTTP, datetime, file I/O, and compression.

## Package Management & Tooling

* [uv](https://github.com/astral-sh/uv) ⭐ 90,004 | 🐛 2,900 | 🌐 Rust | 📅 2026-09-20 - An extremely fast Python package and project manager. 10-100x faster than pip, replaces pip-tools, poetry, pyenv, pipx, and virtualenv in a single tool.
* [prek](https://github.com/j178/prek) ⭐ 8,434 | 🐛 36 | 🌐 Rust | 📅 2026-09-20 - A fast Rust-based reimplementation of the pre-commit framework for managing Git hooks.
* [pixi](https://github.com/prefix-dev/pixi) ⭐ 7,750 | 🐛 720 | 🌐 Rust | 📅 2026-09-18 - A fast conda/pip package manager.
* [maturin](https://github.com/PyO3/maturin) ⭐ 5,811 | 🐛 54 | 🌐 Rust | 📅 2026-09-16 - Build and publish Rust-based Python packages with pyo3, cffi, and uniffi bindings.

## Profiling

* [filprofiler](https://github.com/pythonspeed/filprofiler/) ⭐ 908 | 🐛 106 | 🌐 Rust | 📅 2026-05-03 - Memory profiler for Python that identifies peak memory usage and allocation sources in data processing applications.

## Rust-Python Interop

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,355 | 🐛 392 | 🌐 Rust | 📅 2026-09-20 - A Python 3 interpreter written entirely in Rust.
* [PyO3](https://github.com/PyO3/pyo3) ⭐ 16,156 | 🐛 405 | 🌐 Rust | 📅 2026-09-19 - Rust bindings for the Python interpreter. The foundation for most projects on this list.
* [setuptools-rust](https://github.com/PyO3/setuptools-rust) ⭐ 680 | 🐛 19 | 🌐 Python | 📅 2026-09-10 - Setuptools plugin for Rust extensions.

## Scientific Computing

* [river](https://github.com/online-ml/river) ⭐ 6,104 | 🐛 73 | 🌐 Python | 📅 2026-09-18 - Online machine learning in Python; computationally heavy algorithms in Rust.
* [radiate](https://github.com/pkalivas/radiate) ⭐ 256 | 🐛 0 | 🌐 Rust | 📅 2026-09-19 - A high-performance evolution engine for genetic programming and evolutionary algorithms.
* [feos](https://github.com/feos-org/feos) ⭐ 196 | 🐛 33 | 🌐 Rust | 📅 2026-09-18 - Lightning fast thermodynamic modeling with a fully developed Python interface.
* [forust](https://github.com/jinlow/forust) ⭐ 96 | 🐛 10 | 🌐 Rust | 📅 2026-04-13 - A lightweight gradient boosted decision tree library.
* [cellular\_raza](https://github.com/jonaspleyer/cellular_raza) ⭐ 21 | 🐛 5 | 🌐 Rust | 📅 2026-09-11 - A cellular agent-based simulation framework.

## Search & Indexing

* [tantivy-py](https://github.com/quickwit-oss/tantivy-py) ⭐ 427 | 🐛 11 | 🌐 Rust | 📅 2026-09-17 - Python bindings for Tantivy, a full-text search engine library (Lucene alternative).
* [ahocorasick\_rs](https://github.com/G-Research/ahocorasick_rs/) ⭐ 234 | 🐛 15 | 🌐 Python | 📅 2026-09-07 - Fast multi-pattern string search using the Aho-Corasick algorithm, 1.5-7x faster than alternatives.
* [ruosh](https://github.com/AiDinho/ruosh) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-25 - A pythonic  full-text search library with a  Whoosh-like API, but the search engine underneath is Tantivy.

## Security

* [PySpector](https://github.com/ParzivalHack/PySpector) ⭐ 151 | 🐛 2 | 🌐 Python | 📅 2026-09-20 - A High-Performance Python/Rust Graph-Based SAST Framework.

## Serialization & Parsing

* [orjson](https://github.com/ijl/orjson) ⭐ 8,229 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - Fast, correct JSON library supporting dataclasses, datetimes, and numpy.
* [jiter](https://github.com/pydantic/jiter) ⭐ 550 | 🐛 25 | 🌐 Rust | 📅 2026-09-12 - Fast iterable JSON parser, used by pydantic and the OpenAI Python SDK.
* [ormsgpack](https://github.com/aviramha/ormsgpack) ⭐ 399 | 🐛 8 | 🌐 Rust | 📅 2026-09-18 - Fast MessagePack serialization/deserialization, derived from orjson.
* [lp\_parser\_rs](https://github.com/dandxy89/lp_parser_rs) ⭐ 5 | 🐛 2 | 🌐 Mathematical Programming System | 📅 2026-09-10 - Parser for Linear Programming files supporting IBM CPLEX, FICO Xpress, Gurobi, and Mosek formats.

## Sorting

* [natsort-rs](https://github.com/valentinstn/natsort-rs) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-05-16 - Fast natural sorting library, 5-45x faster than alternatives.

## Tokenization & ML

* [tiktoken](https://github.com/openai/tiktoken) ⭐ 19,288 | 🐛 131 | 🌐 Python | 📅 2026-08-17 - A fast BPE tokenizer for use with OpenAI's models.
* [tokenizers](https://github.com/huggingface/tokenizers) ⭐ 11,050 | 🐛 219 | 🌐 Rust | 📅 2026-09-18 - Hugging Face's fast tokenizer library with Python bindings.
* [safetensors](https://github.com/huggingface/safetensors) ⭐ 3,900 | 🐛 91 | 🌐 Rust | 📅 2026-09-18 - A safe and fast format for storing and loading tensors.

## Validation & Data Modeling

* [pydantic-core](https://github.com/pydantic/pydantic-core) ⚠️ Archived - Core validation logic for pydantic, written in Rust.
* [jsonschema-rs](https://github.com/Stranger6667/jsonschema) ⭐ 817 | 🐛 12 | 🌐 Rust | 📅 2026-09-16 - A high-performance JSON Schema validator.

## Visualization

* [rerun](https://github.com/rerun-io/rerun) ⭐ 11,478 | 🐛 1,266 | 🌐 Rust | 📅 2026-09-18 - Visualize streams of multimodal data. Built in Rust with a Python SDK.

## Web Frameworks & Servers

* [robyn](https://github.com/sansyrox/robyn) ⭐ 7,404 | 🐛 101 | 🌐 Python | 📅 2026-09-14 - A super fast async Python web framework with a Rust runtime.
* [granian](https://github.com/emmett-framework/granian) ⭐ 5,656 | 🐛 41 | 🌐 Rust | 📅 2026-09-14 - A Rust HTTP server for Python WSGI/ASGI/RSGI apps, built on Hyper and Tokio.

## Web Scraping & HTML

* [selectolax](https://github.com/rushter/selectolax) ⭐ 1,679 | 🐛 9 | 🌐 Cython | 📅 2026-09-18 - Fast HTML5 parser with CSS selectors, using Rust's html5ever engine.
* [css-inline](https://github.com/Stranger6667/css-inline) ⭐ 316 | 🐛 29 | 🌐 Rust | 📅 2026-09-18 - CSS inlining implemented in Rust, for fast HTML email preparation.
* [html-py-ever](https://github.com/SimonSapin/html5ever-python) ⚠️ Archived - Fast HTML parsing and CSS selecting via html5ever.
* [markupever](https://github.com/awolverp/markupever) ⭐ 37 | 🐛 2 | 🌐 Rust | 📅 2026-07-21 - High-performance HTML and XML parser with CSS selector support built on Rust's html5ever engine.
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

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-20._
