# Muta benchmark

## Requirement

- NodeJS >= 10

## Quick start

```shell
git clone https://github.com/homura/muta-benchmark.git
cd muta-benchmark
npm install
node index -d 5 http://127.0.0.1:8000/graphql
```

or install globally

```
git clone https://github.com/homura/muta-benchmark.git
cd muta-benchmark
npm install
npm link
muta-bench -d 5 http://127.0.0.1:8000/graphql
```

## Options

```
Options:
  -m --method [method]            HTTP method (default: "POST")
  -d --duration [duration]        number of second (default: 5)
  -g --gap [gap]                  muta's timeout_gap (default: 30)
  -c --connections [connections]  number of connection (default: 20)
  -h, --help                      output usage information
```
