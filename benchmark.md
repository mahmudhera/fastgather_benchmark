## Fastgather benchmark

```
sourmash scripts fastgather fecal_ref.sig gtdb-rs207.genomic.k51.zip -k 51 -o test_fastgather.csv
```

```
User time (seconds): 290938.79
System time (seconds): 828.88
Percent of CPU this job got: 16207%
Elapsed (wall clock) time (h:mm:ss or m:ss): 30:00.23
Average shared text size (kbytes): 0
Average unshared data size (kbytes): 0
Average stack size (kbytes): 0
Average total size (kbytes): 0
Maximum resident set size (kbytes): 15759492
Average resident set size (kbytes): 0
Major (requiring I/O) page faults: 27
Minor (reclaiming a frame) page faults: 10614288
Voluntary context switches: 2602641
Involuntary context switches: 1290597
Swaps: 0
File system inputs: 28624
File system outputs: 1640
Socket messages sent: 0
Socket messages received: 0
Signals delivered: 0
Page size (bytes): 4096
Exit status: 0
```

##  Our gather
```
gather fecal_ref.sig filelist_gtdb_rs207_genomic_k_51 my_gather_output -t 128
```
```
Command being timed: "gather fecal_ref.sig filelist_gtdb_rs207_genomic_k_51 my_gather_output -t 128"
        User time (seconds): 3183.60
        System time (seconds): 565.69
        Percent of CPU this job got: 875%
        Elapsed (wall clock) time (h:mm:ss or m:ss): 7:08.41
        Average shared text size (kbytes): 0
        Average unshared data size (kbytes): 0
        Average stack size (kbytes): 0
        Average total size (kbytes): 0
        Maximum resident set size (kbytes): 36026200
        Average resident set size (kbytes): 0
        Major (requiring I/O) page faults: 0
        Minor (reclaiming a frame) page faults: 16986189
        Voluntary context switches: 22320040
        Involuntary context switches: 77778
        Swaps: 0
        File system inputs: 45108112
        File system outputs: 504
        Socket messages sent: 0
        Socket messages received: 0
        Signals delivered: 0
        Page size (bytes): 4096
        Exit status: 0
```
