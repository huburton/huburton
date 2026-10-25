### Hugo Burton

Junior developer in Montmédy (France), close to the Luxembourg and Belgian borders. I learned to code
at school, at UNamur and at School 19 (42 network), and I keep learning by building tools I use every
day, on hardware I run myself. Looking for a first developer job in Luxembourg or Belgium.

#### Path

- **Secondary school, computing option** (diploma 2021). One-month internship at **LuxScan**: a Python
  tool to sort images by hand and mark wood defects for cutting.
- **Computech**: one month of PC sales, diagnosis and repair.
- **UNamur, first year of computer science** (2021–2022): [alpha-omega](https://git.huburton.com/huburton/alpha-omega),
  a werewolf strategy game in the terminal with an AI, built in a team of four.
- **School 19, 42 network** (2024–2026): C and Unix, from a libc rewrite to a shell and a raycaster.
- **Electronics and making**: a 3D printer built from aluminium extrusions at 16, a connected pet feeder,
  a four-probe boiler monitor with its own board and printed case, LED projects with ESP boards.
- **Self-hosting and local AI**: a home server with about twenty Docker services, local LLMs on two GPUs,
  and an Arch Linux desktop I configure down to the boot chain.

#### Projects

| Project | What it is | Stack |
|---|---|---|
| [huburton-os](https://git.huburton.com/huburton/huburton-os) | The web platform I use every day: a chat with my AI agents and the jobs they run, live task tracking, a planning view synced both ways with Google Calendar, a media library. Demo mode with fake data. | Astro, React, Bun, Hono, Docker |
| [job-scout](https://git.huburton.com/huburton/job-scout) | Job-search agent: collects public offers, extracts facts with a local LLM (grammar-constrained JSON), applies evidence-checked filters, scores and notifies. Offline demo. | Python, SQLite, llama.cpp |
| [jarvis](https://git.huburton.com/huburton/jarvis) | Local French voice assistant: wake word, Whisper, local LLM, tools with permission levels and spoken confirmation. Text demo without a microphone. | Python, faster-whisper, llama.cpp |
| [homelab](https://git.huburton.com/huburton/homelab) | Infrastructure as code of my home server and local AI stack: Docker stacks behind Caddy and Cloudflare Tunnel, llama.cpp on two GPUs. | Docker, Caddy, Cloudflare, Tailscale |
| [dotfiles](https://git.huburton.com/huburton/dotfiles) | My Arch Linux desktop: Hyprland configured in Lua with a 155-check test, a shader for QD-OLED colour fringes, self-healing session, updates that check the signed kernel image, Secure Boot dual boot. | Lua, QML, Bash, GLSL |
| [claude-qg](https://git.huburton.com/huburton/claude-qg) | How I run Claude Code as an always-on hub that delegates to worker sessions and notifies me through one channel with an urgency policy. | Claude Code, MCP, Bun, TypeScript |
| [Distributeur_Croquettes](https://git.huburton.com/huburton/Distributeur_Croquettes) | Connected pet feeder: my firmware and electronics in a case printed from a MakerWorld model. Scheduled meals from Home Assistant, portion control, physical button. | ESP8266, ESPHome, Home Assistant |

#### School 19 (42 network)

[Cub3D](https://git.huburton.com/huburton/CUB3D) (raycaster, in a pair) · [Minishell](https://git.huburton.com/huburton/Minishell) (bash-like shell, in a pair) ·
[Philosophers](https://git.huburton.com/huburton/Philosophers) · [PushSwap](https://git.huburton.com/huburton/PushSwap) ·
[Fdf](https://git.huburton.com/huburton/Fdf) · [Minitalk](https://git.huburton.com/huburton/Minitalk) ·
[libft](https://git.huburton.com/huburton/libft) · [ft_printf](https://git.huburton.com/huburton/ft_printf) ·
[get_next_line](https://git.huburton.com/huburton/get_next_line)

#### How I work

I use AI coding assistants (mostly Claude Code) the way developers have always used Stack Overflow, man pages
and other people's snippets: as tools. I decide the architecture, review what gets written, and can explain
every choice in these repositories.
