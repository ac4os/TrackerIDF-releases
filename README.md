<div align="center">

<img width="100%" alt="Tracker IDF" src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:3b82f6,100:22c55e&height=200&section=header&text=Tracker%20IDF&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=bico%20%C2%B7%20sensor&descAlignY=58&descSize=20" />

# 🛰️ Tracker IDF

### Monitor & Auto-Cadastro de Identificadores de Pista (IDF)

<br/>

[![Versão Mais Recente](https://img.shields.io/github/v/release/ac4os/TrackerIDF-releases?label=vers%C3%A3o&style=for-the-badge&color=22c55e&logo=github)](https://github.com/ac4os/TrackerIDF-releases/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/ac4os/TrackerIDF-releases/total?style=for-the-badge&color=3b82f6&logo=google-drive)](https://github.com/ac4os/TrackerIDF-releases/releases)
[![Online Agora](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Ftrackeridf-telemetry.ac4os-dev.workers.dev%2Fstats&query=%24.online&label=online%20agora&style=for-the-badge&color=22c55e&logo=cloudflare)](#-uso-em-tempo-real)
[![Usuários](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Ftrackeridf-telemetry.ac4os-dev.workers.dev%2Fstats&query=%24.total&label=usu%C3%A1rios&style=for-the-badge&color=8b5cf6&logo=statuspage)](#-uso-em-tempo-real)
[![Compatibilidade SO](https://img.shields.io/badge/Windows-10%20%7C%2011%20(64--bit)-0ea5e9?style=for-the-badge&logo=windows)](#)
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-Gratuita-f59e0b?style=for-the-badge)](#)

<br/>

### ⚡ [**BAIXAR EXECUTÁVEL (ÚLTIMA VERSÃO)**](https://github.com/ac4os/TrackerIDF-releases/releases/latest)

<sub>Sem instalador. Baixe o **`TrackerIDF-vX.X.X.exe`** na aba *Assets* e use imediatamente.</sub>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

## ⚡ Recursos em Destaque

</div>

| Recurso | Descrição Técnica & Operacional |
| --- | --- |
| 📡 **Sniffer em Tempo Real** | Monitora dinamicamente a trilha de logs do WebPosto sem causar concorrência de leitura ou travamentos. |
| ⚡ **Cadastro Instantâneo (1-Click)** | Basta dar um duplo-clique no cartão interceptado na tabela para disparar o cadastro na automação. |
| 🏷️ **Cadastro Avulso Manual** | Permite registrar um IDF diretamente sem precisar passar o cartão fisicamente no bico. |
| 📄 **Exportação Pronta** | Salva histórico de cartões identificados em formato `.TXT` estruturado com data e hora. |

<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

## 🔌 Concentradoras Homologadas

</div>

| Concentradora / Automação | Status | Método de Integração / Comunicação |
| --- | --- | --- |
| **Companytec** (Linha CBC) | 🟢 OPERACIONAL | Comunicação via Socket / IP direto da concentradora |
| **HorusTech** | 🟢 OPERACIONAL | Gravação nativa no módulo de automação |
| **EZTech (EZForecourt)** | 🟡 EM HOMOLOGAÇÃO | Protocolo em fase de testes e mapeamento |
| **Softplus / Demais marcas** | ⚪ NO ROADMAP | Em estudo técnico para próximas versões |

> 💡 **Utiliza outro Concentrador em pista?**
> Abra uma **[Issue](https://github.com/ac4os/TrackerIDF-releases/issues)** informando fabricante, modelo e protocolo para priorizarmos a homologação.

<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

## 🚦 Passo a Passo de Uso

</div>

```
┌──────────────┐     ┌──────────────┐     ┌──────────────────┐     ┌──────────────────┐
│  Abrir o App │ ──> │ Detectar Log │ ──> │ Definir IP Auto. │ ──> │ Capturar / Gravar│
└──────────────┘     └──────────────┘     └──────────────────┘     └──────────────────┘

```

1. **Executar:** Inicie o arquivo `.exe` (como não há instalador, se o Windows Defender SmartScreen alertar, clique em *Mais informações* ➔ *Executar assim mesmo*).
2. **Definir Log:** Verifique se o caminho do log do WebPosto foi identificado automaticamente e clique em **`Iniciar Leitura`**.
3. **Configurar IP da Automação:**
> ⚠️ **Atenção obrigatória:** Para gravar cartões diretamente na concentradora, preencha o **endereço IP** e a respectiva **porta** da automação de pista.

4. **Capturar e Gravar:** Quando um cartão ou tag sem cadastro for passado no bico, ele aparecerá instantaneamente na grade. Dê **duplo-clique** sobre ele para efetuar o cadastro.
<img width="1137" height="878" alt="image" src="https://github.com/user-attachments/assets/06244c20-3e43-4755-81bc-ca4899b1f913" /> 


https://github.com/user-attachments/assets/837b1c8e-ab22-4b4a-a034-38778a4ea2c3


   
5. **Cadastrar Avulso:** Caso precise cadastrar um cartão que não passou no bico, use a função **`Cadastrar Avulso`**, digite o identificador e conclua.

<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

## 📊 Uso em Tempo Real

<img alt="Usuários ativos por dia" src="https://trackeridf-telemetry.ac4os-dev.workers.dev/chart.svg" width="100%" />

<sub>Máquinas únicas ativas por dia. Atualização automática · telemetria <b>anônima</b> (apenas um identificador irreversível da máquina + versão, nenhum dado pessoal).</sub>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

## 🛡️ Termos de Uso & Isenção de Responsabilidade

</div>

* 🟢 **Uso Livre e Gratuito:** Software desenvolvido para apoiar técnicos, suporte e operadores de pista. A revenda, empacotamento comercial ou cobrança por este utilitário é expressamente proibida.
* ⚖️ **Aviso Legal:** Ferramenta independente. Não possui qualquer vínculo comercial, parceria formal ou endosso da **Quality Automação Ltda.** (desenvolvedora do WebPosto) ou dos fabricantes de hardware (**Companytec / HorusTech**). Utilize sob supervisão técnica.

<br/>

<div align="center">

### Desenvolvido por **ac4os** · Mantido junto à **Trindade Tech** 

<img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,50:3b82f6,100:0ea5e9&height=120&section=footer" />

</div>
