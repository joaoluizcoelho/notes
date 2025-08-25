# Guia de Recon — Fontes de Pesquisa OSINT

Este documento lista algumas URLs e serviços para coletar informações sobre um site/domínio específico durante a fase de **Reconnaissance** em segurança ofensiva.  
Substitua `example.com` pelo domínio alvo.

---

## 🔐 Certificados e Subdomínios

- **crt.sh (Certificados TLS)**
  - [https://crt.sh/?q=example.com](https://crt.sh/?q=example.com)
  - Útil para descobrir subdomínios e histórico de certificados SSL/TLS.

- **Censys (Infraestrutura da Internet)**
  - [https://search.censys.io/certificates?q=example.com](https://search.censys.io/certificates?q=example.com)
  - [https://search.censys.io/hosts?q=example.com](https://search.censys.io/hosts?q=example.com)
  - Pesquisa por certificados, hosts e serviços expostos.

- **Cert Spotter**
  - [https://sslmate.com/certspotter/api/v1/issuances?domain=example.com](https://sslmate.com/certspotter/api/v1/issuances?domain=example.com)  
  - Alternativa ao `crt.sh`.

---

## 🌐 Exposição de Serviços

- **Shodan**
  - [https://www.shodan.io/search?query=example.com](https://www.shodan.io/search?query=example.com)
  - Pesquisa de serviços e banners de IPs relacionados.

- **Hunter.io (Emails)**
  - [https://hunter.io/search/example.com](https://hunter.io/search/example.com)  
  - Descobre e-mails corporativos relacionados a um domínio.

- **Spyse (Recon Avançado)**
  - [https://spyse.com/search?query=example.com](https://spyse.com/search?query=example.com)

---

## 📡 DNS e WHOIS

- **DNSdumpster**
  - [https://dnsdumpster.com/](https://dnsdumpster.com/)
  - Descobre registros DNS e possíveis subdomínios.

- **ViewDNS.info**
  - Reverse IP Lookup: [https://viewdns.info/reverseip/?host=example.com&t=1](https://viewdns.info/reverseip/?host=example.com&t=1)
  - Whois Lookup: [https://viewdns.info/whois/?domain=example.com](https://viewdns.info/whois/?domain=example.com)

- **Whois.domaintools**
  - [https://whois.domaintools.com/example.com](https://whois.domaintools.com/example.com)

---

## 📊 Históricos e Crawlers

- **Wayback Machine**
  - [https://web.archive.org/web/*/example.com](https://web.archive.org/web/*/example.com)
  - Histórico de páginas e endpoints antigos.

- **SecurityTrails**
  - [https://securitytrails.com/domain/example.com](https://securitytrails.com/domain/example.com)  
  - Informações de DNS, histórico de IPs e subdomínios.

- **BuiltWith**
  - [https://builtwith.com/example.com](https://builtwith.com/example.com)  
  - Tecnologias utilizadas no site.

---

## 📥 Dumps e Credenciais Vazadas

- **Have I Been Pwned**
  - [https://haveibeenpwned.com/domain/example.com](https://haveibeenpwned.com/domain/example.com)
  - Checa se emails do domínio aparecem em vazamentos.

- **Dehashed**
  - [https://www.dehashed.com/search?query=example.com](https://www.dehashed.com/search?query=example.com)
  - Pesquisa por senhas, e-mails e leaks associados.

---

# ✅ Observações
- Combinar resultados de diferentes fontes aumenta a cobertura do recon.

