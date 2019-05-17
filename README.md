# Gorgparse

## sleep.go

```bash
./sleep
```

```bash
[-c|--count] is required
usage: print [-h|--help] -c|--count <integer> [-d|--delay <float>]

             Simple example of argparse flags

Arguments:

  -h  --help   Print help information
  -c  --count  Number of iterations to count
  -d  --delay  Delay between iterations. Default: 1
```

```bash
./sleep -c 10
```

```bash
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4
Iteration: 5
Iteration: 6
Iteration: 7
Iteration: 8
Iteration: 9
Iteration: 10
```

```bash
./sleep -c 10 -d 0.1
```

```bash
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4
Iteration: 5
Iteration: 6
Iteration: 7
Iteration: 8
Iteration: 9
Iteration: 10
```

## command.go 

```bash
./command
```

```bash
[sub]Command required
usage: commands <Command> [-h|--help]

                Simple example of argparse commands

Commands:

  start  Will start a process
  stop   Will stop a process

Arguments:

  -h  --help  Print help information
```

```bash
./command start
```

```bash
Started process
```

```bash
./command stop
```

```bash
Stopped process
```
