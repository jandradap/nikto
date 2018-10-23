# nikto

[![](https://images.microbadger.com/badges/image/jorgeandrada/nikto:latest.svg)](https://microbadger.com/images/jorgeandrada/nikto:latest "Get your own image badge on microbadger.com")[![](https://images.microbadger.com/badges/version/jorgeandrada/nikto:latest.svg)](https://microbadger.com/images/jorgeandrada/nikto:latest "Get your own version badge on microbadger.com")[![](https://images.microbadger.com/badges/commit/jorgeandrada/nikto:latest.svg)](https://microbadger.com/images/jorgeandrada/nikto:latest "Get your own commit badge on microbadger.com")

**Nikto with ansi2html**

```
docker run --rm -it jorgeandrada/nikto -host www.example.org -port 443 -ssl
docker run --rm -it jorgeandrada/nikto -host www.example.org
docker run --rm -it -v $PWD/output:/tmp/nikto jorgeandrada/nikto -host www.example.org -p 80 -Format htm -output /tmp/nikto/example.html
```

<a href='https://ko-fi.com/A417UXC' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
