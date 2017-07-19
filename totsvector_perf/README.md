
# Benchmark scripts for to\_tsvector

There are two script for benchmarking PostreSQL function `to_tsvector` with
internal `english_stem` dictionary and `english_hunspell` dictionary.
These scripts are used to check performance of the `to_tsvector` during development of multi-language support modification.

Data set is constant and based on APOD data dump from [za-arthur/pg\_multilingual repo](https://github.com/za-arthur/pg_multilingual/).

For more information about Hunspell dictionaries and instructions how to intall it check [za-arthur/hunspell\_dicts repo](https://github.com/postgrespro/hunspell_dicts).

