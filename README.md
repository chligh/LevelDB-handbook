# LevelDB-handbook

## Architecture
### LSM-Tree
The core storage architecture of LevelDB is a log-structured merge tree (LSM), It is optimized for large sequential writes as opposed to small random writes.
![](./image/lsm_tree.png)
### Components
- log
- memtable
- immutable memtable
- sstable

## SSTable: Sorted String Table
![](./image/sstable1.png)
![](./image/sstable2.png)
![](./image/sstable3.png)
