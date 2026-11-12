# HTTPS SSL

## 0. World Wide Web

This project covers DNS configuration and subdomain management.

### DNS Records

The following subdomains are configured:

- www.fmuhire.tech
- lb-01.fmuhire.tech
- web-01.fmuhire.tech
- web-02.fmuhire.tech

### Script: 0-world_wide_web

The Bash script displays DNS information about subdomains.

Usage:

```bash
./0-world_wide_web domain
./0-world_wide_web domain subdomain
```

The script uses:
- `dig` to retrieve DNS records.
- `awk` to extract DNS information.
- A Bash function to display subdomain details.
