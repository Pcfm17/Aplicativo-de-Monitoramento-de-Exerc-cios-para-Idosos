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
Tipo de experiência desejada:
        ● Clara e acolhedora (linguagem simples e sem jargão). 
        ● Acessível (alto contraste, fontes grandes, voz/TTS, botões grandes, fluxo linear). 
        ● Confiável e segura (foco no usuário, controle de dados e alertas). 
        ● Motivadora (reforços positivos, lembretes gentis, conquistas visíveis). 


## Publico Alvo

Idosos; cuidadoras(es) de idosos; familiares diretos (filhos/netos) e profissionais de saúde que acompanham rotinas.

### Personas

Observação: dados fictícios, criados para orientar decisões de UX.

  - Persona primário:
      * Isaias, 80 anos:
        ● Contexto: Aposentado; sem filhos e mora sozinho; hipertensão controlada; visão reduzida; usa smartphone Android básico. Faz caminhadas e alongamentos
conforme lembra.
        ● Objetivos: Manter autonomia, melhorar equilíbrio e flexibilidade, seguir recomendações do médico sem complicação.
        ● Dores/Dificuldades: Esquece horários, letras pequenas, medo de fazer errado e se machucar.
        ● Comportamento digital: Usa WhatsApp e YouTube; evita apps complexos.
        ● Acessibilidade: botões grandes; alto contraste.

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

### Mapa de empatia

![Mapa de empatia](empatia.png)

![Mapa de empatia](https://github.com/Pcfm17/Aplicativo-de-Monitoramento-de-Exerc-cios-para-Idosos/blob/main/WhatsApp%20Image%202025-09-05%20at%2014.16.10.jpeg)

Quais informações sobre o usuário o serviço deve guardar?
        ● Identificação mínima: nome/apelido, faixa etária, contato de acompanhante  (opcional). 
        ● Preferências e acessibilidade: tamanho da fonte, tema alto contraste, preferências  de áudio/voz, velocidade de fala. 
        ● Saúde (com consentimento explícito): restrições/contra indicações, medicação, metas. 
        ● Atividade: exercícios concluídos, duração, frequência, passos (média estipulada). 
        ● Contexto técnico: tipo de dispositivo, versão do app, permissões de notificações/voz. 
        ● Consentimentos LGPD: finalidades, compartilhamento com acompanhantes e revogação.

## Contexto de uso

Ambientes típicos: casa (mesas, balcões, cama, armário, cadeiras, quartos, sofá, estantes com objetos variados, geladeira, balcão, filtro de água, abajur, remédio, celular, TV, pia, espelho, privada, box, tapete e lava roupa), parque (academis ao ar livre, escorregador, grama, areia, concreto, criança), UBS/clínica. 
Condições: possíveis ruídos externos, iluminação variável, internet instável; uso com/sem óculos; mãos trêmulas; telas pequenas. 
Cenário socioeconômico e cultural: renda fixa; preferência por versão gratuita; apoio de familiares; linguagem simples em Português-BR; confiança construída por clareza e privacidade. 

## Jornada do usuário

Abaixo, o fluxo principal e alguns fluxos alternativos. O foco é a primeira experiência até o uso recorrente. 
Fluxo Principal (Isaías):
    1. Descoberta & Instalação 
        ○ Gatilho: indicação de médico ou conhecido. 
        ○ Ações: baixar app, permitir notificações e acessibilidade (fonte grande, contraste, voz). 
        ○ Resultado: app pronto pra uso, tutorial rápido. 
    2. Onboarding guiado (3 telas) 
        ○ Define limitações físicas. 
        ○ Define exercícios simples. 
        ○ Escolhe rotinas leves (alongamento, caminhada guiada, mobilidade). 
        ○ Adiciona contato de emergência e convida cuidador/familiar. 
    3. Ajuste de Acessibilidade 
      ○ Teste de áudio/voz, tamanho de texto, botões, ritmo da fala. 
    4. Primeira Sessão 
        ○ Lembrete amigável 
        ○ Mostra o exercício já planejado pro dia 
        ○ Verifica início e fim 
        ○ Pergunta como se sentiu em relação ao exercício 
        ○ Registra a atividade (caso tenha acompanhante envia notificação com relatório gerado) 
    5. Recompensa 
        ○ Tela de parabéns; recebe um estímulo visual; dica de hidratação. 
    6. Rotina Semanal 
        ○ Lembretes ajustados aos horários do idoso. 
        ○ Resumo semanal simples: dias ativos, minutos totais, tendência (↑/→/↓). 
    7. Acompanhamento por Cuidador/Família 
        ○ App/portal com checklist diário, alertas de ausência e mensagens de incentivo.

Fluxos Alternativos & Exceções:
        ● Sem Internet: rotina roda offline; sincroniza depois. 
        ● Interrupção no meio do exercício: app retoma do passo anterior; salva progresso 
        parcial. 
        ● Cansaço/Dor: instrução para parar, alongar leve, registrar ocorrência e notificar 
        cuidador (caso tenha). 
        ● Dispositivo antigo: app visa atender o máximo possível de versões antigas.
        
Encerramento da Jornada:
        ● Como começa: convite/instalação → onboarding curto → primeira rotina. 
        ● Como se desenvolve: lembretes gentis → rotinas acompanhadas simples → progresso compartilhado com usuário é possível acompanhante. 
        ● Como termina (ciclo): resumo semanal e pequenas metas → reforço positivo → ajustes de acessibilidade e metas conforme progressão.

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







