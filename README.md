# cracked
run/john mypasswd --show | cut -d':' -f2 | head -n -2 > cracked/cracked

run/john mypasswd -w=cracked/cracked
