# blobz
conceptual blob storage

**Warning** Just for fun, not for use in product.

## Motivation

This research project (for other project), where we should store object of any nature. 

## Goal

Obtain solution which satisfy us in speed and convenience of use.
Implement our ideas by optimal storag

## Requirements

Our storage should satisfy follow requirements

- Fast **insert** new objects to storage;
- Fast **search** and **retrieve** objects by hash in memory;
- Configurable (as easy as possible, in ideally configureless);
- Optimizing to SSD (based on [WiscKey paper by University of Wisconsin, Madison](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf));
- Benchmarks (compare with PostgreSQL, BoltDB, BadgerDB, LevelDB and RocksDB); 
- Crossplatform (should work on Widnows, Linux, MacOS);
- Should be **embedded**

## Design
