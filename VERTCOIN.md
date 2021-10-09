
# Mine Vertcoin + Zil with Team Black Miner

## LINUX
Currently we do not have Vertcoin algorithm support for Team Black Miner.

We have to merge the code from SPMiner and it will be included in version 2.0.

So if you want to mine Vertcoin + Zil you must dualmine with SPMiner and Team Black Miner.

SPMiner for Vertcoin sleeps in the Zil POW window while TBMiner works at Zil.

First time you run SPMiner it will generate the **verthash.dat** file neccesary.

Keep this file so you have it in the folder at the next run.

Filesize is about 1.3 GB.

Get SPMiner from:
* https://github.com/sp-hash/SPMiner/releases

And copy the executable into this folder.

Run SPMiner and Team Black Miner in paralell with two terminal windows.

One for SPMiner:

```bash
$ ./start_vtc_miningpoolhub+zil.sh
```

(Or you can use the **start_vtc_hashalot+zil.sh** start script)

And one for TBMiner:

```bash
$ ./tbminer_shardpool_zil.sh
```