# ♻️ Ponto Verde - Conectando Pessoas ao Descarte Consciente 🌱

## 🧩 Site Desenvolvido para o Projeto de Extensão - UNIP Jundiaí
O projeto ocorre em torno da temática **“Tecnologia e Sustentabilidade na Comunidade”,**
integra conteúdos das disciplinas **Interface Humano-Computador, Engenharia de Requisitos e Programação Web Responsiva,**
além da disciplina **Projeto e Desenvolvimento I,** que organiza o processo de construção da solução tecnológica.

## 🌐 Acesse o Site: https://larielivitoria.github.io/PontoVerde/

### 👩🏻‍💻 Meu Papel no Desenvolvimento
Fui a responsável técnica integral pela execução da programação do site, atuando nas seguintes frentes:

**Arquitetura e Estruturação:** Planejamento de toda a estrutura de arquivos e organização do projeto.

**UI/UX Design & Layout:** Criação da identidade visual tendo como referência a TOTVS e a AVANADE, hierarquia visual, 
paleta de cores e design responsivo com foco na experiência do usuário (IHC).


# 📑 Documentação 

## 📋 1 - ENGENHARIA DE REQUISITOS

### 🗣️ 1.1 Levantamento de Requisitos (Elicitação)

**Metodologia e Técnicas Utilizadas:**

**Questionário Estruturado:** Aplicado para coletar dados estatísticos sobre o nível de conhecimento da população.

**Entrevistas Presenciais:** Realizadas com usuários locais para captar detalhes subjetivos e dificuldades específicas 
no processo de descarte.

**Análise do Cenário:** <br>
O processo de levantamento teve como foco identificar as principais "dores" dos moradores de Jundiaí e região. 
Através da interação direta, confirmamos que os **maiores impeditivos** para o descarte correto de REEE, são:

- Falta de conhecimento sobre a existência de locais apropriados.
- Dificuldade de localizar pontos de coleta próximos.
- Dificuldade de entender como preparar os resíduos para o descarte.


### 💡 1.2 Definição de Funcionalidades

Para sanar as dificuldades identificadas, o sistema foi projetado com as seguintes funcionalidades principais:

**Cartilha Informativa Sobre REEE:** Seção dedicada a educar o usuário sobre o que compõe o lixo eletrônico, separando por categorias.

**Guia de Preparação de Descarte:** Instruções detalhadas sobre os procedimentos necessários antes de levar o objeto ao 
ponto de coleta (ex: remoção de pilhas ou limpeza de dados).

**Mapa de Ecopontos:** Centralização geográfica dos pontos de coleta de Jundiaí em uma interface única, permitindo que o 
usuário visualize a proximidade de cada local.

**Filtros de Categorias Aceitas:** Identificação visual rápida (ícones) para que o usuário saiba exatamente qual tipo de 
material é recebido em cada ecoponto específico.


 ### ⚙️ 1.3 Requisitos Funcionais:

**RF01 – Localização Geográfica:** O sistema deve fornecer um mapa interativo com marcadores de geolocalização dos principais ecopontos da região.

**RF02 – Informação Educativa:** O sistema deve exibir conteúdos textuais e visuais que orientem o usuário sobre o que é REEE e como separá-lo.

**RF03 – Detalhamento de Unidade:** O sistema deve listar informações específicas de cada ponto de coleta, incluindo endereço completo e horários de funcionamento.

**RF04 – Identificação de Categorias:** O sistema deve indicar visualmente quais tipos de resíduos são aceitos em cada localidade.



### 🛡️ 1.4 Requisitos Não Funcionais:

**RNF01 – Responsividade:** A interface deve ser desenvolvida com foco em Mobile-First, garantindo adaptação perfeita em dispositivos 
móveis e desktops via Bootstrap.

**RNF02 – Desempenho e Carregamento:** O sistema deve utilizar imagens em formato .WebP, visando reduzir o tempo de carregamento e o 
consumo de dados do usuário.

**RNF03 – Disponibilidade e Independência:** O framework Bootstrap deve ser integrado de forma local (offline), garantindo a renderização 
do layout independente de conexões com CDNs externas.

**RNF04 – Semântica e SEO:** O código deve ser estruturado em HTML5 semântico, priorizando a acessibilidade para leitores de tela 
e a indexação em motores de busca.
