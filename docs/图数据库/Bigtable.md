# Bigtable
Bigtable是一款由Google公司开发的大规模分布式列存储系统，用于存储结构化的数据。它采用了类似于一个有序映射表（ordered map）的数据结构，其中每个row key可以对应多个column和timestamp，而column又被组织在column family中。

## Bigtable的特点

- 1.  高可扩展性：Bigtable可以处理PB级别的数据，并支持自动分片和负载均衡，以实现水平可扩展。
    
- 2.  高性能：Bigtable采用了基于索引的查询优化技术和缓存机制，可以实现高效的数据检索和处理操作。
    
- 3.  强大的复制和冗余：Bigtable使用多副本复制和故障转移等机制，以确保数据的可靠性和容错性。
    
- 4.  灵活的数据模型：Bigtable支持灵活的数据模型，可以处理不同类型的数据，如邮件、Web内容、日志等。
    
- 5.  具备ACID特性：Bigtable支持原子性、一致性、隔离性和持久性等ACID特性，确保数据的完整性和可靠性。
    

## 应用
Bigtable被广泛应用于Google内部以及互联网行业的各种场景中，例如谷歌搜索、谷歌地图、YouTube等。
