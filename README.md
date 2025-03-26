## RocksDB: A Persistent Key-Value Store for Flash and RAM Storage

[![CircleCI Status](https://circleci.com/gh/facebook/rocksdb.svg?style=svg)](https://circleci.com/gh/facebook/rocksdb)

<<<<<<< HEAD RocksDB is developed and maintained by Facebook Database
Engineering Team. It is built on earlier work on
[LevelDB](https://github.com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com)

This code is a library that forms the core building block for a fast key-value
server, especially suited for storing data on flash drives. It has a
Log-Structured-Merge-Database (LSM) design with flexible tradeoffs between
Write-Amplification-Factor (WAF), Read-Amplification-Factor (RAF) and
Space-Amplification-Factor (SAF). It has multi-threaded compactions, making it
especially suitable for storing multiple terabytes of data in a single database.
======= <<<<<<< HEAD RocksDB is developed and maintained by Facebook Database
Engineering Team. It is built on earlier work on
[LevelDB](https://github.com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com)

This code is a library that forms the core building block for a fast key-value
server, especially suited for storing data on flash drives. It has a
Log-Structured-Merge-Database (LSM) design with flexible tradeoffs between
Write-Amplification-Factor (WAF), Read-Amplification-Factor (RAF) and
Space-Amplification-Factor (SAF). It has multi-threaded compactions, making it
especially suitable for storing multiple terabytes of data in a single database.
======= <<<<<<< HEAD RocksDB is developed and maintained by Facebook Database
Engineering Team. It is built on earlier work on
[LevelDB](HTTPS://GitHub.Com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com) ======= RocksDB is developed
and maintained by Facebook Database Engineering Team. It is built on earlier
work on [LevelDB](https://github.com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com)

> > > > > > > 2873ea08ffd610d95750802e38b8cfd9627bdb25
> > > > > > > 6079a3362ce1f080b4a0e0082b8a30ed36bc86b2
> > > > > > > e1cbc1594d448147ea7845b68d148a552cc73167

Start with example usage here:
https://github.com/facebook/rocksdb/tree/main/examples

See the [github wiki](https://github.com/facebook/rocksdb/wiki) for more
explanation.

<<<<<<< HEAD The public interface is in `include/`. Callers should not include
or rely on the details of any other header files in this package. Those internal
APIs may be changed without warning.

# Questions and discussions are welcome on the [RocksDB Developers Public](https://www.facebook.com/groups/rocksdb.dev/) Facebook group and [email list](https://groups.google.com/g/rocksdb) on Google Groups.

<<<<<<< HEAD The public interface is in `include/`. Callers should not include
or rely on the details of any other header files in this package. Those internal
APIs may be changed without warning.

# Questions and discussions are welcome on the [RocksDB Developers Public](https://www.facebook.com/groups/rocksdb.dev/) Facebook group and [email list](https://groups.google.com/g/rocksdb) on Google Groups.

<<<<<<< HEAD See the [github wiki](HTTPS://GitHub.Com/facebook/rocksdb/wiki) for
more explanation. ======= See the
[github wiki](https://github.com/facebook/rocksdb/wiki) for more explanation.

> > > > > > > 2873ea08ffd610d95750802e38b8cfd9627bdb25

The public interface is in `include/`. Callers should not include or rely on the
details of any other header files in this package. Those internal APIs may be
changed without warning.

Questions and discussions are welcome on the
[RocksDB Developers Public](https://www.facebook.com/groups/rocksdb.dev/)
Facebook group and [email list](https://groups.google.com/g/rocksdb) on Google
Groups.

> > > > > > > 6079a3362ce1f080b4a0e0082b8a30ed36bc86b2
> > > > > > > e1cbc1594d448147ea7845b68d148a552cc73167

## License

RocksDB is dual-licensed under both the GPLv2 (found in the COPYING file in the
root directory) and Apache 2.0 License (found in the LICENSE.Apache file in the
root directory). You may select, at your option, one of the above-listed
licenses.
