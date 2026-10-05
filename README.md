# Furkan Yalçın

**Software engineering · C# / Unity · Backend systems**  
**Computer Engineering @ Istanbul Technical University**

I'm a Computer Engineering student at ITU, expecting to graduate in **June–July 2027**. I build gameplay systems with **C# and Unity**, and backend applications with **ASP.NET Core, Node.js and Python**. My work also includes **Semantic Kernel and MCP** integrations.

I like understanding how systems work, measuring bottlenecks and finding practical ways to solve problems.

[LinkedIn](https://www.linkedin.com/in/yalcin-furkan/) · [LeetCode](https://leetcode.com/u/FuYal/) · [LeetCode 2](https://leetcode.com/u/Kazarix/) · [Codeforces](https://codeforces.com/profile/Kekil)

## Featured project — Matchtoria

**C# · Unity 6 · DOTween · Domain-driven gameplay**

A **two-person match-3 game** built around a rich gameplay model, rather than placing game rules inside rendering components.

- **Domain-driven design:** board, tile and level objects hold gameplay state and behavior. Tile classes implement their own damage rules; `Level` owns move counts, objectives and win/lose decisions.
- **Command-based animation:** `BoardModel` resolves swaps and cascades into timestamped commands. `BoardView` plays them through DOTween, with timed callbacks that align objective updates with tile destruction.
- **Capability-based tile behavior:** `IMatchable`, `IMovable`, `IDamageable` and `ITriggerable` describe what a tile can do. Matching, falling and special-tile effects operate on the gameplay model rather than sprites.
- **Gameplay algorithms:** post-swap matching scans the affected rows and columns, while cascade resolution handles further matches, obstacle-aware falling and board refills.

[Source code](https://github.com/yalcinfu22/Matchtoria) · [Architecture walkthrough](https://github.com/yalcinfu22/Matchtoria/blob/main/docs/architecture.md) · [Gameplay demo](https://github.com/yalcinfu22/Matchtoria#matchtoria)

## Other selected projects

| Project | What to explore | Technologies |
| --- | --- | --- |
| [Chatify](https://github.com/yalcinfu22/Chatify) | Real-time messaging, authentication and a repository-pattern backend | Node.js, Express, Socket.IO, MongoDB, React |
| [Basic Computer](https://github.com/yalcinfu22/Basic-Computer) | A CPU implementation with an ALU, control unit, memory and simulation testbenches | Verilog |
| [GetHere](https://github.com/yalcinfu22/GetHere) | A food-delivery application with customer, courier and manager workflows | Python, Flask, MySQL |

**Teamwork:** Matchtoria and Basic Computer were two-person projects; GetHere was a five-person project. Project READMEs include more context and contributor information.

## What I work with

- **Gameplay:** C#, Unity, DOTween, domain-driven design principles
- **Backend:** ASP.NET Core, Node.js, Express, REST APIs, Socket.IO
- **AI integrations:** Semantic Kernel, Model Context Protocol (MCP), retrieval-augmented generation (RAG)
- **Languages:** C#, C/C++, Python, Java, JavaScript
- **Data and tools:** MySQL, MongoDB, Git, Docker, Postman
- **Also explored:** VHDL, Verilog, MATLAB and digital design

## Looking ahead

I'm interested in gameplay and backend systems, performance and reliable software. I'm open to **part-time software engineering opportunities while studying** and **graduate roles from July 2027**, including relocation within Europe and remote opportunities.
