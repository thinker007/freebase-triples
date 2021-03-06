# CHANGELOG
Overview of the full pipeline.

# Scripts

```
```

# Data

Organizing the files as if running $ tree command:
```
Original: freebase-rdf-latest.gz
.
└── freebase-rdf-latest
    # *[10K Samples - GitHub]*
    ├── fb-rdf-10k-head.nt
        ├── fb-rdf-10k-head-s01-c01.nt
        ├── fb-rdf-10k-head-s01-c02.nt
        └── fb-rdf-10k-head-s01-c03.nt
            └── fb-rdf-10k-head-desc-all-s02-c01.nt
                └── fb-rdf-10k-head-desc-en-s02-c01.nt
            └── fb-rdf-10k-head-name-all-s02-c01.nt
                └── fb-rdf-10k-head-name-en-s02-c01.nt
            └── fb-rdf-10k-head-type-s02-c01.nt
    ├── fb-rdf-10k-tail-s01-c01.nt
    ├── fb-rdf-10k-desc-all-s01-c01.nt
    ├── fb-rdf-10k-names-en-s01-c01.nt
    ├── fb-rdf-10k-names-all-s01-c01.nt
    # *[All Data - External Drive]*
    ├── freebase-rdf-latest-s01-c01
    ├\─ freebase-rdf-latest-s01-c02 [Skipped]
    └\─ freebase-rdf-latest-s01-c03 [Skipped]
        └── freebase-rdf-latest-desc-s02-c01
            ├── freebase-rdf-latest-desc-en-s02-c01
            └── freebase-rdf-latest-desc-[ISO lang...]-s02-c01
        └── freebase-rdf-latest-name-s02-c01
            ├── freebase-rdf-latest-name-en-s02-c01
            └── freebase-rdf-latest-desc-[ISO lang...]-s02-c01
        └── freebase-rdf-latest-type-s02-c01
            └── freebase-rdf-latest-type-[type...]-s02-c01
```

## Data Slices

Data Slice | Size | Triples
--- | --- | ---
All | 213G | 3,130,753,066 - 100%
*slices* | - | -
name | 4G | 72,699,101 - 2.32%
desc | 8G | 20,472,070 - 0.653%
type | 15G | 266,321,867 - 8.50%
akas | 305M | 4,611,150 - 0.147%
keys | 13G | 146,583,100 - 4.68%
*uniques* | - | -
pred | 23M | 784,977

## Schema








