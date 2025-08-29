# **Tema escolhido:** Nome da aplicação ou produto

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Nome Componente 1
- Nome Componente 2
- Nome Componente 3

## Resumo

Apresente uma breve descrição da sua aplicação ou produto.

## Introdução

- Apresente uma contextualização para o problema que o serviço ou poduto proposto irá resolver e por quê esse tipo de aplicação é necessária.
- Em uma única frase, resuma o objetivo do serviço ou poduto.
- Que tipo de experiência o serviço ou poduto deve proporcionar para os usuários?

## Publico Alvo

- Determine o seu público alvo:

### Personas

  **Persona Primária: Ana (A Gestora do Lar)**
        Ana representa o usuário residencial principal. Com cerca de 38 anos, pertence à classe média, é mãe e a principal responsável pelo planejamento financeiro da família. Seu contexto cultural é pragmático em relação à tecnologia: ela utiliza aplicativos que resolvem problemas práticos de forma simples. Sua motivação para usar o produto é primariamente econômica, buscando reduzir a conta de luz para aliviar o orçamento doméstico.

  **Persona Secundária: Carlos (O Eletricista Profissional)**
        Carlos é um profissional autônomo de 45 anos que busca se diferenciar no mercado. Seu contexto econômico o impulsiona a agregar valor ao seu serviço para justificar um preço justo, em vez de competir apenas por preço. Culturalmente, ele vê a tecnologia como uma ferramenta de trabalho para otimizar seus diagnósticos e provar a qualidade de seu serviço ao cliente.

  **Outras Personas: Tiago (O Jovem Tecnológico)**
        Tiago representa o "early adopter", um jovem desenvolvedor de 26 anos, entusiasta de tecnologia, dados e automação. Seu contexto cultural é o de quem busca otimizar a vida com tecnologia. Economicamente, ele não tem a mesma pressão orçamentária de Ana, mas sua motivação é ter controle total sobre os dados de consumo por eficiência, curiosidade e para integrar com sua visão de casa inteligente.

* **Quais informações sobre o usuário o serviço ou poduto deve guardar?**

    * **Persona primária (Ana):**
        * Dados de perfil (login) e tarifa de energia local.
        * Configuração da residência (lista de aparelhos por cômodo).
        * Histórico de consumo detalhado (geral e por aparelho).
        * Metas de economia e configurações de alertas.

    * **Persona secundária (Carlos):**
        * Deve guardar todas as informações da persona primária.
        * Adicionalmente, deve permitir o gerenciamento de múltiplos clientes/residências.
        * Deve armazenar dados para a geração de relatórios comparativos (antes/depois de um serviço).

    * **Outras personas (Tiago):**
        * As informações a serem guardadas são as mesmas da Persona Primária (Ana), pois o modo de uso residencial é o mesmo.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

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

## Análise de concorrência

1. Plugs Inteligentes (Ex: Positivo, Intelbras)

Esses dispositivos são concorrentes diretos que medem o consumo de aparelhos individualmente. O ponto positivo deles é a alta precisão na medição e a funcionalidade extra de controle remoto. Contudo, apresentam como pontos negativos uma visão limitada do consumo da casa, já que seria caro e impraticável comprar um plug para cada aparelho, e a incapacidade de monitorar equipamentos de instalação fixa, como chuveiros e ar-condicionado.

2. Aplicativos de Concessionárias (Ex: Enel, Neoenergia)

Os aplicativos das próprias distribuidoras de energia são gratuitos e apresentam os dados oficiais do consumo total da residência, o que são seus pontos fortes. Suas principais desvantagens são a falta de detalhamento por aparelho, a ausência de informações em tempo real (os dados são atualizados com atraso) e a falta de alertas sobre consumo excessivo, fazendo com que o usuário só descubra o gasto elevado quando a fatura chega.

3. Ecossistemas de Casa Inteligente (Ex: Google Home, Alexa)

Estas plataformas atuam como concorrentes indiretos. Seus pontos positivos são a automação, que permite criar rotinas para economizar energia, e a conveniência de centralizar o controle de vários dispositivos. Os pontos negativos são que o foco principal é a automação e não a análise de consumo, o alto custo para montar o ecossistema e a análise de dados de energia, que é geralmente muito básica ou até mesmo inexistente.

## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->
