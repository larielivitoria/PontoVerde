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

## 1 - 📋 ENGENHARIA DE REQUISITOS

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



## 2 - 🧠 INTERFACE HUMANO-COMPUTADOR

### 🏛️ 2.1 Princípios de Usabilidade
Os princípios de usabilidade aplicados ao projeto baseiam-se nas **Heurísticas de Nielsen,** garantindo que a interface 
seja intuitiva e eficiente para o cidadão.

 **2.1.1 Visibilidade do Status do Sistema (Feedback)** <br>
O sistema sempre informa ao usuário o que está acontecendo por meio de respostas visuais imediatas.

- Ao passar o mouse sobre os cards de ecopontos ou botões, o efeito de hover (mudança de escala e cor) sinaliza 
que o elemento é interativo. Isso evita que o usuário fique em dúvida se pode clicar ou não.


 **2.1.2 Correspondência entre o Sistema e o Mundo Real** <br>
A linguagem e os símbolos utilizados são familiares ao cidadão, evitando termos técnicos difíceis.

- O mapa interativo utiliza a **convenção universal de geolocalização** que todos já conhecem do Google Maps.

**2.1.3 Controle e Liberdade do Usuário:** <br>
Oferecemos **"saídas de emergência"** claras para que o usuário tenha o **total controle** da navegação 
e poder desfazer ações ou mudar de direção facilmente.

- **Logotipo Interativo:** A logo do Ponto Verde na **Navbar** e no **Footer** funciona como um atalho constante para retornar à *Home*,
servindo como uma rota de fuga rápida.

- **Botões de Retorno no Rodapé:** Em páginas internas, botões estrategicamente posicionados permitem que o usuário volte ao início
sem precisar usar as setas do navegador.

- **Voltar ao Topo:** Um botão de **âncora** no rodapé da *Home* facilita a navegação, permitindo que o usuário retorne ao slogan principal instantaneamente após navegar até o fim da home.

**2.1.4 Consistência e Padronização** <br>
O site segue um padrão visual e funcional em todas as seções, evitando confusão.

- A paleta de cores e a tipografia são mantidas em todas as páginas. O menu de navegação (*Navbar*) e o rodapé (*Footer*) estão sempre 
no mesmo lugar, seguindo o padrão de sites corporativos modernos.

**2.1.5 Prevenção de Erros:** <br>
Projetamos a interface para minimizar ações involuntárias.

- **Seleção em vez de Digitação:** Oferecemos **cards clicáveis** em vez de um campo de texto aberto onde poderia ocorrer
  erros de digitação do usuário.

- **Botões com Estados Claros (Hover):** Com a animação da escala e mudança de cor ao passar o mouse, evitamos
  cliques **"no vazio"**, garantindo que o usuário saiba exatamente onde clicar.

- **Links Externos:** Ao clicar no link para o mapa, garantimos que ele **abra em uma nova aba** (usando `target="_blank"`)
  evita que o usuário **"perca"** o nosso site e tenha que fazer todo o caminho de volta. Isso previne o erro de navegação
  acidental para **fora do fluxo** do projeto.

- **Segurança dos Links Externos:** Utilizamos a combinação dos atributos `target="_blank"` com `rel="noopener noreferrer"`.
  O uso de *noopener* impede que a página de destino tome o controle da aba do nosso site através do objeto *"window.opener"*,
  enquanto o *noreferrer* **protege a privacidade do usuário** ao não vazar informações de origem para o servidor do mapa.

**2.1.6 Flexibilidade e Eficiência de Uso (Responsividade)** <br>
 Através do *Bootstrap*, o layout se adapta automaticamente (*Mobile-First*). Um usuário no celular consegue achar 
 o endereço tão rápido quanto alguém no desktop, garantindo que a eficiência não dependa do dispositivo.

**2.1.7 Design Estético e Minimalista** <br>
 A interface evita informações irrelevantes que possam competir com os dados principais.

Focamos no conceito de **Clean Design.** Cada seção tem um objetivo único (ou educar ou localizar), com espaçamentos 
que permitem o **"respiro"** visual, facilitando a leitura das informações de descarte de REEE.



### 🤝 2.2 Design Centrado no Usuário
Nesta etapa, o foco total foi a **empatia.** Projetamos o site não como desenvolvedores, mas como cidadãos que enfrentam
 a frustração de não saber o que fazer com seu lixo eletrônico.

**2.2.1 Experiência do Usuário (UX):** <br>
Através das nossas entrevistas, percebemos que o usuário se sente "perdido" na hora de descartar seus eletrônicos. 
Por isso, o design foi pensado para **acolher:** em vez de textos complexos, usamos uma interface clara que entrega a 
solução (o local de descarte) em poucos segundos, reduzindo a ansiedade do usuário.

**2.2.2 A Inspiração (TOTVS e Avanade) como Geradora de Confiança:** <br>
 Usamos a estética profissional dessas empresas para que o usuário sinta que está em um **ambiente seguro e oficial.**

A experiência de navegação limpa, inspirada nesses players, garante que o usuário não se sinta confuso. 
A "beleza" aqui serve à usabilidade: uma interface bonita e organizada faz o usuário se sentir capaz de realizar a tarefa.

**2.2.3 Resolvendo a "Dor" do Usuário:** <br>
O design prioriza a facilidade. Se o usuário está no celular, debaixo de sol, procurando um ecoponto, ele não quer ler sobre engenharia; ele quer um mapa que funcione. Nossa inspiração nessas empresas ajudou a criar essa hierarquia: o que é mais importante para o humano aparece primeiro.

