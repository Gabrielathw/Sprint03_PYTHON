# ChargeVolt
***
Challenge GoodWe 2026 - Turma 1CCPY
***
### Integrantes:
### Gabriela Caetano - RM: 572738
### Laura Pícari - RM: 569914
### Lucas Neves - RM: 572679
### João Victor - RM: 571630
### Yihang Xu - RM: 571720
***
## Sobre o Projeto

O ChargeVolt é uma proposta de solução para o ecossistema de carregamento inteligente de veículos elétricos da GoodWe, focada na expansão do ambiente residencial para o ambiente comercial

O projeto busca resolver desafios relacionados a:
- Controle inteligente de demanda energética;
- Interoperabilidade entre carregadores e plataformas;
- Tarifação e pagamento flexíveis;
- Experiência do usuário unificada;
- Integração com energia limpa e inteligência artificial.
***

## Problemas Identificados
- Sobrecarga energética em horários de pico
- Aumento dos custos energéticos;
- Dificuldade de gerenciamento das recargas;
- Baixa eficiência no aproveitamento da energia solar;
- Experiência fragmentada para os usuários.

***
## Objetivo
Desenvolver uma solução que demonstre como tecnologias de monitoramento, inteligência artificial, gerenciamento energético e controle de demanda podem contribuir para uma infraestrutura de carregamento
mais eficiente, sustentável e preparada para o crescimento da mobilidade elétrica.

## Arquitetura do Sistema
O sistema foi desenvolvido em Python e está organizado nos seguintes módulos:

- Cadastro de Usuários
Permite o registro de usuários através de nome e e-mail. Após o cadastro, o login é realizado automaticamente.

- Gerenciamento de Recargas
Responsável por iniciar sessões de carregamento, calcular energia consumida, aplicar tarifas e registrar informações da sessão.

- Sistema de Pontos
Usuários cadastrados acumulam pontos a cada recarga realizada, incentivando a fidelização e o uso contínuo da plataforma.

- Histórico de Recargas
Armazena e exibe todas as sessões realizadas, permitindo acompanhar consumo energético, custos e formas de pagamento.

- Dashboard Gerencial
- 
Consolida indicadores importantes como:
* Quantidade de sessões;
* Energia consumida;
* Energia solar utilizada;
* Receita gerada;
* CO₂ evitado.
* Assistente IA

Simula um sistema de inteligência artificial capaz de:
* Prever demanda;
* Estimar ocupação dos carregadores;
* Avaliar disponibilidade de energia solar;
* Sugerir melhores horários para recarga;
* Estimar economia potencial.

## Dynamic Load Management (DLM)
Simula o balanceamento inteligente da potência disponível entre veículos conectados, priorizando aqueles com menor nível de bateria.

## Simulação de Carga
Permite calcular a energia necessária para completar a bateria de um veículo elétrico e estimar sua autonomia.

## Tecnologias Utilizadas
* Python
* Estruturas de Dados (listas e dicionários)
* Programação Procedimental
* Simulação de Inteligência Artificial
* Simulação de Dynamic Load Management

## Funcionalidades

1 - Cadastro de usuários
2 - Login automático após cadastro
3 -  Modo visitante
4 - Recarga de veículos elétricos
5 - Sistema de pontos
6 - Tarifação dinâmica por horário
7 - Histórico geral de recargas
8 - Dashboard gerencial
9 - Assistente IA
10 - Simulação de energia solar
11 - Dynamic Load Management Inteligente
12 - Simulação de carga e autonomia

## Sustentabilidade e Energia Renovável
O ChargeVolt incorpora conceitos de sustentabilidade através da simulação da utilização de energia solar durante as recargas.

Benefícios simulados:
* Redução do consumo da rede elétrica;
* Melhor aproveitamento de fontes renováveis;
* Diminuição de emissões de CO₂;
* Incentivo à mobilidade elétrica sustentável.

Além disso, o sistema calcula uma estimativa do CO₂ evitado durante cada sessão de carregamento.
