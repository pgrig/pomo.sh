# pomo

A terminal pomodoro timer in plain bash, no dependencies.

```
pomo              # 25 min work, 5 min break, 15 min long break after 4 rounds
pomo 50 10        # custom intervals in minutes
pomo 90s 30s      # intervals in seconds
pomo 25 5 15 4    # work, break, long break, number of rounds
```

Keys: `p` — pause, `s` — skip the current stage, `q` — quit.

At the end of each stage you get a desktop notification (`notify-send`) and a sound (`canberra-gtk-play`). The timer works without them too.

## Install

```
git clone https://github.com/pgrig/pomo ~/Projects/pomo
ln -s ~/Projects/pomo/pomo ~/.local/bin/pomo
```
