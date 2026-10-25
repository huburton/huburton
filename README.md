### Hugo Burton

Junior developer in Montmédy (France), close to the Luxembourg and Belgian borders. I learned to code
at school, at UNamur and at School 19 (42 network), and I keep learning by building tools I use every
day, on hardware I run myself. Looking for a first developer job in Luxembourg or Belgium.

#### Path

- **Secondary school, computing option** (diploma 2021). One-month internship at **LuxScan**: a Python
  tool to sort images by hand and mark wood defects for cutting.
- **Computech**: one month of PC sales, diagnosis and repair.
- **UNamur, first year of computer science** (2021–2022): [alpha-omega](https://github.com/huburton/alpha-omega),
  a werewolf strategy game in the terminal, with an AI, for a team of four.
- **School 19, 42 network** (2024–2026): C and Unix, from a libc rewrite to a shell and a raycaster.
- **Electronics and making**: a 3D printer built from aluminium extrusions at 16, a connected pet feeder,
  a four-probe boiler monitor with its own board and printed case, LED projects with ESP boards.
- **Self-hosting and local AI**: a home server with about twenty Docker services, local LLMs on two GPUs,
  and an Arch Linux desktop I configure down to the boot chain.

#### Projects

| Project | What it is | Stack |
|---|---|---|
| [huburton-os](https://github.com/huburton/huburton-os) | Personal web "OS" in daily use: agenda with two-way Google Calendar sync, projects and tasks stored as Markdown in an Obsidian vault, media library, AI agent with tools. Demo mode with a fake vault. | Astro, React, Bun, Hono, Docker |
| [job-scout](https://github.com/huburton/job-scout) | Job-search agent: collects public offers, extracts facts with a local LLM (grammar-constrained JSON), applies evidence-checked filters, scores and notifies. Offline demo. | Python, SQLite, llama.cpp |
| [jarvis](https://github.com/huburton/jarvis) | Local French voice assistant: wake word, Whisper, local LLM, tools with permission levels and spoken confirmation. Text demo without a microphone. | Python, faster-whisper, llama.cpp |
| [homelab](https://github.com/huburton/homelab) | Infrastructure as code of my home server and local AI stack: Docker stacks behind Caddy and Cloudflare Tunnel, llama.cpp on two GPUs. | Docker, Caddy, Cloudflare, Tailscale |
| [dotfiles](https://github.com/huburton/dotfiles) | My Arch Linux desktop: Hyprland configured in Lua with a 155-check test, a shader for QD-OLED colour fringes, self-healing session, updates that check the signed kernel image, Secure Boot dual boot. | Lua, QML, Bash, GLSL |
| [claude-qg](https://github.com/huburton/claude-qg) | How I run Claude Code as an always-on hub that delegates to worker sessions and notifies me through one channel with an urgency policy. | Claude Code, MCP, Bun, TypeScript |
| [Distributeur_Croquettes](https://github.com/huburton/Distributeur_Croquettes) | Connected pet feeder: scheduled meals from Home Assistant, portion control, physical button, printed case. | ESP8266, ESPHome, Home Assistant |

#### School 19 (42 network)

[Cub3D](https://github.com/huburton/CUB3D) (raycaster, in a pair) · [Minishell](https://github.com/huburton/Minishell) (bash-like shell, in a pair) ·
[Philosophers](https://github.com/huburton/Philosophers) · [PushSwap](https://github.com/huburton/PushSwap) ·
[Fdf](https://github.com/huburton/Fdf) · [Minitalk](https://github.com/huburton/Minitalk) ·
[libft](https://github.com/huburton/libft) · [ft_printf](https://github.com/huburton/ft_printf) ·
[get_next_line](https://github.com/huburton/get_next_line)

#### How I work

I use AI coding assistants (mostly Claude Code) the way developers have always used Stack Overflow, man pages
and other people's snippets: as tools. I decide the architecture, review what gets written, and can explain
every choice in these repositories.
