# 👨🏻‍💻 [Hang Liu](https://h4ng.dev) [@h6ng](https://h4ng.dev)

[![GitHub followers](https://img.shields.io/github/followers/h6ng?label=Follow&style=social)](https://github.com/h6ng/?tab=follow)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/h4ng/)](https://www.linkedin.com/in/h4ng/)
[![Gmail Badge](https://img.shields.io/badge/-hglu@student.ubc.ca-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:hglu@student.ubc.ca)](mailto:hglu@student.ubc.ca)
[![Website Badge](https://img.shields.io/badge/-h4ng.dev-c14438?style=social&logo=Google-Chrome&logoColor=red&link=https://h4ng.dev)](https://h4ng.dev)

[![ProfileViews](https://komarev.com/ghpvc/?username=h6ng&color=red&style=flat)](https://komarev.com/ghpvc/?username=h6ng)

:wave: Hello! I'm a Computer Engineering student at **UBC** (BASc, Co-op, expected May 2028), working across the stack from RISC-V assembly and FPGA firmware up to PyTorch models and React frontends. I like problems that sit close to the metal — timer interrupts, framebuffers, memory-mapped I/O — and I like problems that are just hard search problems in disguise, like chess engines and event-driven trading systems. I care about correctness, latency, and building things end-to-end rather than gluing together pretrained parts.

📍 Vancouver, BC — **available Fall 2026 / Winter 2027 for 4, 8, or 12-month co-op**, looking for firmware/hardware or software engineering roles.

<!-- START OF PROFILE STACK, DO NOT REMOVE -->
| 💻 **Technology** | 🚀 **Projects** |
| - | - |
| [![C++](https://img.shields.io/static/v1?label=&message=C%2B%2B&color=00599C&logo=C%2B%2B&logoColor=FFFFFF)](https://isocpp.org/) | [![NECAI](https://img.shields.io/static/v1?label=&message=NECAI%20(Chess%20Engine)&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/necai) [![IamP](https://img.shields.io/static/v1?label=&message=IamP&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/iamp) |
| [![C](https://img.shields.io/static/v1?label=&message=Embedded%20C&color=A8B9CC&logo=C&logoColor=FFFFFF)](https://en.cppreference.com/w/c) | [![Tron](https://img.shields.io/static/v1?label=&message=tron-fpga-vga&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/tron-fpga) |
| [![SystemVerilog](https://img.shields.io/static/v1?label=&message=SystemVerilog&color=1A5F9C&logo=verilog&logoColor=FFFFFF)](https://ieeexplore.ieee.org/document/8299595) | [![FPGA](https://img.shields.io/static/v1?label=&message=RISC--V%20FPGA%20labs&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng) |
| [![Python](https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=Python&logoColor=FFFFFF)](https://www.python.org/) | [![QuantFlow](https://img.shields.io/static/v1?label=&message=QuantFlow&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/quantflow) |
| [![PyTorch](https://img.shields.io/static/v1?label=&message=PyTorch&color=EE4C2C&logo=PyTorch&logoColor=FFFFFF)](https://pytorch.org/) | [![IamP](https://img.shields.io/static/v1?label=&message=ResNet%20from%20scratch&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/iamp) [![NNUE](https://img.shields.io/static/v1?label=&message=neural%20eval&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/necai) |
| [![React](https://img.shields.io/static/v1?label=&message=React&color=61DAFB&logo=React&logoColor=FFFFFF)](https://react.dev/) | [![NECAI UI](https://img.shields.io/static/v1?label=&message=necai--web&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/necai) |
| [![SQL](https://img.shields.io/static/v1?label=&message=SQL&color=4479A1&logo=PostgreSQL&logoColor=FFFFFF)](https://www.postgresql.org/) | [![Relational DB](https://img.shields.io/static/v1?label=&message=coursework&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng) |
| [![Shell](https://img.shields.io/static/v1?label=&message=Shell&color=4EAA25&logo=GNU%20Bash&logoColor=FFFFFF)](https://www.gnu.org/) | [![dotfiles](https://img.shields.io/static/v1?label=&message=dotfiles&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/h6ng/dotfiles) |
<!-- END OF PROFILE STACK, DO NOT REMOVE -->

### 🔧 Selected Projects

**[Tron Game (FPGA + VGA)](https://github.com/h6ng/tron-fpga)** — `Embedded C`, `RISC-V`, `JTAG UART`
Real-time light-cycle game on a RISC-V FPGA platform. Timer-interrupt-driven game loop, framebuffer VGA rendering, memory-mapped I/O, collision detection, autonomous opponent movement, and 7-segment score tracking. Debugged over JTAG UART with Quartus and ModelSim.

**[NECAI — Chess Engine](https://github.com/h6ng/necai)** — `C++`, `PyTorch`, `React`
Minimax with alpha-beta pruning and quiescence search to depth 4 — **1800+ Elo at 0.44s average search time**. Classical evaluator (material, piece-square tables, pawn structure, king safety) running ~50K nodes/sec, plus a PyTorch neural evaluator trained on ~50M Stockfish-labeled positions (depth ≥ 18) with a Tanh-calibrated scalar output.

**[IamP — Image Processing & Labelling](https://github.com/h6ng/iamp)** — `C++`, `Python`, `PyTorch`, `CUDA`
ResNet implemented from scratch rather than fine-tuned from torchvision, targeting 94-class alphanumeric classification. End-to-end pipeline: pattern detection → automated cropping → label assignment, eliminating manual annotation. Trained across the CS department RTX 3070 server and Colab T4, managing checkpoint portability between environments.

**[QuantFlow — Autonomous Financial Agent](https://github.com/h6ng/quantflow)** — `Python`, `asyncio`, `EC2`
Event-driven trading system over WebSockets: ~120 events/sec at ~18ms decision latency. Modular strategy engine supporting 3 strategies, ~2× throughput gain from async processing, +5% return over a 7-day simulation with ~12% max drawdown.

### 🛠 Toolbox

**Languages** — SystemVerilog · C · C++ · RISC-V Assembly · Python · Java · SQL · TypeScript · Bash
**Hardware & EDA** — FPGA · Quartus · ModelSim/Questa · UVM · JTAG · waveform debugging
**Protocols** — UART · SPI · QSPI · I2C
**Software** — PyTorch · OpenCV · React · FastAPI · Flask · Docker · PostgreSQL · MongoDB · Supabase · Git · Linux
**Testing** — JUnit · Pytest

### 🏆 Beyond Code

- 🎯 **Hackathons** — 4+ across Quebec and Vancouver; top 4 of 50+ teams for a real-time mobile object detection system for visually impaired navigation (~90% accuracy, 15–30 FPS on-device)
- ⚡ **IEEE UBC Student Branch** — Event Planner Specialist; 3+ events, 100+ attendees, team of 5+ volunteers
- 📚 **Tutorax** — Private math and French tutor since July 2024; 5+ students, up to 20% measured score improvement
- ♟️ Chess (~1800 Elo) · 🏀 UBC Intramural Basketball
- 🌍 French (Native) · English (Fluent) · Mandarin (Intermediate) · Spanish (Intermediate)

<div>
    <img src="https://cultofthepartyparrot.com/parrots/hd/githubparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/opensourceparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/databaseparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/scienceparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/laptop_parrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/fixparrot.gif" width="36" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/asyncparrot.gif" width="36" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/exceptionallyfastparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/60fpsparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/stableparrot.gif" width="30" height="30"/>
</div>
