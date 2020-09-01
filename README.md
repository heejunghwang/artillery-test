# Artillery test

Artillery is a stress test library. This repo has sample code with artillery library.

# How to run

```
yarn && yarn test
```

The result will be like this. (sample result)

```
Started phase 0 (Warm up), duration: 5s @ 22:09:32(+0900) 2020-09-01
Started phase 1 (Sustained max load), duration: 10s @ 22:09:38(+0900) 2020-09-01
Report @ 22:09:42(+0900) 2020-09-01
Elapsed time: 10 seconds
  Scenarios launched:  237
  Scenarios completed: 237
  Requests completed:  237
  Mean response/sec: 24.36
  Response time (msec):
    min: 1
    max: 3.4
    median: 1.6
    p95: 2.4
    p99: 3.3
  Codes:
    200: 237

Report @ 22:09:48(+0900) 2020-09-01
Elapsed time: 16 seconds
  Scenarios launched:  118
  Scenarios completed: 118
  Requests completed:  118
  Mean response/sec: 18.58
  Response time (msec):
    min: 1.1
    max: 3.8
    median: 1.4
    p95: 2.4
    p99: 3.6
  Codes:
    200: 118

All virtual users finished
Summary report @ 22:09:48(+0900) 2020-09-01
  Scenarios launched:  355
  Scenarios completed: 355
  Requests completed:  355
  Mean response/sec: 22.02
  Response time (msec):
    min: 1
    max: 3.8
    median: 1.5
    p95: 2.4
    p99: 3.4
  Scenario counts:
    0: 355 (100%)
  Codes:
    200: 355
```

## Reference

- https://artillery.io/