<div align="center">

# Guia de Descarte de E-Lixo e Baterias
### Logística Reversa, Neutralização Toxicológica e Triagem Comunitária

[![GitHub Stars](https://img.shields.io/github/stars/pedroiff0/guia-elixo?style=flat-square&color=2e7d32)](https://github.com/pedroiff0/guia-elixo/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/pedroiff0/guia-elixo?style=flat-square&color=2e7d32)](https://github.com/pedroiff0/guia-elixo/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/pedroiff0/guia-elixo?style=flat-square&color=2e7d32)](https://github.com/pedroiff0/guia-elixo/issues)
[![Licença MIT](https://img.shields.io/badge/licença-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat-square)](#status)
[![Plataforma Web](https://img.shields.io/badge/web-elixo.phrandrade.com-blue?style=flat-square)](https://elixo.phrandrade.com)
[![Instituição](https://img.shields.io/badge/IFF-Campus%20Bom%20Jesus-1b5e20?style=flat-square)](https://portal1.iff.edu.br/nossos-campi/bom-jesus-do-itabapoana)

Plataforma web de conscientização ambiental, catálogo reativo de resíduos eletroeletrônicos (REEE) e modelagem de Ponto de Entrega Voluntária (PEV) para o Noroeste Fluminense.

[Acesso Online](https://elixo.phrandrade.com) · [Sobre](#sobre-o-projeto) · [Funcionalidades](#funcionalidades) · [Catálogo](#catálogo-de-resíduos-e-baterias) · [Projeto Institucional](#projeto-institucional-no-iff) · [Base Legal](#marcos-legais-e-diagnóstico-municipal) · [Execução Local](#como-executar-localmente) · [Autores](#autores--orientação) · [Citação](#como-citar)

</div>

---

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Contexto Acadêmico & Diagnóstico Regional](#contexto-acadêmico--diagnóstico-regional)
- [Demonstração e Acesso Online](#demonstração-e-acesso-online)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Catálogo de Resíduos e Baterias](#catálogo-de-resíduos-e-baterias)
- [Projeto Institucional no IFF](#projeto-institucional-no-iff)
- [Tríade Documental no ReLaTeX](#tríade-documental-no-relatex)
- [Marcos Legais e Diagnóstico Municipal](#marcos-legais-e-diagnóstico-municipal)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Como Executar Localmente](#como-executar-localmente)
- [Autores & Orientação](#autores--orientação)
- [Como Citar](#como-citar)
- [Licença](#licença)

---

## Sobre o Projeto

O **Guia de Descarte de E-Lixo e Baterias** é um projeto de intervenção técnica e conscientização cidadã desenvolvido no curso de Bacharelado em Engenharia de Computação do Instituto Federal Fluminense (*Campus* Bom Jesus do Itabapoana), no âmbito da disciplina Filosofia da Ciência e Tecnologia (2026/2).

O projeto aborda a problemática do lixo eletroeletrônico sob as lentes da responsabilidade tecnológica (Hans Jonas), da obsolescência programada na modernidade líquida (Zygmunt Bauman) e da neutralidade instrumental da técnica (Alberto Cupani). Como resposta prática às deficiências locais de saneamento, foi desenvolvida uma plataforma web otimizada para dispositivos móveis que cataloga os resíduos, expõe seus perigos toxicológicos, ensina procedimentos imediatos de segurança e orienta o encaminhamento correto pela logística reversa.

---

## Contexto Acadêmico & Diagnóstico Regional

| Parâmetro | Detalhe |
| :--- | :--- |
| **Instituição** | Instituto Federal de Educação, Ciência e Tecnologia Fluminense (IFF) |
| **Campus** | Campus Bom Jesus do Itabapoana - RJ |
| **Curso** | Bacharelado em Engenharia de Computação |
| **Disciplina** | Filosofia da Ciência e Tecnologia (6.º Período) |
| **Docente Orientador** | Prof. Me. Rafael Ferreira Tardin da Silva |
| **Docente Patrono** | Prof. Dr. Rafael Artur de Paiva Gardoni |
| **Ano / Semestre** | 2026 / 2.º Semestre |

### Diagnóstico do Município de Bom Jesus do Itabapoana (PMGIRS 2024)
Conforme dados do Plano Municipal de Gestão Integrada de Resíduos Sólidos de Bom Jesus do Itabapoana (2024):
1. **Inexistência de Aterro Próprio:** O município não dispõe de aterro sanitário ou industrial licenciado em seu território.
2. **Geração Per Capita:** A taxa oficial é de 0,724 kg/habitante/dia de resíduos sólidos.
3. **Transbordo Rodoviário Poluente:** Todo o rejeito coletado é transbordado em carretas e transportado por 67 km de rodovia até a Central de Tratamento de Resíduos (CTR Campos), em Campos dos Goytacazes.
4. **Passivo de REEE:** Baterias de lítio e chumbo-ácido descartadas na coleta convencional acabam enterradas ou incineradas clandestinamente, acarretando contaminação crônica de metais pesados na bacia do Rio Itabapoana.

---

## Demonstração e Acesso Online

A aplicação está disponível publicamente com acesso imediato:

- **Domínio de Produção:** [https://elixo.phrandrade.com](https://elixo.phrandrade.com)
- **Espelho GitHub Pages:** [https://pedroiff0.github.io/guia-elixo/](https://pedroiff0.github.io/guia-elixo/)
- **Portfólio Institucional do Autor:** [https://phrandrade.com](https://phrandrade.com)

---

## Funcionalidades

- **Busca Reativa Instantânea:** Campo de busca em tempo real com filtragem automática de títulos, riscos e procedimentos de descarte.
- **Filtros por Categoria:** Navegação segmentada por Baterias, Pilhas, Celulares, Informática e Eletrodomésticos.
- **Estrutura Triangular por Item:** Cada componente do catálogo detalha explicitamente (1) Risco Toxicológico & Físico, (2) Preparo Seguro Obrigatório e (3) Ponto de Destino Homologado.
- **Design Mobile-First:** Interface responsiva desenhada para operação fluida em smartphones, com barra de navegação inferior (*bottom tab bar*) e seções em sanfona (*accordion*).
- **Central de Legislações Integrada:** Acesso em um clique aos textos oficiais em PDF de leis federais, resoluções normativas (CONAMA, INEA) e planos municipais (PMGIRS BJI e Campos).
- **Privacidade e Desempenho:** Arquitetura 100% estática, sem cookies de terceiros, sem rastreadores e com tempo de carregamento inferior a 300 ms.

---

## Tecnologias Utilizadas

<div align="left">

| Tecnologia | Finalidade no Projeto |
| :--- | :--- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Estruturação semântica acessível e metatags OpenGraph |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Design responsivo, tipografia Inter, paleta institucional IFF e variáveis CSS |
| ![JavaScript](https://img.shields.io/badge/JavaScript_ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Lógica reativa de busca, filtros dinâmicos de categoria e controle de UI |
| ![LaTeX](https://img.shields.io/badge/LaTeX-ReLaTeX-008080?style=flat-square&logo=latex&logoColor=white) | Editoração acadêmica de relatórios ABNT, slides e panfletos nas classes IFF |
| ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) | Controle de versão distribuído e automação de deploy via GitHub Pages |

</div>

---

## Catálogo de Resíduos e Baterias

O banco de dados integrado cataloga 8 grupos críticos de resíduos eletroeletrônicos:

| Resíduo | Risco Toxicológico / Físico | Preparo Obrigatório | Destino Recomendado |
| :--- | :--- | :--- | :--- |
| **Baterias de Íon de Lítio** | Fuga térmica (*thermal runaway*), fogo espontâneo e emissão de gases de cobalto e níquel | Isolar os polos metálicos com fita adesiva e guardar em caixa plástica seca | Logística reversa no varejo técnico de compra ou PEV do IFF |
| **Pilhas Comuns e Alcalinas** | Lixiviação de zinco, manganês e cádmio bioacumulativos no lençol freático | Armazenar em garrafa PET fechada; fita isolante nos terminais de 9V | Coletores de pilhas em supermercados, agências dos Correios ou IFF |
| **Baterias de Chumbo-Ácido** | Ácido sulfúrico altamente corrosivo e até 10 kg de chumbo causador de saturnismo | Manter rigorosamente na vertical; não deitar nem drenar a solução ácida | Troca obrigatória na aquisição da bateria substituta em revendedoras |
| **Smartphones e Tablets** | Retardantes bromados (BFRs), metais pesados em trilhas e estufamento de baterias | Fazer backup de dados, restaurar os padrões de fábrica e preservar a tela | Balcão Cidadão dos Correios, lojas de operadoras ou PEV do IFF |
| **Placas-mãe e Circuitos** | Soldas com liga estanho-chumbo e poeira metálica perigosa caso trituradas | Acondicionar em caixas rígidas para evitar fraturas nas placas | Oficinas pedagógicas de hardware do IFF ou Projeto Circuito Verde |
| **Fontes, Cabos e Conectores** | Dioxinas cancerígenas liberadas na queima ilegal para obtenção do cobre | Enrolar sem nós apertados e preservar os conectores originais | Aulas práticas de montagem do IFF ou caixa de fiação do PEV |
| **Monitores CRT e Telas LCD** | Até 2 kg de óxido de chumbo no cone de vidro (CRT) e vapor de mercúrio em lâmpadas CCFL | Nunca quebrar o vidro ou o gabinete plástico; transportar apoiado | Agendamento na Secretaria Municipal de Meio Ambiente ou campanhas IFF |
| **Eletrodomésticos Pequenos** | Volume maciço de carcaças termoplásticas não biodegradáveis e motores | Higienizar resíduos de alimentos e fluidos antes da entrega | Associações locais de catadores ou oficinas de conserto elétrico |

---

## Projeto Institucional no IFF

A proposta articula uma solução sistêmica permanente para o *Campus* Bom Jesus do Itabapoana baseada em três pilares:

```
[ Comunidade / Munícipes ]
           │
           ▼
┌──────────────────────────────────────┐
│  Ponto de Entrega Voluntária (PEV)   │  <-- Resolução INEA n.º 183/2019
│     no IFF Campus Bom Jesus          │      (Triagem rápida sem desmonte industrial)
└──────────────────┬───────────────────┘
                   │
         ┌─────────┴─────────┐
         ▼                   ▼
┌─────────────────┐ ┌──────────────────────────────────────┐
│ Itens Funcionais│ │      Lotes de Sucata Homologada      │
│   e Componentes │ └──────────────────┬───────────────────┘
│   Pedagógicos   │                    │ Transporte seguro (67 km)
└────────┬────────┘                    ▼
         │          ┌──────────────────────────────────────┐
         │          │     Projeto Circuito Verde (IFF)     │
         │          │         Campus Guarus / Campos       │
         │          └──────────────────┬───────────────────┘
         │                             │ Contratos de reciclagem
         ▼                             ▼
┌─────────────────┐ ┌──────────────────────────────────────┐
│ Aulas Práticas  │ │  Indústrias de Fundição e Refino     │
│ Eng. Computação │ │      (Logística Reversa Certificada) │
└─────────────────┘ └──────────────────────────────────────┘
```

1. **PEV no IFF BJI com Amparo na Resolução INEA n.º 183/2019:** Dispensa de licenciamento ambiental para pontos de entrega e segregação primária de REEE que não realizem desmonte químico ou descaracterização industrial no local.
2. **Integração com o Circuito Verde (IFF Campus Guarus):** Encaminhamento periódico de lotes consolidados de sucata ao projeto institucional já consolidado no Campus Guarus, que mantém convênios formais com empresas homologadas de reciclagem.
3. **Passada de Bastão Interdisciplinar:** A Engenharia de Computação realizou a concepção técnica, modelagem logística e implementação do software. A rotina contínua de operação do PEV, campanhas em escolas da rede municipal e monitoramento de bioindicadores da bacia do Rio Itabapoana fica a cargo do curso Técnico em Meio Ambiente.

---

## Tríade Documental no ReLaTeX

Toda a documentação acadêmica e material gráfico de apoio foi elaborada e compilada com precisão no sistema **ReLaTeX** (instância institucional TeX Live 2026), garantindo 0 erros de compilação:

| Documento | Classe / Modelo | Extensão | Descrição |
| :--- | :--- | :---: | :--- |
| **Relatório Técnico** | `iffrelatorio` | 18 páginas | Relatório formal com fundamentação teórica, objetivos, ODS da ONU, fichamento do PMGIRS e modelagem do PEV |
| **Slides da Apresentação** | `iffslides` | 36 lâminas | Apresentação visual widescreen sincronizada com o roteiro de oratória e identidade visual do IFF |
| **Roteiro de Oratória** | `iffdoc` | 8 páginas | Roteiro com marcação de tempo (15 min de apresentação + 10 min de arguição), tópicos e falas dos autores |
| **Panfleto Impresso (Guia A4)** | `iffdoc` (Landscape) | 2 páginas | Panfleto horizontal A4 frente e verso formatado em cartões para impressão e distribuição escolar |

> **Nota:** Os arquivos PDF completos da tríade estão sob avaliação da banca examinadora e serão liberados para download público após a defesa oficial no portfólio dos autores.

---

## Marcos Legais e Diagnóstico Municipal

O projeto fundamenta-se estritamente na legislação ambiental brasileira e estadual:

- **Lei Federal n.º 12.305/2010 (PNRS):** Institui a Política Nacional de Resíduos Sólidos e fixa o princípio da responsabilidade compartilhada pelo ciclo de vida dos produtos.
- **Decreto Federal n.º 10.240/2020:** Regulamenta a logística reversa de produtos eletroeletrônicos de uso doméstico e estabelece metas progressivas de recolhimento no território nacional.
- **Resolução CONAMA n.º 401/2008:** Estabelece os teores máximos de chumbo, cádmio e mercúrio e determina a obrigatoriedade da devolução de pilhas e baterias aos fabricantes e importadores.
- **Resolução INEA n.º 183/2019 (RJ):** Regulamenta os sistemas de logística reversa no Estado do Rio de Janeiro e concede isenção de licenciamento ambiental a pontos de triagem rápida sem desmonte.
- **PMGIRS Bom Jesus do Itabapoana (2024):** Atesta a inexistência de aterro sanitário municipal e a necessidade de mitigação do transbordo rodoviário por 67 km.
- **PMGIRS Campos dos Goytacazes (2024):** Regulamenta as diretrizes do consórcio regional e a operação do aterro sanitário licenciado CTR Campos.

---

## Estrutura do Repositório

```
guia-elixo/
├── .editorconfig                  # Configuração de indentação e charset UTF-8
├── .github/                       # Modelos de issues, pull requests e codeowners
│   ├── CODEOWNERS
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml
│   │   ├── feature_request.yml
│   │   └── config.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── CHANGELOG.md                   # Histórico de alterações seguindo Keep a Changelog
├── CITATION.cff                   # Metadados de citação acadêmica em formato CFF 1.2.0
├── CODE_OF_CONDUCT.md             # Código de conduta para colaboradores
├── CONTRIBUTING.md                # Diretrizes de contribuição e convenções de commit
├── LICENSE                        # Licença de código aberto (MIT)
├── README.md                      # Documentação técnica do repositório
├── SECURITY.md                    # Diretrizes de reporte confidencial de segurança
├── SUPPORT.md                     # Canais de suporte e dúvidas sobre o projeto
└── index.html                     # Código-fonte da aplicação web (HTML5, CSS3, JS Vanilla)
```

---

## Como Executar Localmente

Como a aplicação é constituída em arquitetura estática pura (*vanilla*), não é necessária a instalação de dependências pesadas, compiladores ou gerenciadores de pacotes.

### 1. Clonar o repositório
```bash
git clone https://github.com/pedroiff0/guia-elixo.git
cd guia-elixo
```

### 2. Executar via servidor local
Você pode abrir o arquivo `index.html` diretamente em seu navegador web ou iniciar um servidor HTTP local simples:

**Com Python 3:**
```bash
python3 -m http.server 8000
```

**Com Node.js (npx):**
```bash
npx serve .
```

Acesse a aplicação no navegador em `http://localhost:8000`.

---

## Autores & Orientação

<div align="center">

### Equipe Discente (Engenharia de Computação - IFF BJI)

| Foto | Autor | E-mail Institucional | Função no Projeto |
| :---: | :--- | :--- | :--- |
| <img src="https://ui-avatars.com/api/?name=Bento+Neto&background=1b5e20&color=fff&size=80" width="60" style="border-radius:50%" /> | **Bento Fernandes da Silva Neto** | `bento.neto@gsuite.iff.edu.br` | Fundamentação Teórica & Metodologia |
| <img src="https://ui-avatars.com/api/?name=Bernardo+Rainha&background=1b5e20&color=fff&size=80" width="60" style="border-radius:50%" /> | **Bernardo Rainha Gomes** | `b.rainha@gsuite.iff.edu.br` | Diagnóstico Regional & Levantamento PMGIRS |
| <img src="https://ui-avatars.com/api/?name=Pedro+Miranda&background=1b5e20&color=fff&size=80" width="60" style="border-radius:50%" /> | **Pedro Henrique Miranda de Oliveira** | `p.h.miranda1712@gmail.com` | Roteiro de Oratória & Articulação Interdisciplinar |
| <img src="https://github.com/pedroiff0.png?size=80" width="60" style="border-radius:50%" /> | **Pedro Henrique Rocha de Andrade** | `pedroiff0@gmail.com` | Arquitetura Web, Sistema TeX & Modelagem do PEV |

### Corpo Docente Orientador

| Docente | Titulação / Lotação | Perfil Institucional | Papel |
| :--- | :--- | :---: | :--- |
| **Prof. Me. Rafael Ferreira Tardin da Silva** | Mestre em Filosofia / IFF Campus Bom Jesus | [Integra IFF](https://integra.iff.edu.br/ecossistema/pessoas/rafael-ferreira-tardin-da-silva/rafael%20tardin) | Professor Orientador da Disciplina |
| **Prof. Dr. Rafael Artur de Paiva Gardoni** | Doutor em Engenharia / IFF Campus Bom Jesus | [Integra IFF](https://integra.iff.edu.br/ecossistema/pessoas/rafael-artur-de-paiva-gardoni/Rafael%20Gardoni) | Professor Patrono / Avaliador |

</div>

---

## Como Citar

Se este trabalho, arquitetura ou banco de dados for útil para pesquisas acadêmicas ou projetos de extensão, cite-o através dos metadados de [CITATION.cff](CITATION.cff):

```bibtex
@misc{silvaneto2026elixo,
  author       = {Silva Neto, Bento Fernandes da and Rainha Gomes, Bernardo and Miranda de Oliveira, Pedro Henrique and Rocha de Andrade, Pedro Henrique},
  title        = {Guia Prático de Descarte de Resíduos Eletroeletrônicos e Baterias (E-Lixo)},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/pedroiff0/guia-elixo}},
  note         = {Instituto Federal Fluminense, Campus Bom Jesus do Itabapoana}
}
```

---

## Licença

Este projeto é distribuído sob os termos da licença de código aberto **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

Documentos técnicos, textos dos relatórios e gráficos acadêmicos são licenciados sob **Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)**.

---

<div align="center">

<sub>Instituto Federal de Educação, Ciência e Tecnologia Fluminense (IFF) · Campus Bom Jesus do Itabapoana</sub><br>
<sub>Bacharelado em Engenharia de Computação · Disciplina de Filosofia da Ciência e Tecnologia (2026/2)</sub>

</div>
