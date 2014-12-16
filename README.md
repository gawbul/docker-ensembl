docker-ensembl
==============

Dockerfile to create a container image with the EnsEMBL Perl APIs and tools installed

To pull from repository type:

```
docker pull gawbul/docker-ensembl
```

To build from source, first clone the repository using:

```
git clone git@github.com:gawbul/docker-ensembl.git
```

Then `cd docker-ensembl` and type:

```
docker build -t gawbul/docker-ensembl .
```

To run type:

```
docker run -it gawbul/docker-ensembl bash
```

To test EnsEMBL is working type:

```
perl $HOME/ensembl_test_db_conn.pl
```
