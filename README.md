# ti-config

A [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) configuration focuses on malspam/phishing targeting Japan.

## Installation

```bash
pip install threatingestor
pip install threatingestor[twitter] threatingestor[rss]
pip install hug
```

## Usage

```bash
git clone https://github.com/ninoseki/ti-config
cd ti-config
threatingestor config.yml
```

You can fire up the web interface to check aggregation results.

```bash
hug -m threatingestor.extras.webapp
```

Then open `http://localhost:8000/` in your web browser.
