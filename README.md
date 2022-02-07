# Dynamic Analysis Tools
> An ongoing & curated collection of awesome vulnerability scanning software, libraries and frameworks, best guidelines and technical resources and most important dynamic application security testing (DAST)


## What is Dynamic Analysis?
[Dynamic analysis](https://www.intel.com/content/www/us/en/develop/documentation/inspector-user-guide-windows/top/getting-started/dynamic-analysis-vs-static-analysis.html) is the testing and evaluation of an application during runtime.

The primary advantage of dynamic analysis: It reveals subtle defects or vulnerabilities whose cause is too complex to be discovered by static analysis. Dynamic analysis can play a role in security assurance, but its primary goal is finding and debugging errors.

## Table of Contents

#### [Programming Languages](#programming-languages-1)

<details>
 <summary>Show languages</summary>
  <!-- Please use HTML syntax here so that it works for Github and mkdocs -->
  <ul>
    <li><a href="#dotnet">.NET</a></li>
    <li><a href="#c">C</a></li>
    <li><a href="#cpp">C++</a></li>
    <li><a href="#java">Java</a></li>
    <li><a href="#javascript">JavaScript</a></li>
    <li><a href="#php">PHP</a></li>
    <li><a href="#python">Python</a></li>
    <li><a href="#ruby">Ruby</a></li>
    <li><a href="#rust">Rust</a></li>
    <li><a href="#sql">SQL</a></li>
    <li><a href="#vbasic">Visual Basic</a></li>
    </ul>
</details>

#### [Multiple languages](#multiple-languages-1)

#### [Other](#other-1)

- [API](#api)
  - [Binaries](#binary)
  - [Bytecode/IR](#bytecode)
  - [Containers](#container)
  - [Laravel](#laravel)
  - [Security/DAST](#security)
  - [Web](#web)
  - [WebAssembly](#webassembly)
  - [XML](#xml)
  

---

## Programming Languages

<h2 id="dotnet">.NET</h2>

- [Microsoft IntelliTest](https://docs.microsoft.com/en-us/visualstudio/test/intellitest-manual/getting-started?view=vs-2019) — Generate a candidate suite of tests for your .NET code.
- [Pex and Moles](https://www.microsoft.com/en-us/research/project/pex-and-moles-isolation-and-white-box-unit-testing-for-net/) — Pex automatically generates test suites with high code coverage using automated white box analysis.


<h2 id="c">C</h2>

- [CHAP](https://github.com/vmware/chap) — Analyzes un-instrumented ELF core files for leaks, memory growth, and corruption. It helps explain memory growth, can identify some forms of corruption, and  supplements a debugger by giving the status of various memory locations.
- [KLEE](https://github.com/klee/klee) — Symbolic virtual machine built on top of the LLVM compiler infrastructure.
- [LDRA](https://ldra.com) :copyright: — A tool suite including dynamic analysis and test to various standards can ensure test coverage to 100% op-code, branch & decsion coverage.
- [LLVM/Clang Sanitizers](https://github.com/google/sanitizers) — <ul> <li><a href="https://github.com/google/sanitizers/wiki/AddressSanitizer">AddressSanitizer</a> - A memory error detector for C/C++</li> <li><a href="https://github.com/google/sanitizers/wiki/MemorySanitizer">MemorySanitizer</a> - A detector of uninitialized memory reads in C/C++ programs.</li> <li><a href="https://github.com/google/sanitizers/wiki/ThreadSanitizerCppManual">ThreadSanitizer</a> - A data race detector for C/C++</li> </ul>
- [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) — An interpreter for finding subtle bugs in programs written in standard C.
- [Valgrind](https://valgrind.org/) — An instrumentation framework for building dynamic analysis tools.


<h2 id="cpp">C++</h2>

- [CHAP](https://github.com/vmware/chap) — Analyzes un-instrumented ELF core files for leaks, memory growth, and corruption. It helps explain memory growth, can identify some forms of corruption, and  supplements a debugger by giving the status of various memory locations.
- [KLEE](https://github.com/klee/klee) — Symbolic virtual machine built on top of the LLVM compiler infrastructure.
- [LDRA](https://ldra.com) :copyright: — A tool suite including dynamic analysis and test to various standards can ensure test coverage to 100% op-code, branch & decsion coverage.
- [LLVM/Clang Sanitizers](https://github.com/google/sanitizers) — <ul> <li><a href="https://github.com/google/sanitizers/wiki/AddressSanitizer">AddressSanitizer</a> - A memory error detector for C/C++</li> <li><a href="https://github.com/google/sanitizers/wiki/MemorySanitizer">MemorySanitizer</a> - A detector of uninitialized memory reads in C/C++ programs.</li> <li><a href="https://github.com/google/sanitizers/wiki/ThreadSanitizerCppManual">ThreadSanitizer</a> - A data race detector for C/C++</li> </ul>
- [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) — An interpreter for finding subtle bugs in programs written in standard C.
- [Valgrind](https://valgrind.org/) — An instrumentation framework for building dynamic analysis tools.


<h2 id="java">Java</h2>

- [Java PathFinder](https://github.com/javapathfinder/jpf-core) — An extensible software model checking framework for Java bytecode programs.
- [Parasoft Jtest](https://www.parasoft.com/products/jtest) :copyright: — Jtest is an automated Java software testing and static analysis product that is made by Parasoft. The product includes technology for Data-flow analysis Unit test-case generation and execution, static analysis, regression testing, code coverage, and runtime error detection.


<h2 id="javascript">JavaScript</h2>

- [Iroh.js](https://github.com/maierfelix/Iroh) — A dynamic code analysis tool for JavaScript. Iroh allows to record your code flow in realtime, intercept runtime informations and manipulate program behaviour on the fly.
- [Jalangi2](https://github.com/Samsung/jalangi2) — Jalangi2 is a popular framework for writing dynamic analyses for JavaScript.


<h2 id="php">PHP</h2>

- [Enlightn](https://www.laravel-enlightn.com/) — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.


<h2 id="python">Python</h2>

- [CrossHair](https://github.com/pschanely/CrossHair) — Symbolic execution engine for testing Python contracts.
- [icontract](https://github.com/Parquery/icontract) — Design-by-contract library supporting behavioral subtyping
There is also a wider tooling around the icontract library such as  a linter (pyicontract-lint) and a plug-in for Sphinx (sphinx-icontract).
- [Scalene](https://github.com/emeryberger/scalene) — A high-performance, high-precision CPU and memory profiler for Python
- [typo](https://github.com/aldanor/typo) — Runtime Type Checking for Python 3.


<h2 id="ruby">Ruby</h2>

- [suture](https://github.com/testdouble/suture) — A Ruby gem that helps you refactor your legacy code  by the result of some old behavior with a new version.


<h2 id="rust">Rust</h2>

- [loom](https://github.com/tokio-rs/loom) — Concurrency permutation testing tool for Rust.  It runs a test many times, permuting the possible concurrent executions of that test.
- [MIRI](https://github.com/rust-lang/miri) — An interpreter for Rust's mid-level intermediate representation, which can detect certain classes of undefined behavior like out-of-bounds memory accesses and use-after-free.
- [puffin](https://github.com/EmbarkStudios/puffin) — Instrumentation profiler for Rust.
- [stuck](https://github.com/jonhoo/stuck) — provides a visualization for quickly identifying common bottlenecks in running, asynchronous, and concurrent applications.


<h2 id="sql">SQL</h2>

- [WhiteHat Sentinel Dynamic](https://www.whitehatsec.com/products/dynamic-application-security-testing/) :copyright: — Part of the WhiteHat Application Security Platform. Dynamic application security scanner that covers the OWASP Top 10.


<h2 id="vbasic">Visual Basic</h2>

- [VB Watch](https://www.aivosto.com/vbwatch.html) :copyright: — Profiler, Protector and Debugger for VB6. Profiler measures performance and test coverage. Protector implements robust error handling. Debugger helps monitor your executables.


## Multiple languages

- [Code Pulse](http://code-pulse.com/) — Code Pulse is a free real-time code coverage tool for penetration testing activities by OWASP and Code Dx ([GitHub](https://github.com/codedx/codepulse)).
- [Gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html) — GNU source code coverage program. Code coverage tool and profiling tool which is part of the GCC. Supports C, C++, Fortran.


## Other



<h2 id="api">API</h2>

- [Smartbear](https://smartbear.com/) :copyright: — Test automation and performance testing platform


<h2 id="binary">Binaries</h2>

- [angr](https://github.com/angr/angr) — Platform agnostic binary analysis framework from UCSB.
- [BOLT](https://github.com/facebookincubator/BOLT) — Binary Optimization and Layout Tool - A linux command-line utility used for optimizing performance of binaries  with profile guided permutation of linking to improve cache efficiency
- [Dr. Memory](https://drmemory.org/) — Dr. Memory is a memory monitoring tool capable of identifying memory-related programming errors ([Github](https://github.com/DynamoRIO/drmemory)).
- [DynamoRIO](http://www.dynamorio.org/) — Is a runtime code manipulation system that supports code transformations on any part of a program, while it executes.
- [llvm-propeller](https://github.com/google/llvm-propeller) — Profile guided hot/cold function splitting to improve cache efficiency. An alternative to BOLT by Facebook
- [Pin Tools](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) — A dynamic binary instrumentation tool and a platform for creating analysis tools.
- [TRITON](https://triton.quarkslab.com/) — Dynamic Binary Analysis for x86 binaries.


<h2 id="bytecode">Bytecode/IR</h2>

- [souper](https://github.com/google/souper) — optimize LLVM IR with SMT solvers


<h2 id="container">Containers</h2>

- [cadvisor](https://github.com/google/cadvisor) — Analyzes resource usage and performance characteristics of running containers.


<h2 id="laravel">Laravel</h2>

- [Enlightn](https://www.laravel-enlightn.com/) — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.


<h2 id="security">Security/DAST</h2>

- [AppScan Standard](https://www.hcltechsw.com/products/appscan) :copyright: — HCL's AppScan is a dynamic application security testing suite ([previously by IBM](https://newsroom.ibm.com/2018-12-06-HCL-Technologies-to-Acquire-Select-IBM-Software-Products-for-1-8B)).
- [Enlightn](https://www.laravel-enlightn.com/) — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.
- [WebScanner](https://www.defensecode.com/web-security-scanner-dast/) :copyright: — WebScanner is a DAST solution for comprehensive security audits of active web applications.
- [WhiteHat Sentinel Dynamic](https://www.whitehatsec.com/products/dynamic-application-security-testing/) :copyright: — Part of the WhiteHat Application Security Platform. Dynamic application security scanner that covers the OWASP Top 10.
- [Full OWASP / Vulnerability Scanners](https://github.com/paulveillard/cybersecurity-dynamic-analysis/blob/main/dynamic-application-security-testing.md)


<h2 id="web">Web</h2>

- [Smartbear](https://smartbear.com/) :copyright: — Test automation and performance testing platform


<h2 id="webassembly">WebAssembly</h2>

- [Wasabi](https://github.com/danleh/wasabi) — Wasabi is a framework for writing dynamic analyses for WebAssembly, written in JavaScript.


<h2 id="xml">XML</h2>

- [WhiteHat Sentinel Dynamic](https://www.whitehatsec.com/products/dynamic-application-security-testing/) :copyright: — Part of the WhiteHat Application Security Platform. Dynamic application security scanner that covers the OWASP Top 10.

**[`^        back to top        ^`](#)**

## License
MIT License & [cc](https://creativecommons.org/licenses/by/4.0/) license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

To the extent possible under law, [Paul Veillard](https://github.com/paulveillard/) has waived all copyright and related or neighboring rights to this work.


