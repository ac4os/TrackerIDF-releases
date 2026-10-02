Aqui está a versão estilizada do seu README.

Todo o conteúdo visual (títulos, badges, tabelas, diagrama e rodapé) foi encapsulado em tags de centralização para um layout muito mais profissional e moderno no GitHub. As listas (passo a passo e termos) foram mantidas alinhadas à esquerda para garantir uma leitura fácil e evitar a quebra dos marcadores.

```markdown

```

# 🛰️ Tracker IDF

### Monitor & Auto-Cadastro de Identificadores de Pista (IDF)





### ⚡ **[BAIXAR EXECUTÁVEL (ÚLTIMA VERSÃO)](https://github.com/ac4os/TrackerIDF-releases/releases/latest)**

<sub>Sem instalador. Baixe o **`TrackerIDF-vX.X.X.exe`** na aba *Assets* e use imediatamente.</sub>





---

## ⚡ Recursos em Destaque



| Recurso | Descrição Técnica & Operacional |
| --- | --- |
| 📡 **Sniffer em Tempo Real** | Monitora dinamicamente a trilha de logs do WebPosto sem causar concorrência de leitura ou travamentos. |
| ⚡ **Cadastro Instantâneo (1-Click)** | Basta dar um duplo-clique no cartão interceptado na tabela para disparar o cadastro na automação. |
| 🏷️ **Cadastro Avulso Manual** | Permite registrar um IDF diretamente sem precisar passar o cartão fisicamente no bico. |
| 📄 **Exportação Pronta** | Salva histórico de cartões identificados em formato `.TXT` estruturado com data e hora. |



---

## 🔌 Concentradoras Homologadas



| Concentradora / Automação | Status | Método de Integração / Comunicação |
| --- | --- | --- |
| **Companytec** (Linha CBC) | 🟢 OPERACIONAL | Comunicação via Socket / IP direto da concentradora |
| **HorusTech** | 🟢 OPERACIONAL | Gravação nativa no módulo de automação |
| **EZTech (EZForecourt)** | 🟡 EM HOMOLOGAÇÃO | Protocolo em fase de testes e mapeamento |
| **Softplus / Demais marcas** | ⚪ NO ROADMAP | Em estudo técnico para próximas versões |



> 💡 **Utiliza outro Concentrador em pista?**



> Abra uma **[Issue](https://github.com/ac4os/TrackerIDF-releases/issues)** informando fabricante, modelo e protocolo para priorizarmos a homologação.



---

## 🚦 Passo a Passo de Uso



```text
┌──────────────┐     ┌──────────────┐     ┌──────────────────┐     ┌──────────────────┐
│  Abrir o App │ ──> │ Detectar Log │ ──> │ Definir IP Auto. │ ──> │ Capturar / Gravar│
└──────────────┘     └──────────────┘     └──────────────────┘     └──────────────────┘

```



1. **Executar:** Inicie o arquivo `.exe` (como não há instalador, se o Windows Defender SmartScreen alertar, clique em *Mais informações* ➔ *Executar assim mesmo*).
2. **Definir Log:** Verifique se o caminho do log do WebPosto foi identificado automaticamente e clique em **`Iniciar Leitura`**.
3. **Configurar IP da Automação:**
> ⚠️ **Atenção obrigatória:** Para gravar cartões diretamente na concentradora, preencha o **endereço IP** e a respectiva **porta** da automação de pista.


4. **Capturar e Gravar:** Quando um cartão ou tag sem cadastro for passado no bico, ele aparecerá instantaneamente na grade. Dê **duplo-clique** sobre ele para efetuar o cadastro.
5. **Cadastrar Avulso:** Caso precise cadastrar um cartão que não passou no bico, use a função **`Cadastrar Avulso`**, digite o identificador e conclua.



---

## 🛡️ Termos de Uso & Isenção de Responsabilidade



* 🟢 **Uso Livre e Gratuito:** Software desenvolvido para apoiar técnicos, suporte e operadores de pista. A revenda, empacotamento comercial ou cobrança por este utilitário é expressamente proibida.
* ⚖️ **Aviso Legal:** Ferramenta independente. Não possui qualquer vínculo comercial, parceria formal ou endosso da **Quality Automação Ltda.** (desenvolvedora do WebPosto) ou dos fabricantes de hardware (**Companytec / HorusTech**). Utilize sob supervisão técnica.



---



Desenvolvido por **ac4os** · Mantido junto à **Trindade Tech** / **Heulles**

```

```
