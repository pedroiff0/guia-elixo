# Guia de Descarte de Resíduos Eletroeletrônicos e Baterias (E-Lixo)

[![Licença MIT](https://img.shields.io/badge/licença-MIT-green?style=flat)](LICENSE)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat)](#status)
[![HTML5](https://img.shields.io/badge/HTML5-Semântico-E34F26?style=flat&logo=html5&logoColor=white)](https://elixo.phrandrade.com)
[![CSS3](https://img.shields.io/badge/CSS3-Responsivo-1572B6?style=flat&logo=css3&logoColor=white)](https://elixo.phrandrade.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://elixo.phrandrade.com)
[![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-199900?style=flat&logo=leaflet&logoColor=white)](https://elixo.phrandrade.com/#mapa)
[![LaTeX](https://img.shields.io/badge/LaTeX-ReLaTeX-008080?style=flat&logo=latex&logoColor=white)](#tríade-documental-no-relatex)
[![IFF](https://img.shields.io/badge/IFF-Campus%20Bom%20Jesus-1b5e20?style=flat)](https://portal1.iff.edu.br/nossos-campi/bom-jesus-do-itabapoana)

Plataforma web cidadã de consulta rápida, catálogo reativo com 34 grupos de resíduos, mapa territorial de logística reversa e modelagem técnica de Ponto de Entrega Voluntária (PEV) no Instituto Federal Fluminense.

[Resumo](#resumo) · [Contexto](#contexto) · [Tecnologias](#tecnologias) · [Como usar](#como-usar) · [Catálogo](#catálogo-de-resíduos-e-baterias) · [Mapa Regional](#mapa-regional-dos-campi-do-iff) · [Autores](#autores) · [Como citar](#como-citar) · [Licença](#licença)

---

## Sumário

- [Resumo](#resumo)
- [Contexto](#contexto)
- [Tecnologias](#tecnologias)
  - [Stack](#stack)
- [Acesso Online & Demonstração](#acesso-online--demonstração)
- [Como usar](#como-usar)
- [Catálogo de Resíduos e Baterias](#catálogo-de-resíduos-e-baterias)
- [Mapa Regional dos Campi do IFF](#mapa-regional-dos-campi-do-iff)
- [Projeto Institucional no IFF](#projeto-institucional-no-iff)
- [Tríade Documental no ReLaTeX](#tríade-documental-no-relatex)
- [Marcos Legais e Diagnóstico Municipal](#marcos-legais-e-diagnóstico-municipal)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Status](#status)
- [Como citar](#como-citar)
- [Como contribuir](#como-contribuir)
- [Código de conduta](#código-de-conduta)
- [Segurança](#segurança)
- [Suporte](#suporte)
- [Autores](#autores)
- [Agradecimentos](#agradecimentos)
- [Referências](#referências)
- [Licença](#licença)

---

## Resumo

Trabalho prático integrador da disciplina Filosofia da Ciência e Tecnologia (Bacharelado em Engenharia de Computação, IFF Campus Bom Jesus do Itabapoana, 2026/2): diagnosticar o passivo ambiental de resíduos eletroeletrônicos e baterias no Noroeste Fluminense sob as teorias da responsabilidade tecnológica (Hans Jonas), da modernidade líquida e obsolescência (Zygmunt Bauman) e da filosofia da técnica (Alberto Cupani). O projeto concebeu uma solução em três frentes integradas: uma aplicação web responsiva com busca instantânea sobre 34 resíduos, a modelagem de um Ponto de Entrega Voluntária (PEV) no campus BJI amparado na Resolução INEA n.º 183/2019 com transporte homologado de 67 km até o Projeto Circuito Verde (IFF Campus Guarus), e a transferência de operação ao curso Técnico em Meio Ambiente para continuidade nas escolas municipais.

---

## Contexto

| Campo | Valor |
| :--- | :--- |
| **Instituição** | Instituto Federal de Educação, Ciência e Tecnologia Fluminense (IFF) |
| **Campus** | Campus Bom Jesus do Itabapoana - RJ |
| **Curso e disciplina** | Bacharelado em Engenharia de Computação · Filosofia da Ciência e Tecnologia |
| **Período** | 6.º período, 2026/2 |
| **Professor Orientador** | Prof. Me. Rafael Ferreira Tardin da Silva |
| **Professor Patrono** | Prof. Dr. Rafael Artur de Paiva Gardoni |
| **Autores** | Bento Fernandes, Bernardo Rainha, Pedro Henrique Miranda, Pedro Henrique Rocha de Andrade |
| **Base Municipal** | Plano Municipal de Gestão Integrada de Resíduos Sólidos (PMGIRS BJI 2024) |

### Objetivos

1. Mapear o gargalo socioambiental de Bom Jesus do Itabapoana decorrente da inexistência de aterro sanitário próprio (transbordo de 0,724 kg/hab/dia por 67 km de rodovia até o aterro consorciado CTR Campos).
2. Criar uma plataforma digital intuitiva e aberta orientando os cidadãos sobre como preparar cada resíduo com segurança e onde descartá-lo.
3. Modelar o fluxo de logística reversa e a passada de bastão interdisciplinar entre a Engenharia de Computação e o curso Técnico em Meio Ambiente no IFF.

---

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
![ReLaTeX](https://img.shields.io/badge/ReLaTeX-Overleaf%20Fork-2E7D32?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-Vetorial-FFB13B?style=flat)

### Stack

| Camada | Tecnologia | Uso |
| :--- | :--- | :--- |
| **Interface Cidadã** | HTML5 semântico e CSS3 puro | Aplicação web leve, responsiva e acessível para dispositivos móveis |
| **Lógica de Consulta** | JavaScript Vanilla (ES6+) | Filtragem instantânea por texto e categorias, sem frameworks pesados |
| **Georreferenciamento** | SVG Vetorial Nativo | Mapa esquemático interativo dos campi do IFF e do eixo de 67 km |
| **Documentação Técnica** | LaTeX / ReLaTeX | Editoração do Relatório ABNT (`iffrelatorio`), Slides (`iffslides`) e Panfleto (`iffdoc`) |
| **Hospedagem & Deploy** | GitHub Pages & Domínio Próprio | Distribuição de alta disponibilidade em `elixo.phrandrade.com` |

---

## Acesso Online & Demonstração

- **Portal Oficial:** [https://elixo.phrandrade.com](https://elixo.phrandrade.com)
- **Espelho GitHub Pages:** [https://pedroiff0.github.io/guia-elixo/](https://pedroiff0.github.io/guia-elixo/)
- **Portfólio Institucional:** [https://portfolio.phrandrade.com](https://portfolio.phrandrade.com)

---

## Como usar

Tempo estimado: 2 minutos.

### Execução Local

```bash
git clone https://github.com/pedroiff0/guia-elixo.git
cd guia-elixo
python3 -m http.server 8000
```

Abra o navegador em `http://localhost:8000`. A aplicação carrega imediatamente sem necessidade de instalação de pacotes (`npm` ou `pip`).

---

## Catálogo de Resíduos e Baterias

O banco de dados conta com **34 itens** categorizados, detalhando para cada um o risco, a preparação obrigatória e a base legal:

| Categoria | Itens Cadastrados | Risco Principal | Preparo Recomendado |
| :--- | :--- | :--- | :--- |
| **Baterias** (8 itens) | Celular, notebook, bicicleta elétrica, powerbank, automotiva, nobreak, ferramentas, recarregáveis | Fuga térmica (*thermal runaway*), gases de cobalto e ácido sulfúrico | Isolar os polos metálicos com fita adesiva e manter em recipientes secos |
| **Pilhas** (4 itens) | AA, AAA, retangular 9V, botão CR2032, relógio/auditivo | Cádmio, zinco e manganês bioacumulativos no solo e risco de curto | Guardar em garrafa PET fechada; cobrir contatos de 9V e botão com fita |
| **Celulares & Telefonia** (6 itens) | Smartphones, celulares antigos, tablets, fones sem fio TWS, fones com fio, carregadores | Metais pesados em trilhas e baterias estufadas sob sol | Backup de segurança, restauração de fábrica e preservação da carcaça |
| **Informática & Peças** (12 itens) | Placas-mãe, GPUs, memórias, fontes ATX, HDDs, SSDs, teclados, mouses, roteadores, cabos, monitores CRT, telas LCD/LED, impressoras e toners | Óxido de chumbo em tubos CRT, vapor de mercúrio em LCDs e choque em capacitores | Nunca quebrar tubos de vidro nem queimar fios de cobre a céu aberto |
| **Eletrodomésticos** (2 itens) | Micro-ondas, ferros, liquidificadores, batedeiras e ventiladores | Alta tensão residual em capacitores e volume excessivo em aterros | Limpar resíduos de pó/líquidos e enrolar cabos na base do motor |
| **Lâmpadas** (2 itens) | Fluorescentes compactas/tubulares e lâmpadas LED | Vapor de mercúrio puro inalável em caso de quebra doméstica | Se quebrar, arejar o ambiente por 15 min; entregar inteira na loja de compra |

---

## Mapa Regional dos Campi do IFF

A aplicação inclui um mapa esquemático vetorial demonstrando o eixo de escoamento e cooperação técnica regional:

```
[ Noroeste Fluminense ]                           [ Norte Fluminense ]
IFF Campus Bom Jesus                                IFF Campus Guarus (Campos)
        │                                                   ▲
        │  Triagem primária sem desmonte                    │  Projeto Circuito Verde
        │  (Resolução INEA n.º 183/2019)                   │  (Desmonte técnico & reciclagem)
        └───────────────── Rota Rodoviária ─────────────────┘
                              67 km (RJ-230 / BR-356)
                              Sistema MTR Homologado
```

- **Ponto de Origem (BJI):** Recebimento comunitário e segregação primária entre peças para oficinas escolares e lotes de sucata.
- **Ponto de Destino (Guarus):** Estrutura laboratorial consolidada com contratos formais com fundições e recicladoras certificadas.

---

## Projeto Institucional no IFF

1. **PEV no Campus Bom Jesus:** Amparado pela Resolução INEA n.º 183/2019, que dispensa licenciamento ambiental complexo para pontos de entrega voluntária de triagem rápida sem desmonte industrial.
2. **Parceria com o Circuito Verde:** Aproveitamento da cadeia de logística reversa já credenciada no IFF Campus Guarus, evitando o descarte no Rio Itabapoana ou o envio indevido ao aterro sanitário de Campos.
3. **Passada de Bastão Interdisciplinar:** A Engenharia de Computação realizou o desenho técnico e a plataforma web; o curso Técnico em Meio Ambiente assume a rotina operacional, campanhas em escolas municipais e o monitoramento ambiental continuado.

---

## Tríade Documental no ReLaTeX

Todo o corpo de documentação foi desenvolvido e compilado no sistema **ReLaTeX** com as classes institucionais do IFF:

| Documento | Classe / Modelo | Extensão | Estado |
| :--- | :--- | :---: | :--- |
| **Relatório Técnico** | `iffrelatorio` | 18 páginas | Concluído (sob avaliação da banca) |
| **Slides da Apresentação** | `iffslides` | 36 lâminas | Concluído (sob avaliação da banca) |
| **Roteiro de Oratória** | `iffdoc` | 8 páginas | Concluído (15 min apresentação + 10 min arguição) |
| **Panfleto Impresso (Guia A4)** | `iffdoc` | 1 página | Concluído (formato síntese TLDR com QR Code) |

---

## Marcos Legais e Diagnóstico Municipal

- **Lei Federal n.º 12.305/2010 (PNRS):** [Texto no Planalto](https://www.planalto.gov.br/ccivil_03/_ato2007-2010/2010/lei/l12305.htm)
- **Decreto Federal n.º 10.240/2020:** [Texto no Planalto](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2020/decreto/d10240.htm)
- **Resolução CONAMA n.º 401/2008:** [PDF Oficial](docs/leis/resolucao-conama-401-2008.pdf) · [Consulta LegisWeb](https://www.legisweb.com.br/legislacao/?id=72929)
- **Resolução INEA n.º 183/2019 (RJ):** [PDF Oficial](docs/leis/resolucao-inea-183-2019.pdf) · [Consulta LegisWeb](https://www.legisweb.com.br/legislacao/?id=388039)
- **PMGIRS Bom Jesus do Itabapoana (2024):** [PDF Oficial PMGIRS](https://bomjesus.rj.gov.br/uploads/35604723c1c66d245da60cca87be151183752862.pdf)
- **PMGIRS Campos dos Goytacazes (2024):** [PDF Oficial PMGIRS](https://campos.rj.gov.br/wp-content/uploads/2026/08/residuos_solidos-versao_final_pmgirs.pdf)

---

## Estrutura do Repositório

```
guia-elixo/
├── .editorconfig
├── .github/
│   ├── CODEOWNERS
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
├── CHANGELOG.md
├── CITATION.cff
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── docs/
│   └── leis/
│       ├── resolucao-conama-401-2008.pdf
│       └── resolucao-inea-183-2019.pdf
├── index.html
├── LICENSE
├── README.md
├── SECURITY.md
└── SUPPORT.md
```

---

## Status

Projeto concluído e submetido para avaliação acadêmica em 15/11/2026.

- [x] Aplicação web reativa com 34 resíduos catalogados
- [x] Mapa regional SVG integrando os campi do IFF
- [x] Hospedagem local de PDFs do CONAMA 401 e INEA 183
- [x] Relatório técnico de 18 páginas em `iffrelatorio`
- [x] Lâminas de slides em `iffslides` e roteiro de oratória em `iffdoc`
- [x] Panfleto impresso de 1 página com síntese visual e QR code

---

## Como citar

O repositório fornece metadados no padrão [CITATION.cff](CITATION.cff):

```bibtex
@misc{silvaneto2026elixo,
  author       = {Silva Neto, Bento Fernandes da and Rainha Gomes, Bernardo and Miranda de Oliveira, Pedro Henrique and Rocha de Andrade, Pedro Henrique},
  title        = {Guia de Descarte de Resíduos Eletroeletrônicos e Baterias (E-Lixo)},
  year         = {2026},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/pedroiff0/guia-elixo}},
  note         = {Instituto Federal Fluminense, Campus Bom Jesus do Itabapoana}
}
```

---

## Como contribuir

Contribuições e sugestões são bem-vindas através de [CONTRIBUTING.md](CONTRIBUTING.md).

1. Abra uma issue detalhando o resíduo ou ponto de coleta a adicionar.
2. Crie uma branch a partir de `main`: `git checkout -b feat/novo-residuo`.
3. Faça commits no padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/).
4. Abra o Pull Request para revisão.

---

## Código de conduta

Este projeto adota o [Código de Conduta](CODE_OF_CONDUCT.md) do ecossistema de software do IFF.

---

## Segurança

Diretrizes para relato responsável de vulnerabilidades disponíveis em [SECURITY.md](SECURITY.md).

---

## Suporte

Para dúvidas e esclarecimentos sobre a pesquisa ou aplicação web, consulte [SUPPORT.md](SUPPORT.md).

---

## Autores & Equipe Discente

<div align="center">

<table>
  <tr>
    <td align="center"><img src="https://ui-avatars.com/api/?name=Bento+Neto&background=1b5e20&color=fff&size=140" width="96" height="96" alt="Bento Fernandes" /><br /><sub><b>Bento Fernandes da Silva Neto</b></sub><br />Fundamentação &amp; Metodologia<br /><code>bento.neto@gsuite.iff.edu.br</code></td>
    <td align="center"><img src="https://ui-avatars.com/api/?name=Bernardo+Rainha&background=1b5e20&color=fff&size=140" width="96" height="96" alt="Bernardo Rainha" /><br /><sub><b>Bernardo Rainha Gomes</b></sub><br />Diagnóstico &amp; Levantamento PMGIRS<br /><code>b.rainha@gsuite.iff.edu.br</code></td>
    <td align="center"><img src="https://ui-avatars.com/api/?name=Pedro+Miranda&background=1b5e20&color=fff&size=140" width="96" height="96" alt="Pedro Miranda" /><br /><sub><b>Pedro Henrique Miranda de Oliveira</b></sub><br />Roteiro de Oratória &amp; Articulação<br /><code>p.h.miranda1712@gmail.com</code></td>
    <td align="center"><a href="https://github.com/pedroiff0"><img src="https://github.com/pedroiff0.png?size=140" width="96" height="96" alt="Pedro Henrique Rocha de Andrade" /><br /><sub><b>Pedro Henrique Rocha de Andrade</b></sub></a><br />Arquitetura Web &amp; Modelagem do PEV<br /><code>pedroiff0@gmail.com</code></td>
  </tr>
</table>

</div>

### Professores Orientador e Patrono (Integra IFF)

<div align="center">

<table>
  <tr>
    <td align="center" width="50%"><img src="https://ui-avatars.com/api/?name=Rafael+Tardin&background=0d3311&color=fff&size=160" width="96" height="96" alt="Prof. Rafael Tardin" /><br /><sub><b>Prof. Me. Rafael Ferreira Tardin da Silva</b></sub><br />Professor Orientador (Filosofia da Ciência e Tecnologia / IFF)<br /><a href="https://integra.iff.edu.br/ecossistema/pessoas/rafael-ferreira-tardin-da-silva/rafael%20tardin"><b>Perfil Oficial no Integra IFF</b></a></td>
    <td align="center" width="50%"><img src="https://ui-avatars.com/api/?name=Rafael+Gardoni&background=0d3311&color=fff&size=160" width="96" height="96" alt="Prof. Rafael Gardoni" /><br /><sub><b>Prof. Dr. Rafael Artur de Paiva Gardoni</b></sub><br />Professor Patrono &amp; Colaborador (Engenharia / IFF)<br /><a href="https://integra.iff.edu.br/ecossistema/pessoas/rafael-artur-de-paiva-gardoni/Rafael%20Gardoni"><b>Perfil Oficial no Integra IFF</b></a></td>
  </tr>
</table>

</div>

---

## Agradecimentos

Agradecemos ao professor orientador **Prof. Me. Rafael Ferreira Tardin da Silva** pela condução crítica e metodológica, e ao professor patrono **Prof. Dr. Rafael Artur de Paiva Gardoni** pelo suporte técnico sobre a matriz de resíduos da região.

---

## Referências

1. BRASIL. *Lei n.º 12.305, de 2 de agosto de 2010*. Institui a Política Nacional de Resíduos Sólidos (PNRS).
2. BRASIL. *Decreto n.º 10.240, de 12 de fevereiro de 2020*. Regulamenta a logística reversa de eletroeletrônicos domiciliares.
3. CONAMA. *Resolução n.º 401, de 4 de novembro de 2008*. Limites de metais pesados e descarte de pilhas e baterias.
4. INEA. *Resolução n.º 183, de 12 de julho de 2019*. Dispensa de licenciamento ambiental de Pontos de Entrega Voluntária no Estado do Rio de Janeiro.
5. BOM JESUS DO ITABAPOANA. *Plano Municipal de Gestão Integrada de Resíduos Sólidos (PMGIRS)*. Prefeitura Municipal, 2024.
6. CAMPOS DOS GOYTACAZES. *Plano Municipal de Gestão Integrada de Resíduos Sólidos (PMGIRS)*. Prefeitura Municipal, 2024.
7. JONAS, Hans. *O Princípio Responsabilidade: Ensaio de uma ética para a civilização tecnológica*. Rio de Janeiro: Contraponto, 2006.
8. BAUMAN, Zygmunt. *Vida para Consumo: A transformação das pessoas em mercadoria*. Rio de Janeiro: Jorge Zahar, 2008.
9. CUPANI, Alberto. *Filosofia da Tecnologia: Um convite à reflexão*. Florianópolis: Editora da UFSC, 2016.

---

## Licença

Distribuído sob a licença **MIT** para código-fonte (veja [LICENSE](LICENSE)) e **Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)** para o conteúdo textual e documentação acadêmica.

---

<div align="center">

<a href="https://portfolio.phrandrade.com"><img src="https://github.com/pedroiff0.png?size=96" width="48" height="48" style="border-radius:50%; border:2px solid #166534;" alt="Pedro Henrique Rocha de Andrade" /></a>

<br />

<b>Pedro Henrique Rocha de Andrade</b><br />
<sub>Engenharia de Computação · Instituto Federal Fluminense (IFF)</sub><br />
<sub>Pesquisador de Astronomia &amp; Desenvolvedor de Software</sub>

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-phrandrade.com-1b5e20?style=flat-square&logo=googlechrome&logoColor=white)](https://portfolio.phrandrade.com)
[![GitHub](https://img.shields.io/badge/GitHub-pedroiff0-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pedroiff0)
[![Website](https://img.shields.io/badge/Guia_E--Lixo-elixo.phrandrade.com-2e7d32?style=flat-square&logo=safari&logoColor=white)](https://elixo.phrandrade.com)

<br />

*"Responsabilidade técnica a favor do ambiente regional."*

<br />

<sub>© 2026 Instituto Federal Fluminense · Campus Bom Jesus do Itabapoana</sub>

</div>
