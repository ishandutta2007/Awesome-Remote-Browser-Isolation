# Awesome-Remote-Browser-Isolation

## Top Remote Browser Isolation (RBI) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Web Isolation, Zero-Trust Browsing, Malware Prevention, Secure Remote Browsing & Content Disarm*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Remote Browser Isolation (RBI)**. These solutions execute web content in a remote, isolated environment and stream only safe rendering (pixels or cleaned content) to the user’s device, protecting endpoints from malware, phishing, and zero-day browser threats.



**Examples** include Menlo Security, Authentic8 Silo, Ericom Shield, Cloudflare Browser Isolation, Netskope RBI, Perimeter 81 / Check Point, Palo Alto Prisma Access Browser, Forcepoint RBI, Symantec / Broadcom RBI, iboss, Island, LayerX, Talon Security, Citrix Secure Browser, and Lightpoint (the category leaders).



**Open-source emphasis**: Enterprise RBI platforms with global scale, policy integration, and advanced CDR are commercial. There is, however, a meaningful open-source ecosystem led by **BrowserBox**, containerized VNC/RBI projects, and experimental isolation stacks. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Menlo Security](https://www.menlosecurity.com/)**  

  Leading enterprise remote browser isolation platform focused on transparent isolation, phishing protection, and integration with broader web security and Zero Trust architectures.



- **[Authentic8 Silo](https://www.authentic8.com/)**  

  Cloud-native web isolation platform popular in high-security and regulated environments, with strong session controls and research-oriented capabilities.



- **[Cloudflare Browser Isolation](https://www.cloudflare.com/)**  

  Network-delivered remote browser isolation integrated into Cloudflare’s Zero Trust / SASE platform, using Network Vector Rendering for performance.



- **[Palo Alto Prisma Access / Prisma Access Browser](https://www.paloaltonetworks.com/)**  

  RBI capabilities natively integrated with Prisma Access for policy-driven isolation of risky or unmanaged browsing.



- **[Netskope RBI, Forcepoint RBI, iboss](https://www.netskope.com/)**  

  Cloud security platforms offering remote browser isolation as part of broader SWG, CASB, and Zero Trust offerings.



- **[Island, LayerX, Talon Security](https://www.island.io/)**  

  Modern enterprise browser and isolation-focused solutions emphasizing secure access, productivity, and data protection.



- **[Ericom Shield, Citrix Secure Browser](https://www.ericom.com/)**  

  Established isolation and secure browser solutions for enterprises needing controlled remote browsing environments.



- **[Other RBI & secure browser platforms](https://www.menlosecurity.com/)**  

  Additional commercial tools covering clientless isolation, CDR, and Secure Enterprise Browser approaches.



## Open-Source GitHub Projects



- **[BrowserBox](https://github.com/BrowserBox/BrowserBox)**  

  Leading open-source remote browser isolation platform. Provides secure, cross-platform RBI that runs remote browsers and streams sessions, with both self-hosted and managed options.



- **[SupraRBI-VNC](https://github.com/SupraAXES/SupraRBI-VNC)**  

  Remote Browser Isolation solution implemented as a VNC server. Users connect with a VNC client; each session launches an isolated browser instance for the target URL.



- **[rbix](https://github.com/manigandand/rbix)**  

  Container-based remote browser isolation project using WebSocket reverse proxying and isolated browser containers for RBI workloads.



- **[ViewFinderJS / related isolation projects](https://github.com/search?q=remote+browser+isolation+OR+ViewFinder)**  

  Open-source clientless or embeddable remote browser isolation implementations that stream pixels from a remote browser to the local device.



- **[Kasm Workspaces (community / self-hosted roots)](https://github.com/kasmtech)**  

  Containerized desktop and browser streaming platform frequently used as a foundation for remote browser isolation deployments.



- **[Other RBI PoCs & container isolation tools](https://github.com/search?q=remote+browser+isolation+OR+RBI+VNC+OR+browser+isolation)**  

  Research and proof-of-concept projects demonstrating pixel-pushing, containerized Chrome, and WebSocket-based isolation.



- **[Secure document viewing / CDR companions](https://github.com/search?q=content+disarm+OR+CDR+OR+safe+document+viewer)**  

  Open tools that complement RBI by sanitizing or safely rendering documents inside isolated environments.



- **[Browser automation + isolation hybrids](https://github.com/search?q=headless+chrome+isolation+OR+remote+chrome)**  

  Projects combining headless or remote Chrome instances with isolation patterns for secure automation and browsing.



### Additional Strong Open-Source Options



- **Container runtimes & sandboxes**: Docker, Firecracker, or gVisor-based isolation for browser processes.

- **VNC / noVNC / Guacamole**: Classic remote desktop protocols adapted for browser-only isolation sessions.

- **WebRTC streaming stacks**: Open components for low-latency pixel or video streaming of remote browser sessions.

- **Policy & proxy layers**: Open reverse proxies and identity-aware proxies that can gate access to isolated browsers.

- **Logging & session recording**: Open tools for capturing and auditing isolated browsing sessions.

- Self-hosted combinations of Kasm / BrowserBox-style platforms with enterprise identity providers.



**Frameworks for building custom systems**:  

The most mature open-source starting points are **BrowserBox** and containerized VNC/RBI projects such as **SupraRBI-VNC** or **rbix**.  

These can be combined with identity providers, reverse proxies, and optional CDR tools to create a self-hosted isolation service.  

Commercial RBI platforms (Menlo, Authentic8, Cloudflare, Prisma Access, Netskope, Island, etc.) provide global scale, advanced threat intelligence, seamless policy integration, and lower operational overhead.  

Many security teams prototype with open-source isolation stacks and later adopt commercial RBI for production Zero Trust and high-risk browsing use cases.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Remote Browser Isolation is a security control. Proper configuration, network isolation, patching of the isolation infrastructure, and integration with identity and DLP controls are critical.

- Open-source RBI projects offer transparency and flexibility but require significant operational expertise for hardening, scaling, high availability, and compliance. They are not drop-in replacements for enterprise commercial RBI platforms in most large or highly regulated environments. Operators remain responsible for the security posture of any deployment.



---



**Made for security architects, Zero Trust practitioners, SOC teams, and IT leaders protecting users from web-borne threats.**  

Let's expand open, auditable approaches to browser isolation while recognizing the scale and maturity of leading commercial RBI platforms.
