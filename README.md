### HOW TO RUN ###

    $ go get github.com/go-sql-driver/mysql
    $ go get github.com/gorilla/mux
    $ go get github.com/gorilla/sessions
    $ go get github.com/bradfitz/gomemcache/memcache
    $ go get github.com/pkg/profile
    $ go build -o app
    $ ./app


# prof top 
```
Showing top 10 nodes out of 147
      flat  flat%   sum%        cum   cum%
    3710ms 49.87% 49.87%     3710ms 49.87%  syscall.RawSyscall
     390ms  5.24% 55.11%      410ms  5.51%  sweepspan
     220ms  2.96% 58.06%      220ms  2.96%  runtime.memclr
     150ms  2.02% 60.08%      500ms  6.72%  runtime.MCentral_AllocList
     140ms  1.88% 61.96%      150ms  2.02%  runtime.settype_flush
     110ms  1.48% 63.44%      110ms  1.48%  runtime.markallocated
     100ms  1.34% 64.78%      650ms  8.74%  runtime.MCache_Alloc
      90ms  1.21% 65.99%      520ms  6.99%  cnew
      90ms  1.21% 67.20%     1320ms 17.74%  runtime.mallocgc
      80ms  1.08% 68.28%       80ms  1.08%  runtime.memmove
```

