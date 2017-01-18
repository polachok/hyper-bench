# hyper-bench

```
$ ./wrk -d1m -c10000 -t8 --latency http://127.0.0.1:1337/planets.json                               
 
Running 1m test @ http://127.0.0.1:1337/planets.json
  8 threads and 10000 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     1.88ms    1.70ms  36.94ms   84.76%
    Req/Sec    63.30k    27.00k  110.63k    49.99%
  Latency Distribution
     50%    1.42ms
     75%    2.44ms
     90%    3.92ms
     99%    8.04ms
  30228679 requests in 1.00m, 234.74GB read
  Socket errors: connect 8987, read 0, write 0, timeout 0
Requests/sec: 502998.62
```

# cpu
```
vendor_id       : GenuineIntel
cpu family      : 6
model           : 63
model name      : Intel(R) Xeon(R) CPU E5-2680 v3 @ 2.50GHz
stepping        : 2
microcode       : 0x2e
cpu MHz         : 1387.109
cache size      : 30720 KB
physical id     : 0
siblings        : 24
core id         : 13
cpu cores       : 12
apicid          : 27
initial apicid  : 27
fpu             : yes
fpu_exception   : yes
cpuid level     : 15
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf eagerfpu pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid dca sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm ida arat epb pln pts dtherm tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid cqm xsaveopt cqm_llc cqm_occup_llc
bugs            :
bogomips        : 5000.35
clflush size    : 64
cache_alignment : 64
address sizes   : 46 bits physical, 48 bits virtual
power management:

```
