## Project about Cryptocurrencies for Big Data course


#### About files and directories:

* `Create_hbase_tables.txt` - contains commands to be used to create tables in Apache HBase
* `create_hive_prices.txt` - commands that are executed via processors in NiFi to create tables in Hive, for data about prices
* `create_hive_symbols.txt` - commands that are executed via processors in NiFi to create tables in Hive, for data about symbols
* `data_from_hdfs_nifi.zip` - contains sample files downloaded from Binance exchange.
* `CryptocurrenciesExchangeComparison.xml` - final version of data flow in Apache NiFi, from API to saving to tables in Apache Hive and Apache HBase
* `PySpark for Hive final.ipynb` - notebook for analysis (with use of Apache Spark) of data stored in Apache Hive
* `PySpark_top5_vis.ipynb` - notebook for analysis (with use of Apache Spark) of data stored in Apache HBase

#### About hive tables:
  * `binance_old` - contains all records from binance 
  * `kucoin_old` - contains all records from kucoin
  * `binance_symbols` - contains all symbols of currencies available on binance
  * `kucoin_symbols` - contains all symbols of currencies available on kucoin
