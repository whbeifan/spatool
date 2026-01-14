# spatool
Staphylococcus aureus spa typing tool

## Third-party
-----------

spatool relies on third-party software
* [blast](https://blast.ncbi.nlm.nih.gov/doc/blast-help/downloadblastdata.html)

## Installation
```
#git clone https://github.com/whbeifan/spatool.git
wget -c https://github.com/whbeifan/spatool/archive/refs/heads/main.zip
chmod 755 spatool
spatool create_config #配置文件
spatool update_database #更新数据
```
## Quick usage
```
spatool run_spa run_spa A.fasta
spatool cut_target A.fasta --rprimer GACGATCCTTCAGTGAGCAAAG --fprimer GCAGCAATTTTGTCAGCAGTAG >need.fasta
```
