# 🛡️ SECTEAM — Cyber Defense Unit

### ⚡ Protocolo de Visualização de Defesa Cibernética

Este é o projeto oficial da **SECTEAM** para a palestra no **SESI**. Ele consiste em uma interface de terminal de elite projetada para apresentar documentos de segurança com imersão total no estilo *Cyberpunk/High-Tech*.

---

## 🚀 Funcionalidades do Sistema

### 🖥️ Interface de Comando (Landing Page)

* **Ambiente Imersivo:** Fundo dinâmico com `particles.js` e efeito de interferência (*Scanlines*).
* **Interação Avançada:** Cursor customizado com efeito *ripple*, trilha e magnetismo nos elementos.
* **Acesso Rápido:** Atalho de teclado `ENTER` para iniciar o protocolo de leitura.

### 📄 Visualizador de Documentos (PDF Reader)

* **Interface HUD:** Design em *Glassmorphism* com bordas neon (Cyan & Roxo).
* **Simulação de Descriptografia:** Barra de progresso animada simulando o carregamento de arquivos sigilosos.
* **Comandos de Operador:**
* `[ ESC ] TERMINATE_SESSION` para retornar.
* `SECURE_DOWNLOAD` para baixar o material oficial.



---

## 🛠️ Especificações Técnicas

* **Paleta de Cores:** * Fundo: `#050505` (Deep Black)
* Primária: `#00f2ff` (Cyber Cyan)
* Secundária: `#7000ff` (Electric Purple)


* **Tipografia:** `Orbitron` e `Rajdhani` (via Google Fonts).
* **Bibliotecas:** `particles.js` (Efeitos de partículas).

---

## 📁 Estrutura de Arquivos

```bash
├── index.html       # Portal de entrada e autenticação
├── pdf.html         # Terminal de leitura de documentos
├── pdf.css          # Estilos do visualizador (Glassmorphism)
├── style.css        # Core design e física do cursor
└── assets/          # Repositório de arquivos PDF e recursos

```

---

## ⚙️ Operação Local

Para rodar o terminal em sua máquina, execute um servidor local para evitar bloqueios de segurança do navegador:

**Via Python:**

```bash
python -m http.server 8000

```

Acesse em: `http://localhost:8000`

**Atalhos de Teclado:**

* `ENTER` na Landing → Inicia Protocolo.
* `ESC` no Leitor → Encerra Sessão.
* `SPACE` → Ativa botões focados.

---

## 📜 Licença

Este projeto está sob a licença **MIT**. Sinta-se livre para clonar, modificar e distribuir, mantendo os créditos da **SECTEAM**.

---

> **Aviso de Segurança:** Este software é uma interface demonstrativa para fins educacionais no SESI.