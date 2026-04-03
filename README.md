<p align="center">
  <img src="https://raw.githubusercontent.com/daemonintel/opsec-resources/main/assets/iLoveIMG.png" width="400">
</p>

<hr style="border: none; height: 1px; background-color: #30363d; opacity: 0.5; margin: 24px 0;">

<p align="center">
  <img src="https://img.shields.io/github/license/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/contributors/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/issues/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/discussions/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/forks/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/stars/daemonintel/osint-resources">
</p>

## OPSEC Resources

Repositório criado com o objetivo de compartilhar navegadores, extensões, sistemas operacionais e recursos voltados para privacidade, anonimato, segurança e OPSEC.

---

## Extensões - Firefox

- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) — bloqueador de conteúdo de amplo espectro, com foco em eficiência de CPU e memória.
- [uMatrix](https://addons.mozilla.org/en-US/firefox/addon/umatrix/) — controle total sobre conexões, downloads e execução de conteúdo no navegador.
- [Firefox Multi-Account Containers](https://addons.mozilla.org/pt-BR/firefox/addon/multi-account-containers/) — separa atividades online em contêineres isolados, mantendo cookies independentes.
- [NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/) — permite execução de scripts apenas em domínios confiáveis, mitigando vulnerabilidades exploráveis.
- [Tracking Token Stripper](https://addons.mozilla.org/en-US/firefox/addon/utm-tracking-token-stripper/) — remove parâmetros de rastreamento de URLs (UTM e similares).
- [Font Fingerprint Defender](https://addons.mozilla.org/en-US/firefox/addon/font-fingerprint-defender/) — mascara fingerprint de fontes com valores aleatórios.
- [Change Location](https://addons.mozilla.org/en-US/firefox/addon/change-geolocation-locguard/) — altera a localização geográfica reportada pelo navegador.
- [User-Agent Switcher and Manager](https://addons.mozilla.org/en-US/firefox/addon/user-agent-string-switcher/) — permite falsificar o user-agent do navegador.
- [WebGL Fingerprint Defender](https://addons.mozilla.org/en-US/firefox/addon/webgl-fingerprint-defender/) — oculta fingerprint WebGL com valores falsos.
- [AdNauseam](https://addons.mozilla.org/en-US/firefox/addon/adnauseam/) — ofusca padrões de navegação contra rastreamento publicitário.
- [Terms of Service; Didn’t Read](https://addons.mozilla.org/en-US/firefox/addon/terms-of-service-didnt-read/) — fornece resumos rápidos de termos de serviço.
- [Temporary Containers](https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/) — cria contêineres descartáveis que são removidos após o uso.
- [ClearURLs](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) — remove automaticamente elementos de rastreamento de URLs.
- [Disconnect](https://addons.mozilla.org/en-US/firefox/addon/disconnect/) — bloqueia rastreadores de publicidade, analytics e redes sociais.
- [Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/) — remove cookies automaticamente ao fechar abas.
- [CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/) — impede técnicas de fingerprinting via APIs JavaScript.
- [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/) — evita requisições a CDNs centralizadas servindo recursos localmente.
- [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/) — bloqueia rastreadores automaticamente com base em comportamento.

---

## Extensões - Chrome

Chrome não é ideal para privacidade e OPSEC. Apesar de possuir algumas extensões similares, a cobertura é limitada.

- [NoScript](https://chromewebstore.google.com/detail/noscript/doojmbjmlfjjnbmnoijecmcbfeoakpjm)
- [Privacy Badger](https://chromewebstore.google.com/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
- [Decentraleyes](https://chromewebstore.google.com/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [User-Agent Switcher for Chrome](https://chromewebstore.google.com/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg) — falsificação de user-agent.

---

## Navegadores para privacidade

- [Brave](https://brave.com/download/) — baseado em Chromium, com bloqueio nativo de anúncios, trackers e proteção contra fingerprinting. Possui modo Tor integrado.
- [LibreWolf](https://librewolf.net/) — Firefox hardenizado, sem telemetria e com limpeza automática de dados.
- [Mullvad Browser](https://mullvad.net/browser/) — forte foco em anti-fingerprinting, semelhante ao Tor Browser, mas mais utilizável no dia a dia.
- [Tor Browser](https://www.torproject.org/download/) — roteamento via rede Tor, com isolamento de sessão e anonimato elevado.

---

## VPNs

Evite VPNs gratuitas e soluções baseadas apenas em marketing. Prefira serviços sem logs, com mínimo de coleta de dados e suporte a WireGuard.

- [Mullvad VPN](https://mullvad.net/vpn/) — não requer e-mail ou conta pessoal, aceita pagamentos anônimos, sem logs e com suporte nativo a WireGuard.
- [Proton VPN](https://protonvpn.com/) — open source, possui plano gratuito funcional e suporte a multi-hop.
- [IVPN](https://www.ivpn.net/en/) — foco em transparência e proteção contra rastreamento.

---

## DNS

DNS pode ocultar parcialmente sua navegação do provedor, mas adiciona uma nova camada de confiança em terceiros.

- [NextDNS](https://nextdns.io/) — controle granular de logs, bloqueio de malware e rastreadores.
- [Quad9](https://quad9.net/) — sem logs, bloqueio automático focado em segurança.
- [Cloudflare](https://www.cloudflare.com/pt-br/application-services/products/dns/) — alta performance, porém menor foco em privacidade. Oferece WARP.

---

## Sistemas operacionais

- [Tails OS](https://tails.net/) — sistema live via USB, todo o tráfego é roteado pela rede Tor.
- [Qubes OS](https://www.qubes-os.org/) — isolamento baseado em máquinas virtuais para compartimentalização extrema.
- [Whonix](https://www.whonix.org/) — arquitetura com gateway Tor que força todo o tráfego através da rede Tor.
- [GrapheneOS](https://grapheneos.org/) — Android modificado com foco em segurança, hardening e sandboxing, sem serviços Google por padrão.

---

Contribuições de qualquer tipo são bem-vindas. Consulte [contribuições](CONTRIBUTING.md)
