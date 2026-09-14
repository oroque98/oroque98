![Kainã Roque — Network Analyst: Enterprise Networking, Security & Automation](assets/header.svg)

I work on enterprise campus networks in multi-site corporate environments — switching,
wireless, network access control, secure access and network services.

My approach to automation is read-only first: I automate collection and analysis
before I automate change.

![Cisco](https://img.shields.io/badge/Cisco-informational?style=flat&logo=cisco&logoColor=2F81F7&labelColor=0D1117&color=1F6FEB)
![Aruba AOS-CX](https://img.shields.io/badge/Aruba_AOS--CX-informational?style=flat&labelColor=0D1117&color=1F6FEB)
![Python](https://img.shields.io/badge/Python-informational?style=flat&logo=python&logoColor=2F81F7&labelColor=0D1117&color=1F6FEB)
![Netmiko](https://img.shields.io/badge/Netmiko-informational?style=flat&labelColor=0D1117&color=1F6FEB)

---

## What I work on

| Area | Scope &amp; platforms |
| :--- | :--- |
| **Switching &amp; routing** | Campus LAN operations and design support — Cisco, Aruba AOS-CX |
| **Wireless** | Corporate Wi-Fi deployment support, RF and client-side troubleshooting — Aruba, Aruba Central |
| **Network access control** | 802.1X and MAB authentication, roles and dynamic VLAN assignment — Aruba ClearPass |
| **Secure access** | Firewall and endpoint access troubleshooting — Palo Alto, FortiGate, Zscaler (SASE) |
| **Network services** | DNS, DHCP and IPAM operations — Infoblox |
| **Troubleshooting** | L1–L3 connectivity analysis, interface / neighbor / topology investigation, incident triage |

---

## Automation

Moving network operations from manual CLI work to repeatable, auditable tooling.

```text
   device CLI  ──ssh──▶  Netmiko  ──▶  parser  ──▶  structured data
                                                         │
                                    config audit ◀───────┼───────▶ inventory
                                                         ▼
                                                 anomaly detection
```

- **Python + Netmiko** — SSH collection of read-only commands from network devices
- **Output parsing** — turning unstructured CLI output into structured data
- **Git** — version control for scripts and collected baselines

---

## Currently

- Studying for the **Cisco CCNA** to consolidate routing and switching fundamentals
- Extending my AOS-CX collector toward configuration drift detection
- Moving beyond CLI scraping — REST APIs and structured network data models

---

<!--
  ┌──────────────────────────────────────────────────────────────────────────┐
  │ NAO FACA COMMIT DESTA SECAO ATE QUE O REPOSITORIO ESTEJA PUBLICADO.      │
  │ Uma tabela de projetos com link quebrado e pior do que nenhuma tabela.   │
  └──────────────────────────────────────────────────────────────────────────┘

## Projects

| Project | What it does |
| :--- | :--- |
| [aoscx-collector](https://github.com/oroque98/aoscx-collector) | Read-only Netmiko collection and parsing of Aruba AOS-CX output for configuration audit, inventory and anomaly detection |

-->

## Contact

**LinkedIn** — https://www.linkedin.com/in/kaina-roque &nbsp;·&nbsp; São Paulo, Brazil

<!--
  ──────────────────────────────────────────────────────────────────────────────
  NOTAS DE MANUTENCAO (invisiveis quando o README e renderizado)
  ──────────────────────────────────────────────────────────────────────────────

  ESTRUTURA DE ARQUIVOS NO REPOSITORIO oroque98/oroque98:

      README.md
      assets/
        └── header.svg

  O caminho relativo assets/header.svg funciona no README de perfil.
  Se preferir caminho absoluto, use:
  https://raw.githubusercontent.com/oroque98/oroque98/main/assets/header.svg

  ──────────────────────────────────────────────────────────────────────────────
  ANTES DO PRIMEIRO COMMIT:

  1. LinkedIn — a URL acima usa a vanity URL limpa que voce ainda precisa criar
     (Perfil > Editar URL publica). Para manter a atual, use:
     https://www.linkedin.com/in/kain%C3%A3-roque-23a4a418b
     TESTE O LINK EM UMA ABA ANONIMA ANTES DE COMMITAR.

  2. Nome da conta — esta como "kaina roque" (minusculas) em
     github.com/settings/profile. Altere para "Kaina Roque" (com o til correto).

  3. Confira o banner nos DOIS temas do GitHub (Settings > Appearance).
     A paleta foi escolhida para funcionar nos dois, mas veja com seus olhos.

  4. CCNA — se ja tiver data de prova, troque por algo como:
     "Studying for the Cisco CCNA — exam scheduled for March 2027"

  5. BGP — so entra na tabela se voce opera em producao. Se for estudo,
     pertence a linha do CCNA.

  ──────────────────────────────────────────────────────────────────────────────
  A FILEIRA DE BADGES E OPCIONAL.

  Quatro e o teto. Nao adicione Git, GitHub, VLAN, STP, LACP ou fabricantes que
  ja aparecem na tabela — a tabela e a fonte da verdade; os badges sao so ritmo
  visual. Se achar que o banner ja resolve, delete as 4 linhas sem do.

  ──────────────────────────────────────────────────────────────────────────────
  SEGURANCA — nunca inclua neste repositorio nem nos projetos:
  IPs internos, hostnames reais, nomes de clientes/sites, VLAN IDs de producao,
  SSIDs corporativos, configs proprietarias, credenciais ou tokens.
  Em outputs de exemplo, use dados sinteticos
  (ex.: switch-01, 192.0.2.0/24 — faixa reservada para documentacao, RFC 5737).
  ──────────────────────────────────────────────────────────────────────────────
-->
