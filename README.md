# **Tema escolhido:** - Aplicativo de Monitoramento de Exercícios para Idosos

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Paulo César Fachetti Motta
- Eric Hideyoshi Kanekiyo

## Resumo

Aplicação móvel para registro e acompanhamento de atividades físicas planejadas de idosos, com foco em visualização simples, lembretes inteligentes e acompanhamento seguro de progresso com cuidadores e familiares.

## Introdução

Contextualização do problema: A terceira idade sempre se torna um período complicado para atividades físicas se tornarem rotina na vida, aumentando o risco de queda, perda de autonomia e agravamento de doenças crônicas. Muitos idosos têm barreiras de adesão (medo, esquecimento, limitações motoras/visuais, falta de orientação) e familiares/cuidadores não conseguem ter visibilidade contínua da rotina de exercícios sem um registrador presente. Portanto, um aplicativo simples, inclusivo e seguro pode facilitar o acompanhamento, estimular constância e progresso, além de promover qualidade de vida.
Objetivo em uma frase: Ajudar idosos a praticarem exercícios leves com segurança e constância, oferecendo orientação simples e visibilidade do progresso para cuidadores e idosos.

- Que tipo de experiência o serviço ou poduto deve proporcionar para os usuários?

## Publico Alvo

Idosos; cuidadoras(es) de idosos; familiares diretos (filhos/netos) e profissionais de saúde que acompanham rotinas.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

Observação: dados fictícios, criados para orientar decisões de UX.

  - Persona primário:
      * Isaias, 80 anos:
        ● Contexto: Aposentado; sem filhos e mora sozinho; hipertensão controlada; visão reduzida; usa smartphone Android básico. Faz caminhadas e alongamentos
conforme lembra.
        ● Objetivos: Manter autonomia, melhorar equilíbrio e flexibilidade, seguir recomendações do médico sem complicação.
        ● Dores/Dificuldades: Esquece horários, letras pequenas, medo de fazer errado e se machucar.
        ● Comportamento digital: Usa WhatsApp e YouTube; evita apps complexos.
        ● Acessibilidade: Prefere voz guiada e botões grandes; alto contraste.

      * Ana, 45 anos (filha):
        ● Contexto: Filha de idoso; trabalha em período integral; mora em outra cidade, mas acompanha os pais à distância.
        ● Objetivos: Garantir que o pai siga uma rotina segura de exercícios; receber alertas imediatos em caso de problemas; motivar o pai com mensagens positivas.
        ● Dores/Dificuldades: Falta de tempo para ligações diárias; preocupação constante; dificuldade em encontrar informações confiáveis sobre a saúde do pai.
        ● Comportamento digital: Usuária avançada de aplicativos; valoriza clareza e resumos semanais automáticos.
        ● Acessibilidade: Busca praticidade; interface simples e notificações rápidas no celular.

      * Dr. João, 38 anos (fisioterapeuta):
        ● Contexto: Profissional de saúde que acompanha rotinas de idosos em clínicas e teleatendimento.
        ● Objetivos: Aumentar a aderência dos pacientes aos exercícios; avaliar evolução de forma remota; identificar sinais de risco cedo.
        ● Dores/Dificuldades: Nem sempre tem contato direto com familiares; excesso de pacientes dificulta acompanhamento individual.
        ● Comportamento digital: Habituado a relatórios e dashboards; precisa de dados objetivos.
        ● Acessibilidade: Prefere interface de análise clara, com gráficos simples e indicadores de risco.

  - Persona secundária:
        * Maria, 24 anos, estagiária em empresa de Gerontologia: precisa ver cumprimento diário, sinais de alerta e checklist simples.
    
  - Outras personas ...

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

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

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



