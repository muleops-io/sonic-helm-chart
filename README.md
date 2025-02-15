# Sonic helm chart

**Sonic is a fast, lightweight and schema-less search backend. It ingests search texts and identifier tuples that can then be queried against in a microsecond's time.**

Sonic can be used as a simple alternative to super-heavy and full-featured search backends such as Elasticsearch in some use-cases. It is capable of normalizing natural language search queries, auto-completing a search query and providing the most relevant results for a query. Sonic is an identifier index, rather than a document index; when queried, it returns IDs that can then be used to refer to the matched documents in an external database.

A strong attention to performance and code cleanliness has been given when designing Sonic. It aims at being crash-free, super-fast and puts minimum strain on server resources (our measurements have shown that Sonic - when under load - responds to search queries in the μs range, eats ~30MB RAM and has a low CPU footprint;

![Sonic](https://valeriansaliou.github.io/sonic/images/banner.jpg)

Sonic Helm chart for Kubernetes
