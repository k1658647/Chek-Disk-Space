# Chek-Disk-Space
bash <(wget -q -O- https://raw.githubusercontent.com/Yasher/scripts/main/huge_dirs.sh)   du -hx --max-depth=20 / | grep "[[:digit:]]\.*G"
