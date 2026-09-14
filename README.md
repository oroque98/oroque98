![Kainã Roque — Network Analyst. Enterprise Networking, Security and Automation.](assets/header.svg)

I work on enterprise campus networks in multi-site corporate environments: switching,
wireless, network access control, secure access and network services.

I'm moving that work toward automation, read-only first — collection and analysis
before change.

---

## What I work on

| Area | Scope and platforms |
| :--- | :--- |
| **Switching & routing** | Campus LAN operations and design support — Cisco, Aruba AOS-CX |
| **Wireless** | Corporate Wi-Fi deployment support, RF and client-side troubleshooting — Aruba, Aruba Central |
| **Network access control** | 802.1X and MAB authentication, roles and dynamic VLAN assignment — Aruba ClearPass |
| **Secure access** | Firewall and endpoint access troubleshooting — Palo Alto, FortiGate, Zscaler (SASE) |
| **Network services** | DNS, DHCP and IPAM operations — Infoblox |
| **Troubleshooting** | L1–L3 connectivity analysis, interface / neighbor / topology investigation, incident triage |

---

## Automation

Turning manual CLI work into repeatable, auditable tooling.

```text
collection   ──▶   read-only commands over SSH        (Python, Netmiko)
parsing      ──▶   CLI output into structured data
analysis     ──▶   configuration audit · inventory · anomalies
```

Read-only by design: nothing in my tooling writes to a device. Automating what I can
verify comes before automating what I can change.

---

## Currently

- Studying for the **Cisco CCNA**, consolidating routing and switching fundamentals
- Extending my AOS-CX collector toward configuration drift detection
- Moving past CLI scraping — REST APIs and structured network data models

---

<!--
  ┌──────────────────────────────────────────────────────────────────────────┐
  │  NÃO COMMITAR ESTA SEÇÃO ANTES DE O REPOSITÓRIO EXISTIR E ESTAR PÚBLICO. │
  │  Tabela de projetos com link quebrado é pior do que não ter a seção.     │
  └──────────────────────────────────────────────────────────────────────────┘

## Projects

| Project | What it does |
| :--- | :--- |
| [aoscx-collector](https://github.com/oroque98/aoscx-collector) | Read-only Netmiko collection and parsing of Aruba AOS-CX output for configuration audit, inventory and anomaly detection |

-->

## Contact

**LinkedIn** — https://www.linkedin.com/in/kaina-roque · São Paulo, Brazil

<!--
──────────────────────────────────────────────────────────────────────────────
 NOTAS DE MANUTENÇÃO — invisíveis no README renderizado
──────────────────────────────────────────────────────────────────────────────

 ESTRUTURA NO REPOSITÓRIO oroque98/oroque98

     README.md
     assets/
       └── header.svg

 O caminho relativo funciona no README de perfil. Alternativa absoluta:
 https://raw.githubusercontent.com/oroque98/oroque98/main/assets/header.svg

──────────────────────────────────────────────────────────────────────────────
 ANTES DO PRIMEIRO COMMIT

 1. LinkedIn — a URL acima assume a vanity URL limpa que você ainda precisa
    criar (LinkedIn > Perfil > Editar URL pública). Para manter a atual:
    https://www.linkedin.com/in/kain%C3%A3-roque-23a4a418b
    ABRA O LINK EM ABA ANÔNIMA ANTES DE COMMITAR.

 2. Nome da conta — hoje está em minúsculas em github.com/settings/profile.
    Ajuste para "Kainã Roque".

 3. Bio do perfil — mantenha alinhada com o banner:
    Network Analyst | Enterprise Networking · Security · Automation

 4. Veja o banner nos dois temas (Settings > Appearance) e no celular.

 5. CCNA — com data de prova definida, troque por:
    "Studying for the Cisco CCNA — exam scheduled for <mês/ano>"
    Marco datado comunica mais credibilidade do que "estudando".

 6. BGP — só entra na tabela se você opera em produção. Se for estudo,
    pertence à linha do CCNA.

──────────────────────────────────────────────────────────────────────────────
 NÃO ADICIONAR

 Badges de tecnologia, skillicons, typing SVG, snake, stats cards, streak,
 profile views, barras de proficiência, emojis, frases motivacionais,
 badges de Git/GitHub, protocolos soltos (VLAN, STP, LACP).

 Se um dia quiser uma fileira de badges: máximo 4, style=flat,
 labelColor=0D1117 e color=1F6FEB para ficar legível nos dois temas.

──────────────────────────────────────────────────────────────────────────────
 SEGURANÇA — nunca neste repositório nem nos projetos

 IPs internos, hostnames reais, nomes de clientes ou sites, VLAN IDs de
 produção, SSIDs corporativos, configs proprietárias, credenciais, tokens.
 Em exemplos, use dados sintéticos: switch-01, 192.0.2.0/24
 (faixa reservada para documentação, RFC 5737).
──────────────────────────────────────────────────────────────────────────────
-->
