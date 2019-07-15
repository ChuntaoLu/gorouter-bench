```
payload size: 16 bytes
HttpRouter mem usage: 39064 Bytes
ZanzibarRouter mem usage: 22080 Bytes
goos: darwin
goarch: amd64
pkg: github.com/ChuntaoLu/router-bench
BenchmarkHttpRouterWithGithubAPI-8       	   20000	     59506 ns/op	   33476 B/op	     501 allocs/op
BenchmarkZanzibarRouterWithGithubAPI-8   	   10000	    213361 ns/op	  171956 B/op	    2143 allocs/op
```
```
payload size: 128 bytes
HttpRouter mem usage: 41112 Bytes
ZanzibarRouter mem usage: 19936 Bytes
goos: darwin
goarch: amd64
pkg: github.com/ChuntaoLu/router-bench
BenchmarkHttpRouterWithGithubAPI-8       	   10000	    109214 ns/op	   78775 B/op	     501 allocs/op
BenchmarkZanzibarRouterWithGithubAPI-8   	   10000	    234084 ns/op	  217255 B/op	    2143 allocs/op
```
```
payload size: 1024 bytes
HttpRouter mem usage: 41112 Bytes
ZanzibarRouter mem usage: 19936 Bytes
goos: darwin
goarch: amd64
pkg: github.com/ChuntaoLu/router-bench
BenchmarkHttpRouterWithGithubAPI-8       	    5000	    291934 ns/op	  454584 B/op	     501 allocs/op
BenchmarkZanzibarRouterWithGithubAPI-8   	    5000	    349081 ns/op	  593063 B/op	    2143 allocs/op
```
```
payload size: 8192 bytes
HttpRouter mem usage: 37016 Bytes
ZanzibarRouter mem usage: 20032 Bytes
goos: darwin
goarch: amd64
pkg: github.com/ChuntaoLu/router-bench
BenchmarkHttpRouterWithGithubAPI-8       	     500	   2001240 ns/op	 4319744 B/op	     501 allocs/op
BenchmarkZanzibarRouterWithGithubAPI-8   	    1000	   2578558 ns/op	 4458371 B/op	    2143 allocs/op
```
```
payload size: 65536 bytes
HttpRouter mem usage: 37016 Bytes
ZanzibarRouter mem usage: 21984 Bytes
goos: darwin
goarch: amd64
pkg: github.com/ChuntaoLu/router-bench
BenchmarkHttpRouterWithGithubAPI-8       	     100	  18378088 ns/op	42963620 B/op	     501 allocs/op
BenchmarkZanzibarRouterWithGithubAPI-8   	     200	  18878448 ns/op	43107342 B/op	    2143 allocs/op
```