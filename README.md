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

  **Persona Primária: Ana (A Gestora do Lar):**
        Ana representa o usuário residencial principal. Com cerca de 38 anos, pertence à classe média, é mãe e a principal responsável pelo planejamento financeiro da família. Seu contexto cultural é pragmático em relação à tecnologia: ela utiliza aplicativos que resolvem problemas práticos de forma simples. Sua motivação para usar o produto é primariamente econômica, buscando reduzir a conta de luz para aliviar o orçamento doméstico.

  **Persona Secundária: Carlos (O Eletricista Profissional):**
        Carlos é um profissional autônomo de 45 anos que busca se diferenciar no mercado. Seu contexto econômico o impulsiona a agregar valor ao seu serviço para justificar um preço justo, em vez de competir apenas por preço. Culturalmente, ele vê a tecnologia como uma ferramenta de trabalho para otimizar seus diagnósticos e provar a qualidade de seu serviço ao cliente.

  **Outras Personas: Tiago (O Jovem Tecnológico):**
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

---

### **Persona Secundária: Carlos, o Eletricista**

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
