A PPA repository for package:

- [PAL-USB](https://github.com/DreamVu/PAL-USB)

# Usage

```bash
curl -SsL "https://debashish05.github.io/debashishPPA/KEY.gpg" | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/my_list_file.list "https://debashish05.github.io/debashishPPA/my_list_file.list"
sudo apt update
sudo apt install palusb
```

# Sources

- https://dreamvu.com/
- https://github.com/DreamVu/