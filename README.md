<div align="center">

```
███████╗██╗   ██╗██╗     ███████╗██╗██╗  ██╗███████╗██████╗
╚══███╔╝██║   ██║██║     ██╔════╝██║██║ ██╔╝██╔════╝██╔══██╗
  ███╔╝ ██║   ██║██║     █████╗  ██║█████╔╝ █████╗  ██████╔╝
 ███╔╝  ██║   ██║██║     ██╔══╝  ██║██╔═██╗ ██╔══╝  ██╔══██╗
███████╗╚██████╔╝███████╗██║     ██║██║  ██╗███████╗██║  ██║
╚══════╝ ╚═════╝ ╚══════╝╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
```

### ML Infrastructure · GPU Programming · Systems Engineering

[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/aorko321/)
[![Codeforces](https://img.shields.io/badge/Codeforces-%231F8ACB.svg?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/broken_brain)
[![LeetGPU](https://img.shields.io/badge/LeetGPU-%2376B900.svg?style=for-the-badge&logo=nvidia&logoColor=white)](https://leetgpu.com/profile?display_name=aorko01)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shahir-bin-zulfiker-aorko-6ba990281/)
[![Medium](https://img.shields.io/badge/Medium-%23000000.svg?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@aorko321)
[![dev.to](https://img.shields.io/badge/dev.to-%230A0A0A.svg?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/aorko)

</div>

---

## `> whoami`

I build things close to the metal — GPU kernels, distributed training infrastructure, and systems software. I care about what happens at the layer most engineers treat as a black box: how memory moves, how schedulers make decisions, how kernels actually run on hardware.

Currently going deep on ML systems, GPU programming, and low-level systems (OS internals, networking, memory). Previously built full-stack apps; now I live in the backend.

---

## `> ls ./projects`

<table>
<tr>
<td width="50%" valign="top">

### 🔧 Distributed ML Task Scheduler
> *In Progress*

A cluster-level job scheduler for heterogeneous GPU environments.

- Users submit a training script + dataset via a **simple web UI** — the system handles the rest
- **VRAM & runtime estimation** across different GPU models before scheduling
- **Bin-packing**: multiple jobs share a single GPU when headroom allows, maximizing utilization
- **Checkpoint-based fault recovery**: if a node dies, the job resumes from last checkpoint
- **Job feedback**: users get stdout/stderr on completion or failure
- **Tech**: Python · Ray · Docker · Kubernetes · Prometheus

</td>
<td width="50%" valign="top">

### ⚡ Flash Attention in Triton
> *In Progress*

Implementing Flash Attention from scratch using **Triton GPU kernels**, then training **GPT-2** on top to validate correctness and benchmark real-world throughput.

- Tiled SRAM-based attention to avoid HBM round-trips
- Benchmarking against standard PyTorch attention
- End-to-end GPT-2 training to verify gradient correctness
- **Tech**: Triton · CUDA · PyTorch · Python

</td>
</tr>
</table>

---

## `> cat skills.txt`

<table>
<tr>
<td width="33%" valign="top">

**Languages**
```
Python      ████████████ proficient
C++         ████████████ proficient
Rust        █████░░░░░░░ learning
Go          █████░░░░░░░ learning
```

</td>
<td width="33%" valign="top">

**ML & GPU**
```
PyTorch         ✓ proficient
PyTorch DDP     ✓ proficient
CUDA            ✓ proficient
Triton          ✓ proficient
```

</td>
<td width="33%" valign="top">

**Infra**
```
Docker          ✓
Kubernetes      ✓
Ray             ✓
Prometheus      ✓
```

</td>
</tr>
<tr>
<td valign="top">

**Systems**
```
OS Internals    → active
Networking      → active
Memory Mgmt     → active
```

</td>
<td valign="top">

**Previously**
```
React / Django
PostgreSQL / MongoDB
Full-stack web
```

</td>
<td valign="top">

**DSA**
```
LeetCode grind
Codeforces
GPU puzzles @ LeetGPU
```

</td>
</tr>
</table>

---

## `> github --stats`

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=aorko01&theme=dark&hide_border=true&include_all_commits=false&count_private=false&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![](https://github-readme-streak-stats.herokuapp.com/?user=aorko01&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=aorko01&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

</div>

---

<div align="center">

[![](https://visitcount.itsvg.in/api?id=aorko01&icon=5&color=9)](https://visitcount.itsvg.in)

</div>
