# PisoFacil

Repositorio destinado ao desenvolvimento, documentacao e prototipagem do projeto de extensao PisoFacil, desenvolvido como parte da disciplina Praticas de Gestao de Projetos do curso de Sistemas para Internet da Fatec Sao Roque.

---

## Sobre o Projeto

O PisoFacil e um projeto de extensao universitaria que tem como objetivo desenvolver uma presenca digital para Daniel Laranjeira, profissional autonomo especializado em restauracao e revitalizacao de pisos de madeira em Ibiuna e regiao, no estado de Sao Paulo.

O projeto engloba o planejamento completo de gestao, a prototipagem visual baseada em design aprovado no Figma e a implementacao de uma landing page estatica (MVP) que serve como vitrine digital do servico. O cliente pode entrar em contato diretamente pelo WhatsApp a partir da pagina.

---

## Estrutura do Repositorio

```
Piso-Facil/
|
|-- Checklist/
|-- Contratos/
|-- Diario-de-Bordo/
|-- documentos/
|-- Evidencias/
|   |-- Atas/
|-- Material-Apoio/
|-- MVP/
|   |-- assets/
|   |-- index.html
|   |-- style.css
|   |-- app.js
|-- README.md
```

---

## Descricao das Pastas

### Checklist

Contem as listas de verificacao dos entregaveis do projeto, utilizadas para acompanhar o progresso das etapas e garantir que todos os requisitos da disciplina foram atendidos.

Arquivos presentes:
- `Entregaveis Projeto Extensao Praticas de Gestao de Projetos.md` — lista detalhada dos entregaveis esperados ao longo do projeto.
- `Fatec São Roque - Sistemas para Internet - Práticas de Gestão de Projetos.md` — referencia ao plano de ensino e criterios de avaliacao da disciplina.

---

### Contratos

Contem os documentos formais que formalizam a relacao entre a equipe do projeto e o cliente (Daniel Laranjeira).

Arquivos presentes:
- `Termo_de_Anuencia_PisoFacil.docx` — termo de anuencia assinado pelo cliente, autorizando o desenvolvimento do projeto de extensao e o uso de informacoes para fins academicos.

---

### Diario-de-Bordo

Registro cronologico do andamento do projeto, utilizado para documentar o que foi realizado em cada encontro, decisoes tomadas, dificuldades encontradas e proximos passos definidos.

Arquivos presentes:
- `Diario_de_bordo_PisoFacil.xlsx` — planilha de diario de bordo com colunas de data, atividades realizadas, participantes e observacoes.

---

### documentos

Pasta central com todos os artefatos formais de gestao de projetos produzidos ao longo da disciplina. Cada documento segue metodologias e boas praticas do PMBOK.

Arquivos presentes:
- `01_Identificacao.docx` — identificacao do projeto, contendo nome, descricao resumida, cliente e equipe responsavel.
- `02_TAP_PisoFacil.docx` — Termo de Abertura do Projeto (TAP), documento que formaliza o inicio do projeto, define objetivo, escopo preliminar, partes interessadas e premissas.
- `03_Stakeholders_PisoFacil.docx` — mapeamento e analise das partes interessadas (stakeholders), com nivel de influencia e estrategias de engajamento.
- `CicloDeVida-Governanca.docx` — documento que descreve o ciclo de vida adotado no projeto e as praticas de governanca utilizadas pela equipe.
- `Cronograma_PisoFacil.docx` — cronograma do projeto com as fases, atividades, responsaveis e prazos estabelecidos.
- `EAP-DIAGRAMA.jpg.jpeg` — diagrama da Estrutura Analitica do Projeto (EAP), representando a decomposicao hierarquica de todo o trabalho do projeto.
- `Gestão da Integração e Escopo.pdf` — documento de gestao da integracao e do escopo, incluindo o plano de gerenciamento e o controle de mudancas.
- `Orcamento_PisoFacil.xlsx` — planilha de orcamento do projeto com estimativas de custos, recursos e horas dedicadas.

---

### Evidencias

Pasta destinada ao armazenamento das evidencias formais de reunioes, validacoes e entregas realizadas ao longo do projeto.

#### Evidencias/Atas

Subpasta contendo as atas de reuniao registradas em cada encontro formal com o cliente ou com a equipe de projeto.

Arquivos presentes:
- `Modelo_Ata_Validacao_Escopo_TAP_Preenchido_v2 (1).docx` — ata da reuniao de validacao do escopo e do TAP com o cliente.
- `ata2_validacao-do-prototipo-visual (1).docx` — ata da segunda reuniao, referente a validacao do prototipo visual (Figma) com o cliente.
- `Ata 3_ Recebimento de Materiais e Acompanhamento - PisoFácil.docx` — ata da terceira reuniao, registrando o recebimento de materiais do cliente e o acompanhamento do projeto.
- `Ata 4_ Testes de Usabilidade e Homologação do MVP - PisoFácil.docx` — ata da quarta reuniao, documentando os testes de usabilidade realizados e a homologacao do MVP pelo cliente.

---

### Material-Apoio

Pasta com materiais de referencia utilizados pela equipe para embasar decisoes tecnicas e academicas ao longo do projeto.

Arquivos presentes:
- `Fatec São Roque - Sistemas para Internet - Práticas de Gestão de Projetos.pdf` — plano de ensino da disciplina com criterios, prazos e orientacoes.
- `Gestao de Projetos.pdf` — material de apoio teorico sobre gestao de projetos, utilizado como referencia metodologica.

---

### MVP

Pasta contendo o codigo-fonte do prototipo funcional (Minimum Viable Product) da landing page do PisoFacil. O MVP foi desenvolvido inteiramente em HTML5 e CSS3 puro, sem dependencias de frameworks ou bibliotecas externas, e com fidelidade ao design aprovado no Figma.

A pagina e composta por nove secoes:

1. Navegacao — header com menu de ancoras e botao de CTA para o WhatsApp.
2. Apresentacao — hero com titulo principal, descricao do servico e imagem de destaque.
3. Servicos — grade com os tres servicos oferecidos: Restauracao, Revitalizacao e Acabamentos.
4. Galeria e Antes e Depois — comparacao visual ilustrativa e grade de seis estudos de ambientes.
5. Como Pedir seu Orcamento — tres etapas simplificadas do processo de contato.
6. Sobre Daniel Laranjeira — apresentacao do profissional e informacoes de atendimento regional.
7. Preservacao da Madeira — banner com manifesto sobre sustentabilidade e preservacao.
8. Duvidas Frequentes — secao de FAQ com acordeao nativo em HTML5 (elemento details/summary).
9. Contato e Orcamento — formulario de abertura de conversa com sugestao de mensagem para WhatsApp.
10. Rodape — identidade da marca, links de navegacao, CTA e informacoes legais.

Arquivos presentes:
- `index.html` — estrutura completa da landing page em HTML5 semantico.
- `style.css` — todos os estilos visuais da pagina, incluindo variaveis CSS, layout responsivo e estados interativos.
- `app.js` — arquivo JavaScript reservado para futuras interacoes dinamicas (atualmente vazio, sem dependencias de JS na pagina atual).

#### MVP/assets

Subpasta com todos os recursos visuais utilizados na landing page. Os arquivos foram extraidos diretamente do projeto no Figma via MCP, garantindo fidelidade ao design original.

Imagens:
- `hero-piso.png` — imagem principal da secao de apresentacao (piso com luz natural).
- `comparacao-ambiente.png` — imagem utilizada no bloco de comparacao antes e depois.
- `contato-ambiente.png` — imagem da secao de contato e orcamento.
- `sobre-oficio.png` — fotografia de detalhe de oficio artesanal para a secao Sobre.
- `servico-restauracao.png` — imagem ilustrativa do servico de Restauracao.
- `servico-revitalizacao.png` — imagem ilustrativa do servico de Revitalizacao.
- `servico-acabamentos.png` — imagem ilustrativa do servico de Acabamentos.
- `estudo-01.png` a `estudo-06.png` — seis fotografias ilustrativas de ambientes utilizadas na galeria.

Icones e logotipo (formato SVG):
- `logo-simbolo.svg` — simbolo da marca PisoFacil utilizado no header.
- `logo-simbolo-footer.svg` — variante do simbolo em tom claro para uso no rodape escuro.
- `icon-message-circle.svg` — icone de mensagem com cor branca, usado em botoes primarios.
- `icon-message-circle-green.svg` — variante do icone de mensagem em cor verde, usada em contextos claros.
- `icon-map-pin.svg` — icone de localizacao para a badge de area de atendimento.
- `icon-map-pin-22.svg` — variante maior do icone de localizacao para a secao Sobre.
- `icon-arrow-up-right.svg` — icone de seta diagonal para links secundarios.
- `icon-tree.svg` — icone de arvore para o compromisso de preservacao da madeira.
- `icon-house.svg` — icone de casa para o compromisso de atendimento residencial.
- `icon-leaf.svg` — icone de folha para o banner de preservacao e sustentabilidade.
- `icon-chevrons.svg` — icone de chevrons para o indicador do comparador de antes e depois.
- `icon-info.svg` — icone de informacao para a barra de aviso de imagens ilustrativas.
- `icon-minus.svg` — icone de menos para o estado expandido do FAQ.
- `icon-plus.svg` — icone de mais para o estado recolhido do FAQ.

---

## Tecnologias Utilizadas

- HTML5 — estrutura semantica da pagina.
- CSS3 — estilizacao, variaveis customizadas, grid, flexbox e media queries para responsividade.
- Google Fonts — tipografias Cormorant Garamond (titulos editoriais) e Inter (corpo e interface).
- Figma — ferramenta de design utilizada para criar o prototipo visual aprovado pelo cliente.
- Figma MCP — integracao que permitiu extrair dados de layout, tokens de design e exportar os assets diretamente do Figma durante o desenvolvimento.

---

## Design de Referencia

O design da landing page foi criado integralmente no Figma e serviu como referencia unica para o desenvolvimento do MVP. Todas as cores, tipografias, espacamentos e componentes foram extraidos diretamente do arquivo de design.

Principais tokens de design utilizados:

| Token                | Valor      | Uso                                               |
|----------------------|------------|---------------------------------------------------|
| Fundo principal      | #F7F4ED    | Background das secoes padrao                      |
| Fundo areia          | #EAE4D8    | Background da secao de galeria                    |
| Fundo marfim         | #FEFCF7    | Background da secao Sobre                         |
| Verde principal      | #254B3B    | Cor da marca, botoes e destaques                  |
| Verde escuro         | #1E3C30    | Background do rodape                              |
| Verde salvia         | #C8D4C9    | Textos em fundos escuros                          |
| Creme                | #F6F2E8    | Titulos e textos em fundo verde                   |
| Texto escuro         | #2D3028    | Titulos e textos principais                       |
| Texto cinza          | #66675D    | Textos de suporte e descricoes                    |
| Borda                | #D5CFC2    | Divisores e contornos sutis                       |
| Madeira              | #8D6B4D    | Numeracao dos servicos e detalhes de acento       |
| Fonte serifada       | Cormorant Garamond | Titulos editoriais e citacoes            |
| Fonte sem serifa     | Inter      | Navegacao, descricoes e interface                 |

---

## Como Visualizar o MVP

Para visualizar o prototipo funcional localmente:

1. Navegue ate a pasta `MVP` dentro do repositorio.
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno.
3. Nenhuma instalacao, servidor ou dependencia externa e necessaria, exceto conexao com a internet para carregamento das fontes do Google Fonts.

---

## Equipe do Projeto

Projeto desenvolvido por alunos do curso de Sistemas para Internet da Fatec Sao Roque, no contexto da disciplina Praticas de Gestao de Projetos.

Cliente atendido: Daniel Laranjeira — profissional autonomo de restauracao de pisos de madeira em Ibiuna e regiao, SP.

---

## Contexto Academico

Instituicao: Fatec Sao Roque  
Curso: Sistemas para Internet  
Disciplina: Praticas de Gestao de Projetos  
Modalidade: Projeto de Extensao Universitaria
