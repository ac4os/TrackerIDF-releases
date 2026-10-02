# Tracker IDF

> Ferramenta gratuita para técnico e usuários WP  — captura cartões não cadastrados na automação e no WebPosto (Quality) sendo possivel cadastra identificadores (IDF) diretamente na automação HorusTech.

[![Última versão](https://img.shields.io/github/v/release/ac4os/TrackerIDF-releases?label=vers%C3%A3o&color=2ea44f)](https://github.com/ac4os/TrackerIDF-releases/releases/latest)
[![Plataforma](https://img.shields.io/badge/plataforma-Windows-blue)](#-download)

---

## O que faz?

O Tracker IDF monitora em tempo real o log da automação WebPosto e detecta toda vez que um cartão **não cadastrado** é passado em um bico.

Para cada passagem detectada, ele mostra:

| Campo  | Descrição |
|--------|-----------|
| Hora   | Data e hora exata da passagem |
| Cartão | Código do identificador (IDF) |
| Bico   | Número do bico |
| Sensor | Sensor da automação |

Com um **duplo clique** em qualquer linha, você abre o formulário de cadastro e grava o IDF diretamente na automação — sem precisar abrir o HRSConsole.

---

## Funcionalidades

- 📡 Leitura ao vivo do log `webPostoLeituraAutomacao*` em `C:\Quality\LOG`
- 🔍 Detecção automática do log mais recente
- ✏️ Cadastro de IDF direto na automação HorusTech
- 📦 Cadastro em lote — vários IDF de uma vez, separados por `;`
- 💾 Exportação dos eventos para `.txt`

---

## 📥 Download

Acesse a [**página de releases**](https://github.com/ac4os/TrackerIDF-releases/releases/latest) e baixe o `.exe` da versão mais recente.

> Não precisa instalar nada. Basta executar o arquivo.

Se o Windows exibir um aviso do SmartScreen, clique em **"Mais informações" → "Executar assim mesmo"**.

---

## Como usar

1. Execute o `TrackerIDF.exe`
2. O caminho do log é detectado automaticamente, caso esteja fora do caminho padrão, pode buscar
3. Clique em **"Iniciar leitura"**
4. Passe um cartão não cadastrado no bico — ele aparece na tabela
5. Dê **duplo clique** na linha para cadastrar o IDF na automação (Hoje só temos protocolo HRSConsole)
6. Para cadastro na automação, é necessário informar o ip da automação ( a porta TCP ele busca a livre sozinho)

---

## ⚠️ Aviso importante

O Tracker IDF é uma **ferramenta gratuita**.

A venda ou comercialização deste software **não é autorizada** nem apoiada pelos desenvolvedores.

Este programa **não possui qualquer vínculo** com a **Quality Automação Ltda.** (detentora do WebPosto), nem com a **Companytec / HorusTech**.

**Use por sua conta e risco.**

---

*By **ac4os** — Trindade Tech*
