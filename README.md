# Eduardo Furlan's Notes

My random personal notes that I collect over time, on the most varied subjects, such as design and implementation of language, theory, internals, high performance processing, computer architecture, machine learning, programming, books, links, tips and tricks, curiosities and others.

<table>
    <tr>
        <td><img src="img/construction.gif"></td>
        <td>This website and repositories are permanently under construction, so its contents change constantly.</td>
    </tr>
</table>

## Blog

I keep a personal blog containing short random notes that I collect over time on the most varied subjects. Use the menu to access.


## Selected topics

Some selected notes. There are several others on the blog or in the menu. (not ordered)

* [Python](python/README.md) - my personal notes on Python-related topics that I find interesting.
* [Moving Forth](Moving_Forth/README.md) - my personal notes on Brad Rodriguez's Moving Forth.
* [Fortran](fortran/README.md) - page with my personal notes about Fortran, a high -level programming language that is historically linked to HPC due to its efficient handling of numerical and scientific calculations. Its syntax and resources are optimized for high performance, making it ideal for large-scale simulations and mathematical models in scientific research. Consequently, Fortran remains a basic item in the HPC community for his incomparable computational efficiency.
* [C](c/README.md) - page with my Personal Notes on C Language, which has efficiency and ability to directly manipulate hardware resources, allowing optimized performance for intensive computing tasks. Its low-level operations and portability make it a favorite language for the development of high-speed scalable HPC applications.
* [HPC](https://github.com/efurlanm/hpc) - repository containing my personal notes on High-Performance Computing (HPC). Efficient language design and implementation are crucial for HPC because they directly impact the performance, scalability, and usability of HPC applications. Languages designed specifically for HPC, such as domain-specific languages (DSLs), can optimize parallelism, manage complex computations, and provide abstractions that simplify the development of high-performance code. Additionally, well-designed compilers and interpreters for these languages can further enhance performance by optimizing code execution on HPC systems.
* [Compilers course](https://github.com/efurlanm/teaching/tree/main/comp) (in Portuguese) - lecture notes from the course I teach.


## Vintage computer

Vintage computer internals, or "computer archeology". The first personal computers were designed with both the operating system and programming language embedded in Read-Only Memory (ROM). This integration allowed users to power on the machine and immediately start programming without the need for additional software installation. This seamless access was crucial during the early days of computing, as it enabled users to interact directly with the hardware and develop software efficiently. The built-in programming languages, often BASIC, provided a user-friendly environment for both novice and experienced programmers, making these early computers a significant step in the democratization of computing technology.

* Applesoft ROM internals [[1](http://www.txbobsc.com/scsc/scdocumentor)] [[2](https://6502disassembly.com/a2-rom)]
* TRS-80 ROM internals [[1](https://www.trs-80.com/wordpress/roms/)]
* C64 ROM internals [[1](https://www.pagetable.com/c64ref/c64disasm)] [[2](https://github.com/tgiphil/c64rom)]
* The Complete Spectrum ROM Disassembly [[1](https://archive.org/details/CompleteSpectrumROMDisassemblyThe)]
* Spectrum ROM Disassemblies [[1](https://github.com/ZXSpectrumVault/rom-disassemblies)]
* Altair BASIC Annotated Disassembly [[1](http://altairbasic.org)]
* HP-41 internals [[1](blog/posts/2024/hp41.md)] (link to my blog post)


## Selected books & papers

* [A Construção de um Compilador](buildcomp.md) (Building a Compiler), by VW Setzer & ISH Melo - page with my personal notes about the book.
* [Threaded Interpretive Languages: Their Design and Implementation](https://vdoc.pub/documents/threaded-interpretive-languages-their-design-and-implementation-1seph9gct7uo), by RG Loeliger - explores the principles and architecture of [threaded interpretive languages](https://en.wikipedia.org/wiki/Threaded_code), with a specific focus on Forth-like languages. The book provides practical examples in assembly language and discusses various implementation techniques. It serves as a comprehensive guide for understanding and creating efficient interpreters.
* [Threaded code designs for Forth interpreters](https://dl.acm.org/doi/10.1145/146559.146561), by PJ Hong - techniques for implementing threaded code in Forth interpreters. It classifies these techniques to better understand the mechanisms underlying threaded interpretive languages (TILs) and discusses elements such as thread-codes, primitives, secondaries, and the interpreter's instruction pointer and return stack.
* [Library](https://vdoc.pub/search/compiler) with several books on compilers, computers, and programming.


## Forums

* [Reddit Programming Languages](http://www.reddit.com/r/ProgrammingLanguages) - discussion of programming languages, programming language theory, design, their syntax and compilers.
* [Reddit Compilers](http://www.reddit.com/r/Compilers) - community where people discuss topics related to compiler design, construction, and theory. It's a great place to find resources, ask questions, and share knowledge about compilers.
* [comp.compilers newsgroup](https://compilers.iecc.com) - forum within Usenet dedicated to discussions about compiler design, implementation, and usage. It serves as a platform for experts, enthusiasts, and learners to share knowledge, ask questions, and collaborate on projects related to compilers. Topics often include discussions on compiler construction, optimization techniques, language design, and the challenges faced in developing efficient compilers.


## Wikibooks & Wikipedia

* [Compiler](https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering/Tools/Compiler) - from the book *Introduction to Software Engineering*. Overview of compilers, explaining how they transform source code written in a high-level programming language into machine code or another lower-level language. It also covers the various stages of compilation, including lexical analysis, parsing, semantic analysis, code generation, and optimization.
* [Compiler Construction](https://en.wikibooks.org/wiki/Compiler_Construction) - provides a detailed guide on the theory and practice of compiler construction, including lexical analysis, parsing, semantic analysis, optimization, and code generation.
* [Compiler](https://en.wikipedia.org/wiki/Compiler) - in-depth overview of compilers, which are programs that translate source code written in a high-level programming language into machine code, assembly code, or an intermediate code.
* [History of compiler construction](https://en.wikipedia.org/wiki/History_of_compiler_construction) - historical overview of the development of compilers from the early days of computer science to the modern era. It discusses key milestones, influential projects, and significant advancements in compiler technology over the years.
* [Threaded code](https://en.wikipedia.org/wiki/Threaded_code) - programming technique where the code consists primarily of subroutine calls. It is often used in compilers and interpreters to improve code density and execution efficiency, especially in systems with limited memory. The technique is known for its use in languages like Forth and early versions of BASIC.


## License

My work follows the CC-BY-4.0 license. The works of other authors follow their licenses.


<br><small>Last edited: 2024-12-14</small>
