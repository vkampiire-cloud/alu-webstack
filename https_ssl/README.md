# HTTPS & SSL Project

This directory contains solutions for the **HTTPS SSL** project in the ALX/ALU Webstack curriculum.

## Tasks

| File | Description |
| --- | --- |
| `0-world_wide_web` | Bash script that audits DNS records for subdomains (`www`, `lb-01`, `web-01`, `web-02`) using `dig` and `awk`. |
| `1-haproxy_ssl_termination` | HAProxy configuration file serving HTTPS traffic on port 443 with SSL termination and round-robin load balancing. |
| `2-redirect_http_to_https` | HAProxy configuration file enforcing HTTPS by redirecting all HTTP port 80 traffic to HTTPS with a 301 status code. |
