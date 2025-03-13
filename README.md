## RocksDB: A Persistent Key-Value Store for Flash and RAM Storage

[![CircleCI Status](https://circleci.com/gh/facebook/rocksdb.svg?style=svg)](https://circleci.com/gh/facebook/rocksdb)

<<<<<<< HEAD RocksDB is developed and maintained by Facebook Database
Engineering Team. It is built on earlier work on
[LevelDB](HTTPS://GitHub.Com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com) ======= RocksDB is developed
and maintained by Facebook Database Engineering Team. It is built on earlier
work on [LevelDB](https://github.com/google/leveldb) by Sanjay Ghemawat
(sanjay@google.com) and Jeff Dean (jeff@google.com)

> > > > > > > 2873ea08ffd610d95750802e38b8cfd9627bdb25

This code is a library that forms the core building block for a fast key-value
server, especially suited for storing data on flash drives. It has a
Log-Structured-Merge-Database (LSM) design with flexible tradeoffs between
Write-Amplification-Factor (WAF), Read-Amplification-Factor (RAF) and
Space-Amplification-Factor (SAF). It has multi-threaded compactions, making it
especially suitable for storing multiple terabytes of data in a single database.

Start with example usage here:
https://github.com/facebook/rocksdb/tree/main/examples

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

## License

RocksDB is dual-licensed under both the GPLv2 (found in the COPYING file in the
root directory) and Apache 2.0 License (found in the LICENSE.Apache file in the
root directory). You may select, at your option, one of the above-listed
licenses.

## Funding

This project is funded through
[NGI0 Commons Fund](https://nlnet.nl/commonsfund), a fund established by
[NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) program. Learn more at the
[NLnet project page](https://nlnet.nl/project/Land).

| Land                                                                                                                                                   | PlayForm                                                                                                                                                    | NLnet                                                                                         | NGI0 Commons Fund                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="https://raw.githubusercontent.com/CodeEditorLand/Asset/refs/heads/Current/Logo/Land.svg" height="80px" alt="Land"  />](https://editor.land) | [<img src="https://raw.githubusercontent.com/PlayForm/Asset/refs/heads/Current/Logo/PlayForm.svg" height="80px" alt="PlayForm"  />](https://playform.cloud) | [<img width="240px" src="https://nlnet.nl/logo/banner.svg" alt="NLnet"  />](https://nlnet.nl) | [<img width="240px" src="https://nlnet.nl/image/logos/NGI0CommonsFund_tag_black_mono.svg" alt="NGI0 Commons Fund"  />](https://nlnet.nl/commonsfund) |
