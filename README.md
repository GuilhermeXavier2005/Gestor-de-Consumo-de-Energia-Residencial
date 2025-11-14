# **Gerenciamento de Energia Residencial:** Voltagem

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Guilherme Silva Xavier
- Victor Augusto Caramori Andre

## Resumo

O projeto IHC Voltagem mira precisamente no gerenciamento dos gastos energéticos residenciais, além disso, a voltagem é capaz de armazenar as informações do perímetro e conceber sugestões através dos cálculos de consumo e custos de mantença da eletricidade. Combinando o perfil cadastrado é possível elaborar soluções para os gastos otimizadamente para melhor salvamento de energia, acompanhando seu atual status - consumo, wattz já usados e atual valor da conta conforme a bandeira de taxa tarifária - construindo gráficos e dashboards para compreensão visual do usuário. A voltagem registra, recomenda, alerta e guarda seu histórico conforme o seu cadastro vai se atualizando, melhor se tornam as otimizações.

## Introdução

- <strong>(Apresente uma contextualização para o problema que o serviço ou poduto proposto irá resolver e por quê esse tipo de aplicação é necessária)</strong>. A voltagem é uma visa a construção de elementos gráficos eficientes afim de elucidar os seus clientes, por vezes, discorre de gastos enganosos, erros de leituras ou desconhecimento das bandeiras cobradas sobre o consumo. Enntão algumas dessas questões podem ser exaustivas e demandarem tempo dos usuarios para entender sob qual circunstância suas contas estão aumentando, fazendo que seus usuários sejam capazes de tomar melhores decisões e mudanças de hábitos
- <strong>(Em uma única frase, resuma o objetivo do serviço ou poduto)</strong>. A melhora da inteligibilidade do usuário é esencial na voltagem, é qual esta é completamente programada para ajudar a entender seus gastos
- <strong>(Que tipo de experiência o serviço ou poduto deve proporcionar para os usuários?)</strong>. O usuário será capazes de melhor compreender as possíveis variações, continuidades e médias dos seus consumos e custos, facilitando sua tomada de decisão. A voltagem oferece elucidar perguntas que podem afetar a sua economia semanal, mensal e anual aplicando tecnologias como HTML, CSS, Javascript e ReactJS.

## Publico Alvo

- <strong>Determine o seu público alvo</strong>:
  - Residentes
  - Sindicos
  - Comerciantes locais

### Personas

  **Persona Primária: Ana (A Gestora do Lar):**
        Ana representa o usuário residencial principal. Com cerca de 38 anos, pertence à classe média, é mãe e a principal responsável pelo planejamento financeiro da família. Seu contexto cultural é pragmático em relação à tecnologia: ela utiliza aplicativos que resolvem problemas práticos de forma simples. Sua motivação para usar o produto é primariamente econômica, buscando reduzir a conta de luz para aliviar o orçamento doméstico.

  **Persona Primária: Carlos (O Eletricista Profissional):**
        Carlos é um profissional autônomo de 45 anos que busca se diferenciar no mercado. Seu contexto econômico o impulsiona a agregar valor ao seu serviço para justificar um preço justo, em vez de competir apenas por preço. Culturalmente, ele vê a tecnologia como uma ferramenta de trabalho para otimizar seus diagnósticos e provar a qualidade de seu serviço ao cliente.

  **Persona Primária: Tiago (O Jovem Tecnológico):**
        Tiago representa o "early adopter", um jovem desenvolvedor de 26 anos, entusiasta de tecnologia, dados e automação. Seu contexto cultural é o de quem busca otimizar a vida com tecnologia. Economicamente, ele não tem a mesma pressão orçamentária de Ana, mas sua motivação é ter controle total sobre os dados de consumo por eficiência, curiosidade e para integrar com sua visão de casa inteligente.

* **Quais informações sobre o usuário o serviço ou poduto deve guardar?**

    * **Persona primária (Ana):**
        * Dados de perfil (login) e tarifa de energia local.
        * Configuração da residência (lista de aparelhos por cômodo).
        * Histórico de consumo detalhado (geral e por aparelho).
        * Metas de economia e configurações de alertas.

    * **Persona primária (Carlos):**
        * Deve guardar todas as informações da persona primária.
        * Adicionalmente, deve permitir o gerenciamento de múltiplos clientes/residências.
        * Deve armazenar dados para a geração de relatórios comparativos (antes/depois de um serviço).

    * **Persona primária (Tiago):**
        * As informações a serem guardadas são as mesmas da Persona Primária (Ana), pois o modo de uso residencial é o mesmo.

### Mapa de empatia

![Mapa de empatia](empatia.png)

**Persona Primária: Ana, a Gestora do Lar**

(Usuária final do aplicativo, preocupada em reduzir a conta de luz da família)

* **Pensa e Sente:** Frustrada por não saber o que mais gasta energia. Ansiosa com o valor da conta. Deseja ter mais controle sobre as finanças e ensinar bons hábitos aos filhos.
* **Vê:** Contas de luz cada vez mais altas, notícias sobre aumento de tarifas e filhos usando muitos eletrônicos.
* **Escuta:** Reclamações de amigos e familiares sobre o custo da energia e dicas genéricas de economia na mídia.
* **Fala e Faz:** Pede constantemente para a família apagar as luzes e desligar aparelhos. Pesquisa online por soluções para economizar.
* **Dores:**
    * Não saber quais aparelhos são os verdadeiros vilões do consumo.
    * Dificuldade em engajar a família na economia.
    * Medo de surpresas na conta de luz no fim do mês.
* **Ganhos:**
    * Ter clareza e controle sobre os gastos com energia.
    * Tomar decisões baseadas em dados (ex: trocar um eletrodoméstico).
    * Reduzir o estresse financeiro e alcançar a economia desejada.

**Persona Primária: Carlos, o Eletricista**

(Profissional que pode usar ou recomendar a ferramenta para agregar valor ao seu serviço)

* **Pensa e Sente:** Precisa de formas para provar o valor do seu trabalho ao cliente. Sente a necessidade de se diferenciar da concorrência oferecendo soluções modernas.
* **Vê:** Instalações elétricas ineficientes nas casas dos clientes e o crescimento do mercado de automação e eficiência energética.
* **Escuta:** Clientes pedindo ajuda para reduzir o consumo e reclamando que as medidas que tomam não funcionam.
* **Fala e Faz:** Oferece consultoria de eficiência energética. Realiza diagnósticos e sugere melhorias e a troca de equipamentos.
* **Dores:**
    * Dificuldade em demonstrar o impacto real do seu serviço na conta de luz.
    * Concorrência focada apenas no menor preço.
    * Falta de ferramentas para diagnósticos rápidos e precisos.
* **Ganhos:**
    * Aumentar sua credibilidade e justificar o valor do seu serviço com dados.
    * Fidelizar clientes, tornando-se uma referência em eficiência energética.
    * Criar novas oportunidades de negócio, como monitoramento e manutenção.

## Contexto de uso

- <strong>Descreva o ambiente em que o serviço ou poduto deve ser utilizado.</strong>
  - A voltagem é usado principalmente em um fornecimento web, de modo que todos em uma rede internet posssa acessar. Também deverá oferecer interface com dispositivos móveis, uma versão offline sem conexão aos seus dados no banco. Sendo fácil utilização em pequenos segundos permitindo acompanhamento com atualizações em pequenas horas ou movimentações quantitativas de consumo, ajuste de valores ou cadastro de novos itens e pessoas.
- <strong>Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?</strong>
  - Aplica-se em quaisquer detentor de uma residência, seja própria ou imóvel alugado e também comerciantes que possuam um local para depositar, vender e/ou construir. A voltagem desconsidera culturas ou movimentos sociais uma vez que é focada somente em construir um melhor gerenciamento entre pessoa e consumo elétrico, compreendendo apenas questões orçamentárias do usuário para que este possa aderir as sugestões da voltagem em otimizações de uso energético. 
- <strong>Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?</strong>
  - Questões sobre orçamento mensal de despesas essenciais, números de equipamentos e membros familiares são indispensáveis para a operação da Voltagem, assim como se faz necessário a comprovação de uma pessoa física ou jurídica que responde por um imóvel a ser calculado, bem como prevê constitucionalidades de direito de imóveis. É considerável igualmente obter métricas adicionais para precisão fora da média de consumo estabelecidas pela ANEEL(Agência Nacional de Energia Elétrica)
- <strong>O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?</strong>
  - Fornecimento de informações relacionadas ao consumo elétrico, previsões mensais, gráficos e recomendações para diminuição de custos. Todas as estatísticas devem estar concentradas em um layout com responsividade e interface amigável ao usuário

## Jornada do usuário

Esta é a trajetória de Ana, desde a frustração com a conta de luz até a solução do problema com o aplicativo.

#### **Como a tarefa começa? (Descoberta)**

1.  **Gatilho:** Ana recebe mais uma conta de energia com valor inesperadamente alto, sentindo-se frustrada e sem controle.
2.  **Pesquisa:** Ela busca ativamente na internet por soluções como "aplicativo para controlar gastos com energia".
3.  **Primeiro Contato:** Encontra o "Gestor de Consumo", se atrai pela promessa de clareza e controle, e decide instalar o app.

#### **Como a tarefa se desenvolve? (Uso e Análise)**

4.  **Configuração:** Ela realiza um cadastro rápido e segue um guia simples para registrar seus principais eletrodomésticos.
5.  **Momento de Clareza:** Após alguns dias, o dashboard revela com um gráfico simples que o chuveiro elétrico e o ar-condicionado são os maiores responsáveis pelo alto consumo.
6.  **Ação com Base em Dados:** Com essa informação, ela conversa com a família de forma objetiva, mostrando os "vilões" do consumo e propondo metas (ex: banhos mais curtos).
7.  **Monitoramento:** O app envia alertas de consumo excessivo, permitindo que ela corrija o uso dos aparelhos em tempo real e veja o impacto positivo na projeção da conta.

#### **Como a tarefa termina? (Resultado e Hábito)**

8.  **Sucesso:** A conta de luz seguinte chega visivelmente mais baixa. Ana sente o alívio de ter alcançado seu objetivo.
9.  **Hábito:** O uso do aplicativo se consolida como uma ferramenta de rotina para manter as despesas sob controle.
10. **Recomendação:** Satisfeita, Ana recomenda o aplicativo para amigos e familiares que passam pela mesma dificuldade, tornando-se uma promotora do serviço.

Esta é a trajetória de Carlos, desde a dificuldade em provar seu valor até se tornar um eletricista consultor baseado em dados.

#### **Como a tarefa começa? (Descoberta)**

1.  **Gatilho:** Um cliente reclama que a conta de luz continua alta mesmo após um serviço. Carlos sente que sua palavra técnica não é o suficiente para provar o real problema ou justificar um investimento maior.
2.  **Pesquisa:** Ele busca ativamente por soluções profissionais como "ferramenta para eletricista medir consumo" para ter dados concretos para apresentar.
3.  **Primeiro Contato:** Encontra o "Gestor de Consumo" e se atrai pela existência de um "Modo Profissional", com gerenciamento de clientes e relatórios.

#### **Como a tarefa se desenvolve? (Uso e Análise)**

4.  **Configuração:** Em uma visita de diagnóstico, ele usa o app junto com o cliente, cadastrando os aparelhos para iniciar o monitoramento e posicionando a ferramenta como parte de seu serviço de análise técnica.
5.  **Momento de Clareza:** Dias depois, o dashboard revela que um freezer antigo é o grande vilão do consumo. Ele mostra o gráfico ao cliente, explicando o impacto financeiro exato daquele aparelho.
6.  **Ação com Base em Dados:** Convencido pelos dados irrefutáveis, o cliente aprova a recomendação de Carlos para a troca do aparelho e a adequação do circuito elétrico.
7.  **Monitoramento:** Após o serviço, Carlos inicia um novo período de monitoramento para validar a economia gerada pela intervenção.

#### **Como a tarefa termina? (Resultado e Hábito)**

8.  **Sucesso:** O app gera um relatório comparativo de "Antes e Depois", que Carlos apresenta ao cliente, provando a eficácia do seu trabalho e o retorno sobre o investimento.
9.  **Hábito:** O aplicativo se consolida como a ferramenta padrão em seu "Serviço de Consultoria de Eficiência", sendo usado para diagnóstico e validação em todos os seus principais clientes.
10. **Recomendação:** Satisfeito, Carlos se torna um promotor da ferramenta em sua rede profissional, enquanto seus clientes o recomendam como um especialista diferenciado.


## Análise de concorrência

1. Plugs Inteligentes (Ex: Positivo, Intelbras)

Esses dispositivos são concorrentes diretos que medem o consumo de aparelhos individualmente. O ponto positivo deles é a alta precisão na medição e a funcionalidade extra de controle remoto. Contudo, apresentam como pontos negativos uma visão limitada do consumo da casa, já que seria caro e impraticável comprar um plug para cada aparelho, e a incapacidade de monitorar equipamentos de instalação fixa, como chuveiros e ar-condicionado.

2. Aplicativos de Concessionárias (Ex: Enel, Neoenergia)

Os aplicativos das próprias distribuidoras de energia são gratuitos e apresentam os dados oficiais do consumo total da residência, o que são seus pontos fortes. Suas principais desvantagens são a falta de detalhamento por aparelho, a ausência de informações em tempo real (os dados são atualizados com atraso) e a falta de alertas sobre consumo excessivo, fazendo com que o usuário só descubra o gasto elevado quando a fatura chega.

3. Ecossistemas de Casa Inteligente (Ex: Google Home, Alexa)

Estas plataformas atuam como concorrentes indiretos. Seus pontos positivos são a automação, que permite criar rotinas para economizar energia, e a conveniência de centralizar o controle de vários dispositivos. Os pontos negativos são que o foco principal é a automação e não a análise de consumo, o alto custo para montar o ecossistema e a análise de dados de energia, que é geralmente muito básica ou até mesmo inexistente.

## Coleta de dados

- formulario para adquirir informações essênciais.
  O <a href="https://docs.google.com/forms/d/1gnt6d2HOXxtQqbdqEJQaPvwCvlw3JXGYxVTYouv06SM/edit">formulário</a> de preenchimento é requirido para contextualizar a aplicação do usuário a ser analisado.
- diario de atividades para captar o problema específico do usuário.
  - O usuário haverá de preencher dentro do aplicativo uma espécie de diário, ou blocos de notas conforme a escolha do usuário, no qual ele pode diariamente relatar os problemas envolvidos e enviar para uma análise que buscará atender conformemente os seus pedidos no formato do aplicativo, atendendo seu critério específico, muito semelhante a um chat direto, e se não houver para a Voltagem um algoritmo para tal caso, aplicar Machine Learning em finalidade de aperfeiçoar o software para polir melhor o perfil do cliente. Adicionalmente, uma aba para qual o usuário pode abrir caixinhas de marcação oferecidas pelo próprio software, fazendo que o usuário participe diretamente nas decisões de atualizações futuras, essas caixinhas serão semanalmente atualizadas coletando os votos individual.
- entrevista: <a href="https://feiedu-my.sharepoint.com/:w:/g/personal/unifvandre_fei_edu_br/EdLRzGaXYWBCkruc_Z_tqywBXTrwZLCbaHRKYiKyiaywLA?e=JHWgO9"> (perguntas para realizar a entrevista).

## Análise Hierárquica de Tarefas

![Mapa HTA](mapaHTA.png)

![Tabela HTA](tabelaHTA.jpg)

## GOMS (Goals, Operators, Methods, Selection Rules)

*GOAL 0: Gerenciar e calcular o consumo de energia residencial.*

---

### GOAL 1: Adicionar um novo aparelho ao sistema

**METHOD 1.A:** Cadastrar um aparelho pela tela de formulário.
- **SELECTION RULE:** O usuário precisa inserir um novo eletrodoméstico para que seus gastos possam ser calculados.
- **OPERATORS:**
  - Na tela principal, tocar no botão flutuante de "Adicionar" (+).
  - No menu que aparece, tocar na opção "Adicionar Aparelho".
  - Tocar no campo "Nome do Aparelho" e digitar o nome.
  - Tocar no campo "Potência em Watts" e digitar o valor da potência.
  - Tocar no campo "Cômodo" para abrir a lista de cômodos.
  - Selecionar um cômodo já existente na lista.
  - Tocar no botão "Salvar".
  - Ver a mensagem de confirmação ("Aparelho salvo com sucesso!").

---

### GOAL 2: Registrar um período de consumo para um aparelho

**METHOD 2.A:** Lançar um novo registro de consumo.
- **SELECTION RULE:** O usuário precisa registrar quanto tempo um aparelho ficou ligado para que o sistema possa calcular o custo.
- **OPERATORS:**
  - Na tela principal, tocar no botão flutuante de "Adicionar" (+).
  - No menu que aparece, tocar na opção "Adicionar Consumo".
  - Tocar no campo "Aparelho" para abrir a lista de aparelhos.
  - Selecionar o aparelho desejado.
  - Tocar no campo "Tempo de uso em minutos" e digitar o valor total em minutos.
  - Tocar no botão "Salvar".
  - Ver a mensagem de confirmação ("Consumo salvo com sucesso!").

---

### GOAL 3: Configurar o custo da energia

**METHOD 3.A:** Definir o valor do KWh (Quilowatt-hora).
- **SELECTION RULE:** O usuário precisa informar ao sistema o preço da sua companhia de energia para que os cálculos de custo sejam precisos.
- **OPERATORS:**
  - Na tela principal, tocar no ícone de menu (três pontos).
  - Tocar na opção "Configurações".
  - Tocar no campo "Valor do KWh".
   Digitar o valor monetário do KWh (ex: 0.75).
  - Tocar em "Salvar" ou sair da tela para salvar automaticamente.

---

### GOAL 4: Analisar o consumo total

**METHOD 4.A:** Verificar o cálculo de custo na tela principal.
- **SELECTION RULE:** O usuário quer saber o custo total gerado por todos os consumos registrados.
- **OPERATORS:**
  - Abrir o aplicativo e visualizar a tela principal.
  - Localizar o card ou texto que exibe o "Custo Total Mensal".
  - Ler o valor em Reais (R$) calculado pelo sistema.

## ConcurTaskTrees (CTT)

![Esquema em mapa](CTT.png)

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

## Analise de tratamento de problemas
Reduzir gasto detectando o vilão do consumo (meta do usuário: entender e agir).
1. Criar conta ou login.
2. Inserir tarifa local (bandeira/CEP). 
3. Definir residência (quartos, cômodos).
7. Adicionar aparelho (nome, potência nominal, uso/hora estimada, cômodo).
4. (Opcional) vincular a medição via plug inteligente ou entrada de leitura.
5. Sincronizar com concessionária (se disponível).
6. Receber leituras manuais/diário do usuário.
7. Agregar dados históricos e aplicar cálculos de custo (bandeira tarifária). 
8. Abrir dashboard.
9. Filtrar por período (dia/semana/mês).
10. Selecionar “consumo por aparelho” e ordenar.
11. Identificar top-3 aparelhos de maior consumo.
12. Receber recomendação automática (ex.: “reduzir uso do chuveiro 10%”).
13. Definir meta / alerta (p.ex. aviso quando consumo > X%).
14. Monitorar efeitos (comparar antes/depois)

### Prototipação em baixo nível (papel)
![Esquema das paginas(Rascunho)](esquematizacao.jpeg)
![Esquema das paginas principais(Rascunho)](paginas.jpg)
#### Avaliação heurística

### MOLIC

![dashboard 1](dashboardPrincipal.png)
![dashboard 2](mediaPaparelho.png)
![dashboard 3](cadastrodeaparelhos.png)
![dashboard 4](médias.png)

### Prtotipação em médio nível (Figma)
![(Figma)](FIGMA.png)
- Link para o projeto: <a href="https://www.figma.com/design/lD1s06lJHyz9JRI0985U77/IHC-Voltagem?node-id=0-1&t=1TWqm5BSUEBXSy7j-1"> FIGMA.
#### Avaliação heurística
<a href="ModeloAvaliacaoHeuristica.pdf">avaliação.</a>

### Prtotipação em alto nível (React)
#### Avaliação heurística
<strong>Auto avaliação heurística : <a href="Modelo02AvaliacaoHeuristica.pdf">avaliação modelo 02</a></strong>

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->













