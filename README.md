# dotfiles

Personal configuration files synced across machines.

## Setup

Clone and symlink on each machine:

```bash
git clone git@github.com:natolambert/dotfiles.git ~/dotfiles

# Claude Code settings
mkdir -p ~/.claude
ln -sf ~/dotfiles/.claude/settings.json ~/.claude/settings.json
```

## Contents

- `.claude/settings.json` - Claude Code global permissions
