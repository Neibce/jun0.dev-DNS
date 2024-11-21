# jun0.dev-DNS
 - **[jun0.dev](https://jun0.dev)'s DNS Records**
 - nameserver: Cloudflare (`dan.ns.cloudflare.com`, `kiki.ns.cloudflare.com`)

## Records

Type|Name|Content|Description
--|--|--|--
NS|jun0.dev.|dan.ns.cloudflare.com.|Cloudflare NS
NS|jun0.dev.|kiki.ns.cloudflare.com.|Cloudflare NS
A|jun0.dev.|34.82.127.251|GCP VM Instance
A|nas.jun0.dev.|61.76.50.99|Synology NAS at home (DDNS/Reverse Proxy)
CNAME|w<span>ww</span>.jun0.dev.|jun0.dev.|-
CNAME|mail.jun0.dev.|jun0.dev.|for Webmail Service (Reverse Proxy)
CNAME|drive.jun0.dev.|nas.jun0.dev.|Synology Drive Service (Reverse Proxy)
CNAME|photos.jun0.dev.|nas.jun0.dev.|Synology Photos Service (Reverse Proxy)
CNAME|ppp.jun0.dev.|nas.jun0.dev.|[PPlusPlus](https://github.com/Neibce/PNU-PPlusPlus)'s Server (Docker(Ubuntu)/Reverse Proxy)
MX|jun0.dev.|jun0.dev.|-

Type|Name|Content|Description
--|--|--|--
TXT|jun0.dev.|"google-site-verification=KOld..."|Google Search Console Verification
TXT|jun0.dev.|"v=spf1 include:spf.mailjet.com -all"|SPF for SMTP(Mailjet)
TXT|_dmarc.jun0.dev.|"v=DMARC1; p=quarantine; rua=mailto:y@jun0.dev"|DMARC
TXT|mail._domainkey.jun0.dev.|"v=DKIM1; h=sha256; k=rsa; t=y; p=MII..."|DKIM for jun0.dev
TXT|mailjet._domainkey.jun0.dev.|"k=rsa; p=MIG..."|DKIM for Mailjet
TXT|mailjet._b02dedc1.jun0.dev.|"b02dedc198102bb4e2486d07d50f7365"|Mailjet Verification



