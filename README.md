#!MANAGED-CONFIG http://127.0.0.1:25500/sub?target=surfboard&url=vmess%3A%2F%2FeyJob3N0IjoiIiwicGF0aCI6IlwvdjJyYXkiLCJ0bHMiOiIiLCJhZGQiOiIwMTA1dHcuZmFuczgueHl6IiwicG9ydCI6ODAsImFpZCI6MiwibmV0Ijoid3MiLCJ0eXBlIjoibm9uZSIsInYiOiIyIiwicHMiOiLlj7Dmub4xLeS4iee9keS8mOWMliIsImlkIjoiNzgzMTQwY2MtMDY4MS0zY2U5LTk5OWItOGI1MmNmNDg2MWQ1In0%3D&insert=false&config=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FSleepyHeeead%2Fsubconverter-config%40master%2Fremote-config%2Fspecial%2Fbasic.ini interval=86400 strict=false

[General]
loglevel = notify
interface = 127.0.0.1
skip-proxy = 127.0.0.1, 192.168.0.0/16, 10.0.0.0/8, 172.16.0.0/12, 100.64.0.0/10, localhost, *.local
ipv6 = false
dns-server = system, 223.5.5.5
exclude-simple-hostnames = true
enhanced-mode-by-rule = true

[Proxy]
DIRECT = direct
台湾1-三网优化 = vmess, 0105tw.fans8.xyz, 80, username=783140cc-0681-3ce9-999b-8b52cf4861d5, tls=false, ws=true, ws-path=/v2ray, sni=0105tw.fans8.xyz, ws-headers=Host:0105tw.fans8.xyz, skip-cert-verify=true, tfo=false, udp-relay=true

[Proxy Group]
Proxies = select,台湾1-三网优化
