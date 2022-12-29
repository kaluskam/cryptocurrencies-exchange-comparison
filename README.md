## Project about Cryptocurrencies for Big Data course


#### About files:

* `CryptoExchangeProject.xml` - get data from API of cryptocurrencies exchanges and convert into `avro` and `parquet` files.
* `CryptoExchangeHbaseCorrected.xml` - to above file, added HBase processing.
* `CryptoExchangeProjectSaveFiles.xml` - (from first file) get data from API of cryptocurrencies exchanges, convert into `avro` and `parquet` files, (added) saving to HDFS files: json, avro, parquet.
* `data_from_hdfs_nifi.zip` - contains sample files downloaded from Binance exchange. `Project` directory contains data generated in `CryptoExchangeProject.xml`, `projekt` contains sample data in formats json, avro, parquet.
* `processing_hive.txt` - file to be saved as hql to run saving orc files to hive table
* `CryptoExchangesApiRequesting.xml` - saving files as ORC from both Binance and KuCoin
* `CryptoDataUploadToHive.xml` - added upload to hive table
