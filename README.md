# ⏱️ General Benchmarks

Repository containing benchmarks organized by tech and discussions around it. The benchmarks are not limited to a single programming language, or even to a single framework and are focused on general purpose.

## Benchmark Format

Each benchmark will be composing by the following parts:

- Briefly explanation about the benchmark objective
- Code that was used to gather the benchmark information
- Benchmark results table with data extracted from the code execution

> [!IMPORTANT]  
> Benchmark methods can vary from benchmark to benchmark and will try to use the most reliable possible tools.
> Some benchmarks, mainly the specialized ones, are affected by cold starts and other variables so the methods
> used in them may also vary. We have a curated list of methods and tecniques that can be used to create a benchmark
> and it is listed below. It's important to note that the list can also vary with future updates.

| Tool                                                     | Link                                      |
| -------------------------------------------------------- | ----------------------------------------- |
| hyperfine - a command line benchmarking tool             | https://github.com/sharkdp/hyperfine      |
| BenchmarkDotNet - powerful .net library for benchmarking | https://github.com/dotnet/BenchmarkDotNet |
| performance.now() - Node.js core library                 | -                                         |

## Contributing

You can contribute with meaningful benchmarks, fixes and suggestions to see a detailed information about contrbuting, click [here](./CONTRIBUTING.md).

> [!TIP]
> Take care about you submissions, meaningful and concise benchmarks are valued and too sparse submissions won't be accepted. Try to explain the objective
> of the benchmark clearly.

> [!CAUTION]
> Benchmarks that depends on libraries, frameworks, external apis or any kind of dependency that is not present in the base runtime won't be accepted.

# Summary

<img src="https://static-00.iconduck.com/assets.00/dotnet-icon-2048x2048-6nj1im30.png" align="left" width="50"> <h2>Dotnet</h2>
<img src="https://seeklogo.com/images/N/nodejs-logo-D26404F360-seeklogo.com.png?v=638179441440000000" align="left" width="50"> <h2>Node.js</h2>

- [Test Hello World Benchmark](./benchmarks/javascript/nodejs/test-hello-world/benchmark.md)
