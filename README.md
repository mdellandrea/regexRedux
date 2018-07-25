# Regex Redux Benchmark
Go-based Regex Redux benchmark using native [pcre](https://github.com/mdellandrea/golang-pkg-pcre) regular expressions. This program uses [fasta output](https://benchmarksgame-team.pages.debian.net/benchmarksgame/program/fasta-go-3.html) as its input and can be built and run with the following commands:

```
$ go build -o rr regexRedux.go
$ ./rr < regexReduxInput.txt
```

This is an optimization on the winning Regex Redux program at [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/program/regexredux-go-2.html). In local testing it outperforms the winning version. This version can be found [here](https://benchmarksgame-team.pages.debian.net/benchmarksgame/program/regexredux-go-4.html).
