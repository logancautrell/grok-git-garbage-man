# Grok Git Garbage Man (GGM) 🌀

**The futuristic Git garbage collector with live cyberdeck animations.**

Built live on an M4 Max MacBook Pro with Grok. One command keeps your `.git` folder lean forever — no history rewrite, safe for company upstreams and PRs.

### Installation (one-liner)
```bash
mkdir -p ~/bin && curl -fsSL https://raw.githubusercontent.com/logancautrell/grok-git-garbage-man/main/ggm -o ~/bin/ggm && chmod +x ~/bin/ggm
```

### Usage
```bash
cd /path/to/your/repo
~/bin/ggm              # full purge
~/bin/ggm --dry-run    # simulate without making any changes
~/bin/ggm --status     # show .git bloat info without pruning
~/bin/ggm --help       # show usage
```

### Cron example (monthly cleanup)
```bash
30 3 1 * * cd /your/repo/path && ~/bin/ggm
```

### In Action

![Example](https://github.com/user-attachments/assets/98186d1d-f643-43c1-8a38-a04f6c744143)


Made with ❤️ in Minnesota by Logan + Grok 4.20 beta.
Star it if it saves you space. Issues & PRs welcome!
