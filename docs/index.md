---
hide:
    - toc
    - navigation
---
## Introduction

Valkey is an open-source data store platform that can be used as a database, cache, and event streaming engine. It specifically focuses on serving requests with low latency; hence, it is designed to work in memory rather than on disk.

Although the disk is not used for its active operations, because of the volatile nature of the memory, it is used to persist the data in the event that it is not frequently used, but it requires long-term storage as it may be accessed later.


Valkey currently supports the following data types:

<div class="grid cards" markdown>

-  __String__

    ---

    It stores a sequence of bytes up to 512MB.

    [:octicons-arrow-right-24: Overview](en/data-types/string.md)

-   __List__

    ---

    It stores list of strings by insertion order.

    [:octicons-arrow-right-24: Overview](en/data-types/list.md)

-  __Set__

    ---

    It stores unordered collections of unique strings.

    [:octicons-arrow-right-24: Overview](en/data-types/set.md)


-   __Sorted Set__

    ---

    It stores ordered collections of unique strings.

    [:octicons-arrow-right-24: Overview](en/data-types/sorted-set.md)

-  __Hash__

    ---

    It stores collections of field-value pairs.

    [:octicons-arrow-right-24: Overview](en/data-types/hash.md)

-   __HyperLogLog__

    ---

    It stores the cardinality of a set.

    [:octicons-arrow-right-24: Overview](en/data-types/hyperloglog.md)

-  __Bitmap__

    ---

    It performs set of bitwise operations on strings.

    [:octicons-arrow-right-24: Overview](en/data-types/bitmap.md)


-   __Bitfield__

    ---

    It stores integer values of arbitrary bit length.

    [:octicons-arrow-right-24: Overview](en/data-types/bitfield.md)

-  __Geospatial__

    ---

    It stores geographic coordinates and search for them.

    [:octicons-arrow-right-24: Overview](en/data-types/geospatial.md)

-   __Stream__

    ---

    It stores the data in the append-only log fashion.

    [:octicons-arrow-right-24: Overview](en/data-types/stream.md)

-   __JSON__

    ---

    It stores JSON values.

    [:octicons-arrow-right-24: Overview](en/data-types/json.md)

-  __Time Series__

    ---

    It stores time series data.

    [:octicons-arrow-right-24: Overview](en/data-types/time-series.md)


-   __Bloom Filter__

    ---

    It checks for presence of an element in a set.

    [:octicons-arrow-right-24: Overview](en/data-types/bloom-filter.md)

-  __Cuckoo Filter__

    ---

    It checks for presence of an element in a set of buckets.

    [:octicons-arrow-right-24: Overview](en/data-types/cuckoo-filter.md)


-  __Top-K__

    ---

    It allows you to find the most frequent items in a data stream.

    [:octicons-arrow-right-24: Overview](en/data-types/top-k.md)


-   __T-Digest__

    ---

    It allows you to estimate the percentile of a data stream.

    [:octicons-arrow-right-24: Overview](en/data-types/t-digest.md)

-   __Count-min Sketch__

    ---

    It estimates the frequency of an element in a data stream.

    [:octicons-arrow-right-24: Overview](en/data-types/count-min-sketch.md)

-   __Pub/Sub__

    ---

    It stores the data in publish-subscribe messaging pattern.

    [:octicons-arrow-right-24: Overview](en/data-types/pub-sub.md)

</div>
