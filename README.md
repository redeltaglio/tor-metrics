# Tor Metrics :: [yui.cat](https://yui.cat/) source

Network-oriented Tor metrics and statistics made with love (not javascript)

```bash
# Requirements: python3, jinja2 (pip install jinja2)

git clone https://github.com/tempname1024/tor-metrics.git
cd tor-metrics/tor-metrics
python3 generate.py

# Files are written to www/ by default
```

```
TODO:
* Top exit/guard/relay families (see https://nusenu.github.io/OrNetStats/)
* Interesting statistics (ASN exit concentration, IPv6-supporting relays, etc)
* Implement something similar to https://metrics.torproject.org/bubbles.html
```

This project includes country flags by [GoSquared](https://github.com/gosquared/flags) and relay flags by the [Tor Project](https://www.torproject.org/).

