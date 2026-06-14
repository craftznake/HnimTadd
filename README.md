```sh
$ cat << 'EOF' > craftznake.toml
[identity]
username       = "hnimtadd"
interested_in  = "building tools, optimizing things, and learning systems"
website        = "https://craftznake.space"
EOF

$ echo -e "Hi, I'm \n$(cat craftznake.toml)"
```
