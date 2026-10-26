### Hugo Burton

*[English version](README.md)*

Développeur junior à Montmédy (France), tout près des frontières luxembourgeoise et belge. J'ai appris à
coder au secondaire, à l'UNamur et à l'école 19 (réseau 42), et je continue d'apprendre en construisant
des outils dont je me sers tous les jours, sur du matériel que je gère moi-même. Je cherche un premier
poste de développeur au Luxembourg ou en Belgique.

#### Parcours

- **Secondaire, option informatique** (diplôme en 2021). Stage d'un mois chez **LuxScan** : un outil Python
  pour trier des images à la main et repérer les défauts du bois avant la découpe.
- **Computech** : un mois de vente, de diagnostic et de réparation de PC.
- **UNamur, première année d'informatique** (2021–2022) : [alpha-omega](https://git.huburton.com/huburton/alpha-omega),
  un jeu de stratégie de loups-garous dans le terminal, avec une IA, réalisé à quatre.
- **École 19, réseau 42** (2024–2026) : C et Unix, de la réécriture de la libc jusqu'à un shell et un raycaster.
- **Électronique et fabrication** : une imprimante 3D montée en profilés d'aluminium à 16 ans, un distributeur
  de croquettes connecté, un relevé de chaudière à quatre sondes avec sa propre carte et son boîtier
  imprimé, des projets de LED avec des cartes ESP.
- **Auto-hébergement et IA locale** : un serveur maison avec une vingtaine de services Docker, des LLM locaux
  sur deux GPU, et un poste Arch Linux que je configure jusqu'à la chaîne de démarrage.

#### Projets

| Projet | Ce que c'est | Technologies |
|---|---|---|
| [huburton-os](https://git.huburton.com/huburton/huburton-os) | La plateforme web que j'utilise tous les jours : une discussion avec mes agents IA et les tâches qu'ils mènent, le suivi des tâches en cours, un planning synchronisé dans les deux sens avec Google Agenda, une médiathèque. Mode démo avec de fausses données. | Astro, React, Bun, Hono, Docker |
| [job-scout](https://git.huburton.com/huburton/job-scout) | Agent de recherche d'emploi : il collecte des offres publiques, en extrait les faits avec un LLM local (JSON contraint par une grammaire), applique des filtres vérifiés sur pièces, note et prévient. Démo hors ligne. | Python, SQLite, llama.cpp |
| [jarvis](https://git.huburton.com/huburton/jarvis) | Assistant vocal local en français : mot d'éveil, Whisper, LLM local, outils avec niveaux de permission et confirmation à voix haute. Démo en texte, sans micro. | Python, faster-whisper, llama.cpp |
| [homelab](https://git.huburton.com/huburton/homelab) | Mon serveur maison et mon IA locale décrits en code : piles Docker derrière Caddy et Cloudflare Tunnel, llama.cpp sur deux GPU. | Docker, Caddy, Cloudflare, Tailscale |
| [dotfiles](https://git.huburton.com/huburton/dotfiles) | Mon poste Arch Linux : Hyprland configuré en Lua avec un test de 155 vérifications, un shader contre les franges colorées des écrans QD-OLED, une session qui se répare seule, des mises à jour qui vérifient l'image noyau signée, un double démarrage avec Secure Boot. | Lua, QML, Bash, GLSL |
| [claude-qg](https://git.huburton.com/huburton/claude-qg) | Comment je fais tourner Claude Code en poste permanent : il délègue à des sessions ouvrières et me prévient par un seul canal, selon l'urgence. | Claude Code, MCP, Bun, TypeScript |
| [Distributeur_Croquettes](https://git.huburton.com/huburton/Distributeur_Croquettes) | Distributeur de croquettes connecté : mon firmware et mon électronique, dans un boîtier imprimé d'après un modèle MakerWorld. Repas programmés depuis Home Assistant, portion réglable, bouton physique. | ESP8266, ESPHome, Home Assistant |

#### École 19 (réseau 42)

[Cub3D](https://git.huburton.com/huburton/CUB3D) (raycaster, en binôme) · [Minishell](https://git.huburton.com/huburton/Minishell) (shell façon bash, en binôme) ·
[Philosophers](https://git.huburton.com/huburton/Philosophers) · [PushSwap](https://git.huburton.com/huburton/PushSwap) ·
[Fdf](https://git.huburton.com/huburton/Fdf) · [Minitalk](https://git.huburton.com/huburton/Minitalk) ·
[libft](https://git.huburton.com/huburton/libft) · [ft_printf](https://git.huburton.com/huburton/ft_printf) ·
[get_next_line](https://git.huburton.com/huburton/get_next_line)

#### Ma façon de travailler

J'utilise des assistants de code IA (surtout Claude Code) comme les développeurs ont toujours utilisé Stack
Overflow, les pages de manuel et le code des autres : comme des outils. Je décide de l'architecture, je relis
ce qui est écrit, et je peux expliquer chaque choix fait dans ces dépôts.
