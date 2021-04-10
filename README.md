#### HOW TO USE (UBUNTU TERMINAL)
- `sudo su`
- `apt-get install -y mame-tools libutf8proc-dev`
- `cd "directory"`
- `for i in *.cue; do chdman createcd -i "$i" -o "${i%.*}.chd"; done`
