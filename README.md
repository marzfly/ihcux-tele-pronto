# TelePronto — Protótipo de Baixa Fidelidade

Projeto desenvolvido para a disciplina de **Interação Humano Computador e UX**, com o objetivo de criar um protótipo de baixa fidelidade para o aplicativo **TelePronto**.

O aplicativo tem como objetivo ajudar no atendimento de casos leves por meio de triagem, fila virtual, consulta por vídeo, receitas digitais e lembretes de medicação, conforme solicitado na atividade. 0

## Nome dos alunos

- Arthur Cantarutti
- Bernardo Rocha
- Gabrielly Cunha
- Guilherme A. Honorato
- Mariana Duarte
- Thaís Augusta

## Sobre o projeto

O **TelePronto** é um aplicativo de saúde pensado para facilitar o atendimento de pacientes que precisam de orientação médica rápida.

O protótipo foi feito em estilo **wireframe**, com telas simples, poucos elementos visuais e foco na leitura rápida. A proposta é evitar confusão para usuários que possam estar passando mal.

## Telas do protótipo

O protótipo possui 6 telas principais:

1. **Home / Dashboard**
   - Tela inicial com acesso rápido para consulta, remédios, receitas, farmácias próximas e emergência.

2. **Triagem de Sintomas**
   - Tela onde o usuário seleciona o que está sentindo, como dor de cabeça, febre, tosse ou dor no peito.

3. **Sala de Espera Virtual**
   - Mostra a posição do usuário na fila, quantidade de pacientes na frente e tempo estimado de espera.

4. **Vídeo-Chamada**
   - Tela da consulta com o médico, contendo botões de microfone, câmera, chat e encerrar chamada.

5. **Minha Receita**
   - Exibe a receita digital com QR Code e histórico de receitas anteriores.

6. **Lembrete de Medicação**
   - Permite visualizar horários dos remédios e configurar alertas.

Essas telas seguem as sugestões da atividade, como Home, Triagem, Sala de Espera, Vídeo-Chamada, Receita e Lembrete de Medicação. 

## Análise de Acessibilidade

O design foi pensado para ajudar usuários com visão cansada, visão turva ou dificuldade motora causada por mal-estar.

As principais decisões foram:

- Uso de textos grandes e bem legíveis.
- Botões grandes, fáceis de tocar.
- Poucas informações por tela.
- Ícones simples acompanhados de texto.
- Alto contraste em preto e branco.
- Organização em blocos separados.
- Botão de emergência sempre visível.
- Navegação inferior fixa para facilitar o acesso às telas principais.

Essas escolhas ajudam principalmente pessoas idosas ou usuários com dedos trêmulos, como sugerido na atividade. 

## Fluxo Crítico: iniciar uma consulta de urgência

O caminho principal para iniciar uma consulta é:

1. O usuário abre o aplicativo na tela **Home / Dashboard**.
2. Clica no botão grande **Consulta Agora**.
3. Vai para a tela de **Triagem de Sintomas**.
4. Escolhe o sintoma principal ou descreve o que está sentindo.
5. Clica em **Continuar**.
6. Entra na **Sala de Espera Virtual**.
7. Aguarda ser chamado pelo médico.
8. Quando chegar sua vez, entra na tela de **Vídeo-Chamada**.

Esse fluxo foi criado para ser curto, direto e fácil de entender.

## Prevenção de Erros

Para evitar que o usuário cometa erros importantes, foram usadas algumas soluções:

- O botão **Encerrar** na vídeo-chamada fica separado dos outros botões.
- O botão de encerrar chamada aparece em destaque, evitando toque acidental.
- A tela de espera informa claramente que o usuário pode sair do app e voltar depois.
- A triagem usa opções simples, evitando textos longos.
- A emergência fica sempre visível para casos graves.
- As ações principais usam botões grandes.
- As telas têm poucos caminhos para não confundir o usuário.

## Estados do sistema

O protótipo também mostra estados importantes do sistema:

- Na **Sala de Espera**, o usuário vê quantos pacientes estão na frente.
- O tempo estimado de atendimento aparece com destaque.
- Na **Vídeo-Chamada**, aparece o tempo da consulta.
- Na tela de **Lembrete de Medicação**, os horários mostram se o alerta está ativado.
- Na tela de **Receita**, o QR Code indica que a receita pode ser validada na farmácia.

## Arquivos do projeto

Estrutura sugerida do repositório:

```text
ihcux-tele-pronto/
│
├── README.md
│
└── prototipo/
    ├── prototipo.png
    └── prototipo.pdf
