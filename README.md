# 🌐 Guia Interativo de Comandos de Diagnóstico de Rede

Uma aplicação web responsiva de referência rápida (Cheat Sheet & NOC Playbook) projetada para profissionais de Suporte Técnico (N1/N2), Infraestrutura, Redes e DevOps. Reúne **39 comandos essenciais e avançados** para **Windows (CMD)**, **PowerShell** e **Linux**, com explicações técnicas detalhadas, sintaxe, exemplos copiáveis em um clique e ferramentas de troubleshooting.

---

## ✨ Funcionalidades Principais

* **Base Técnica Abrangente (39 Comandos):**
  * **Nível 1 (Essencial Windows):** `ipconfig`, `ping`, `nslookup`, `tracert`, `pathping`, `Test-NetConnection`, `arp`, `netstat`.
  * **Nível 2 (Complementares CMD):** `netsh`, `route`, `getmac`, `hostname`, `nbtstat`, `tasklist`, `curl`, `wget`, `telnet`, `net use`, `net share`, `net view`, `whoami /all`, `gpresult`.
  * **Nível 2 (PowerShell):** `Get-NetIPConfiguration`, `Get-NetTCPConnection`, `Resolve-DnsName`, `Get-NetNeighbor`, `Get-NetRoute`, `Clear-DnsClientCache`.
  * **Nível 2 (Linux):** `ip addr`, `ss`, `dig`, `traceroute`, `mtr`, `nc (netcat)`, `tcpdump`, `nmcli`, `ethtool`, `whois`, `ufw / iptables`.
* **Checklist de Diagnóstico (Ordem Lógica):** Fluxo passo a passo de resolução de problemas da camada física/local até a camada de aplicação/porta.
* **Tabela de Equivalência Multiplataforma & Cola Técnica:** Comparativo direto entre comandos do Windows CMD, PowerShell e Linux, além de referência rápida de portas críticas (`22`, `53`, `80/443`, `445`, `3389`) e estados de socket TCP (`LISTENING`, `ESTABLISHED`, `SYN_SENT`).
* **Kit de Emergência:** Barra superior com os 19 comandos mais utilizados no dia a dia prontos para cópia imediata.
* **Busca Instantânea & Filtros Combinados:** Filtre simultaneamente por **Sistema/Nível**, **Privilégios (Admin/Root)** e **Objetivo Técnico** (*IP & Interfaces*, *DNS & Domínios*, *Rotas & Latência*, *Portas & Tráfego*, *Compartilhamento & Políticas*).
* **Cópia em 1 Clique:** Todos os exemplos possuem botão de cópia rápida com feedback visual (Toast).
* **Design Mobile-First & Alto Contraste:** Paleta inspirada em interfaces noturnas de alto contraste (`#001219`, `#005F73`, `#0A9396`, `#CA6702`, `#EE9B00`), com alternância entre **Modo Escuro** e **Modo Claro**.
* **Pronto para Impressão / PDF (`@media print`):** Folha de estilo otimizada que oculta botões e menus interativos ao imprimir ou salvar em PDF.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico** (Arquitetura *Single-File*, sem necessidade de build ou servidor backend)
* **Tailwind CSS** (via CDN, com configuração de paleta customizada e suporte a Dark Mode)
* **JavaScript Vanilla (ES6+)** (Filtragem dinâmica, busca em tempo real e manipulação segura da área de transferência)
* **Lucide Icons** (Ícones vetoriais leves)
* **Google Fonts** (`Inter` para leitura e `JetBrains Mono` para blocos de código)

---

## 🚀 Como Usar

Como o projeto foi construído em arquivo único (`comandos_rede.html`), não é necessário instalar dependências ou configurar servidores:

1. Baixe ou clone o arquivo `comandos_rede.html`.
2. Dê um duplo clique no arquivo para abri-lo diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari) no desktop ou smartphone.
3. *(Opcional)* Para gerar um manual físico de bancada, clique no botão **Imprimir / PDF** no topo da página.

---

## 📁 Estrutura do Projeto

```text
├── comandos_rede.html   # Aplicação completa (HTML, CSS/Tailwind, JS e base de dados)
└── README.md            # Documentação do projeto
```

---

## 👨‍💻 Autor

Desenvolvido e mantido por **ALEXANDER**.
