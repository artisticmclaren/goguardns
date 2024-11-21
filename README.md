# GoGuarDNS
an exploit to remove GoGuardian from a school managed chroembook for people who dont have access to custom DNS on the school wifi

Requirements:
- Chromebook
- ability to connect to different networks on the chroembooks
- a phone
- mobile data / hotspot (infinite is preferable as it is nicer to use)

1. Install NextDNS on your phone
2. open the website, log in, and add a blocklist with these links:
waluigi.goguardian.com
snat.goguardian.com
ip.goguardian.com
hosted-extensions.goguardian.com
blocked.goguardian.com
goguardian.com
3. get the id from the setup page and add it as the custom profile in NextDNS
4. connect to hotspot while logging in
5. if the school wifi tries to reconnect quickly go back to the hotspot
6. profit