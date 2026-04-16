# talk-ai

Make any LLM talk like an AI. A system prompt that adds AI slop.

## Usage

- **Quick start**: Visit [Sloppy](https://chatgpt.com/g/g-69e03e3e7bd48191b44e2cf430dc6324-sloppy) and chat with him
- **Integration**: Use [it](prompt.md) as your system prompt

## Examples

Question: "What is Python?"

<details><summary>Before (GPT-5.3, 998 chars)</summary>

[Share link](https://chatgpt.com/share/69e03c1b-d9f8-832f-a805-b8d3cdabf877)

> Python is a **high-level, interpreted programming language** designed for readability and rapid development.
>
> Key characteristics:
>
> * **Readable syntax**: uses indentation instead of braces, close to natural language
> * **Interpreted execution**: runs via an interpreter, no explicit compilation step required
> * **Dynamically typed**: variable types are determined at runtime
> * **Multi-paradigm**: supports procedural, object-oriented, and functional programming
> * **Extensive ecosystem**: rich standard library + packages (e.g., NumPy, PyTorch, Django)
>
> Typical use cases:
>
> * **Machine learning / data science** (NumPy, pandas, PyTorch)
> * **Web development** (Django, Flask, FastAPI)
> * **Automation / scripting**
> * **Systems integration and tooling**
>
> Minimal example:
>
> ```python
> def add(a, b):
>     return a + b
>
> print(add(1, 2))  # 3
> ```
> 
> Semantically, Python emphasizes developer productivity and expressiveness over low-level control, which is why it is widely used in research and prototyping.

</details>

<details><summary>After (GPT-5.3, 2978 chars)</summary>

[Share link](https://chatgpt.com/share/69e03c41-5e68-8327-9730-cf15fc6affcc)

> Great question—“What is Python?” sounds simple, but it’s one of those terms that means very different things depending on context, so let’s pin it down properly.
>
> ---
>
> ## 1. Not the snake, but a programming language
>
> Python is **not primarily the reptile**, and not just a scripting toy either—it’s a **high-level, general-purpose programming language** designed for readability and productivity.
>
> * It’s **not low-level like C** (where you manage memory manually)
> * It’s **not purely academic like some niche languages**
> * It’s **a practical, widely-used tool** for real-world software development
>
> ---
>
> ## 2. Core characteristics (what makes Python “Python”)
>
> ### • Readable syntax
>
> Python emphasizes code that looks almost like English:
>
> * Not cluttered with braces `{}` or semicolons `;`
> * But instead uses indentation to define structure
>
> 👉 In human terms: it’s designed so you can *read code like a story*, not decode symbols.
>
> ---
>
> ### • Interpreted, not compiled (in the traditional sense)
>
> * You don’t compile to machine code ahead of time like C++
> * Instead, Python runs via an interpreter
>
> 👉 Not about raw speed, but about **fast iteration and ease of use**
>
> ---
>
> ### • Dynamically typed
>
> * You don’t declare types explicitly (`int`, `float`, etc.)
> * Python figures it out at runtime
>
> 👉 Not rigid like Java, but flexible—sometimes at the cost of runtime errors
>
> ---
>
> ### • Multi-paradigm
>
> Python is:
>
> * Not only object-oriented
> * Not only functional
> * But supports **procedural, OOP, and functional styles**
>
> ---
>
> ## 3. What is Python used for?
>
> This is where Python really stands out—not narrow, but extremely broad:
>
> ### • Software development
>
> * Backend systems (e.g., Django, Flask)
>
> ### • Data science & AI
>
> * Libraries like NumPy, pandas, TensorFlow, PyTorch
>
> ### • Automation & scripting
>
> * File processing, web scraping, system tasks
>
> ### • Web development
>
> * APIs, servers, full-stack frameworks
>
> ### • Education
>
> * Often the **first language taught**, because it's simple
>
> 👉 Not specialized like MATLAB (scientific only), not system-level like Rust—**but a generalist that adapts**
>
> ---
>
> ## 4. Why is Python so popular?
>
> Let’s contrast:
>
> * It’s **not the fastest language** → but fast enough
> * It’s **not the most strict** → but very flexible
> * It’s **not the lowest-level** → but very productive
>
> So why use it?
>
> * Huge ecosystem (libraries for almost everything)
> * Strong community support
> * Rapid development speed
>
> 👉 In plain language: you trade a bit of performance for a lot of convenience.
>
> ---
>
> ## 5. A minimal mental model
>
> If you had to compress everything:
>
> * Python is **a tool for telling computers what to do**
> * But not in a rigid, machine-like way
> * Instead in a **human-readable, flexible style**
>
> ---
>
> ## 一句话总结
>
> Python 不是最快、也不是最底层的语言，而是一个以“易读、易写、用途广”为核心优势的通用编程语言。
>
> ---
>
> If you want, I can also:
>
> * Compare Python vs C++ / Java
> * Show a minimal example program
> * Or explain how Python actually runs internally (bytecode, interpreter, etc.)

</details>

## Credits

- [hexiecs/talk-normal](https://github.com/hexiecs/talk-normal/tree/main)
