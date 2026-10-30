# 💸 App de Organização de Finanças pessoais "Conta Amiga"

PRD refinado pelo Copilot web

Prompts totais aplicados foram 5 colocados nas linhas abaixo 


```markdown
Atue como Product Manager, UX Designer, UI Designer, Especialista em Acessibilidade e Engenheiro Full Stack.

Crie um MVP funcional de um aplicativo de organização de finanças pessoais baseado em conversação.

# Visão do Produto

O produto será um Assistente de Finanças Pessoais Conversacional.

O objetivo é permitir que usuários registrem despesas, receitas e metas financeiras por meio de linguagem natural, sem depender de formulários complexos ou planilhas.

O sistema deve atuar como um Agente Financeiro Inteligente capaz de interpretar mensagens do usuário, organizar automaticamente as informações financeiras e gerar recomendações personalizadas.

O produto deve transmitir simplicidade, acolhimento, segurança e incentivo à educação financeira.

---

# Problema

Muitas pessoas abandonam aplicativos financeiros porque:

- Exigem preenchimento manual excessivo.
- Possuem interfaces complexas.
- Não oferecem acompanhamento personalizado.
- Apresentam conceitos financeiros difíceis para iniciantes.

O produto deve eliminar essas barreiras por meio de uma experiência conversacional simples e intuitiva.

---

# Público-Alvo

Público principal:

- Pessoas entre 18 e 40 anos.
- Iniciantes em educação financeira.
- Usuários que nunca utilizaram aplicativos financeiros.

Público secundário:

- Usuários que utilizam planilhas simples.
- Profissionais autônomos.
- Pessoas que desejam simplificar seu controle financeiro.

---

# Proposta de Valor

"Controle suas finanças conversando com seu assistente financeiro pessoal."

O aplicativo deve permitir que o usuário organize sua vida financeira simplesmente conversando.

---

# Funcionalidades do MVP

## 1. Registro de Transações por Chat

O usuário poderá registrar movimentações em linguagem natural.

Exemplos:

"Gastei R$ 45 no almoço"

"Recebi R$ 3.500 de salário"

"Uber R$ 30"

"Mercado 200 reais"

O sistema deve:

- Identificar valores.
- Identificar receitas e despesas.
- Sugerir categorias.
- Registrar automaticamente.
- Confirmar a operação para o usuário.

Exemplo de resposta:

"Despesa registrada com sucesso. R$ 45 em Alimentação."

---

## 2. Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Assinaturas
- Compras
- Outros

O usuário deve poder corrigir categorias sugeridas.

---

## 3. Dashboard Financeiro

Exibir:

- Saldo atual
- Total gasto no mês
- Total recebido no mês
- Categorias com maiores gastos
- Evolução financeira

Utilizar gráficos simples e fáceis de entender.

---

## 4. Metas Financeiras

Permitir criar metas como:

- Viajar
- Comprar notebook
- Fazer reserva de emergência

Cada meta deverá possuir:

- Nome
- Valor alvo
- Prazo
- Valor acumulado
- Percentual de progresso

---

## 5. Agente Financeiro

O sistema deve analisar dados financeiros e oferecer recomendações personalizadas.

Exemplos:

"Você gastou 20% mais com delivery neste mês."

"Você está próximo da sua meta de emergência."

"Gostaria de definir um limite mensal para alimentação?"

O tom deve ser educativo e amigável.

Nunca utilizar linguagem punitiva ou julgadora.

---

## 6. Relatórios Inteligentes

Gerar resumos automáticos:

Diário

Semanal

Mensal

Exemplo:

"Neste mês você economizou R$ 300 em comparação ao mês anterior."

---

# Fluxo do Usuário

Primeiro acesso:

1. Cadastro.
2. Definição de objetivo financeiro.
3. Pequeno onboarding.
4. Entrada na tela principal de chat.

Uso diário:

1. Abrir aplicativo.
2. Registrar movimentações.
3. Receber confirmação.
4. Visualizar dashboard.
5. Receber recomendações.

---

# Principais Telas

## Tela de Onboarding

Objetivo:

Conhecer o usuário.

Componentes:

- Nome
- Objetivo financeiro
- Tutorial rápido

---

## Tela Principal de Chat

Componentes:

- Histórico de conversa
- Campo de mensagem
- Sugestões rápidas
- Mensagens inteligentes

Esta deve ser a tela principal do produto.

---

## Dashboard Financeiro

Componentes:

- Saldo
- Receitas
- Despesas
- Gráficos
- Indicadores do mês

---

## Metas Financeiras

Componentes:

- Lista de metas
- Barras de progresso
- Previsão de conclusão

---

## Relatórios

Componentes:

- Insights automáticos
- Comparativos
- Tendências

---

# Design Universal e Acessibilidade

O produto deve seguir rigorosamente princípios de Design Universal.

A experiência deve ser utilizável pelo maior número possível de pessoas, independentemente de:

- Idade
- Nível de alfabetização financeira
- Experiência tecnológica
- Capacidade física
- Capacidade cognitiva

Diretrizes:

- Interfaces simples.
- Poucas etapas.
- Linguagem clara.
- Fontes legíveis.
- Alto contraste.
- Hierarquia visual clara.
- Compatibilidade com leitores de tela.
- Navegação por teclado.
- Componentes acessíveis.
- Área de toque confortável para dispositivos móveis.
- Não depender apenas de cores para comunicar informações.
- Mensagens de erro amigáveis.
- Feedback claro após qualquer ação.

Exemplo:

Ao invés de:

"Erro ao registrar despesa."

Utilizar:

"Não consegui identificar o valor gasto. Poderia informar o valor da compra?"

---

# Requisitos de UX

- Mobile First.
- Design responsivo.
- Experiência extremamente simples.
- Curva de aprendizado mínima.
- Foco em iniciantes.
- Componentes modernos.
- Navegação intuitiva.

Evitar:

- Poluição visual.
- Telas excessivamente complexas.
- Excesso de gráficos.
- Termos técnicos financeiros.

---

# Requisitos Visuais

Inspirar-se na simplicidade e clareza de produtos modernos como:

- Nubank
- Duolingo
- Notion

Sem copiar identidade visual.

Características visuais desejadas:

- Interface clean.
- Muito espaço em branco.
- Bordas suaves.
- Cartões modernos.
- Paleta acolhedora.
- Ícones amigáveis.
- Aparência premium.

---

# Requisitos Técnicos

- Estrutura pronta para escalar.
- Componentização adequada.
- Tipagem consistente.
- Boas práticas de desenvolvimento.
- Preparado para futura integração com IA.
- Preparado para futura integração Open Finance.

---



Interações com o Lovable:

crie um app de finanças pessoais com base nos seguinte PRD (colocado acima)
Perfeito, quero a tela de login caso eu mude de aparelho ou feche o app ao logar novamente para ficar tudo registrado o que já foi feito, quero que começe com todos os dados zerados para eu construir os meus planejamentos aos poucos e a inclusão da IA.


Resultado final no Lovable: https://id-preview--0be5ad74-3648-4701-b363-58644ed01ac0.lovable.app/


![Painel do Conta Amiga](https://github.com/user-attachments/assets/2fa692fa-9485-404a-bb7c-bff8337da25f)


Conta Amiga
Visão Geral
Conta Amiga é um aplicativo de organização financeira pessoal baseado em conversação, desenvolvido para simplificar o controle de receitas, despesas e metas financeiras.

A proposta do produto é oferecer uma experiência intuitiva e acessível, permitindo que usuários organizem suas finanças de forma natural, sem depender de planilhas complexas ou aplicativos financeiros difíceis de utilizar.

O sistema atua como um assistente financeiro digital, ajudando o usuário a registrar movimentações, acompanhar resultados e desenvolver hábitos financeiros saudáveis.

Objetivo do Produto
Permitir que qualquer pessoa organize sua vida financeira por meio de uma experiência simples, conversacional e acessível.

O aplicativo busca reduzir as barreiras comuns encontradas em soluções tradicionais de controle financeiro, oferecendo:

Registro simplificado de receitas e despesas;
Acompanhamento financeiro em tempo real;
Visualização clara da situação financeira;
Definição e acompanhamento de metas;
Relatórios e insights sobre hábitos de consumo.
Funcionalidades Implementadas
 Conversa
O módulo de Conversa é o principal canal de interação do usuário com o sistema.

Objetivos
Registrar receitas e despesas utilizando linguagem natural;
Simplificar o lançamento de movimentações financeiras;
Centralizar a comunicação com o assistente financeiro.
Exemplos de uso
Gastei R$ 50 no mercado
Recebi R$ 3.000 de salário
Uber R$ 25
Paguei R$ 40 no almoço
Benefícios
Menos etapas para registrar gastos;
Experiência mais natural e intuitiva;
Redução da complexidade operacional.


 Painel Financeiro
O Painel apresenta uma visão consolidada da situação financeira do usuário.

Indicadores disponíveis
Saldo Atual
Exibe o saldo consolidado baseado nas movimentações registradas.

Saldo Atual = Receitas - Despesas
Resultado do Mês
Apresenta quanto sobrou ou faltou no período atual.

Exemplo:

Neste mês sobrou R$ 500
Recebido no Mês
Mostra o total de receitas registradas durante o mês.

Indicadores esperados:

Salários
Rendimentos
Entradas diversas
Gasto no Mês
Exibe o total das despesas registradas.

Indicadores esperados:

Gastos gerais
Compras
Contas
Transporte
Alimentação
Onde Você Mais Gastou
Área destinada à exibição das categorias com maior volume de gastos.

Exemplo futuro:

1. Alimentação - R$ 600
2. Transporte - R$ 250
3. Lazer - R$ 180
Últimos 3 Meses
Apresenta um histórico recente do comportamento financeiro do usuário.

Objetivos:

Comparar resultados mensais;
Visualizar evolução financeira;
Identificar tendências de gastos e receitas.


 Metas Financeiras
Módulo destinado à criação e acompanhamento de objetivos financeiros.

Exemplos de metas
Reserva de emergência;
Compra de notebook;
Viagem de férias;
Entrada de imóvel;
Troca de veículo.
Informações da Meta
Nome da meta;
Valor desejado;
Valor acumulado;
Progresso percentual;
Prazo estimado.
Benefícios
Incentivar planejamento financeiro;
Aumentar motivação do usuário;
Acompanhar evolução dos objetivos.
Relatórios
Área responsável por gerar análises e resumos financeiros.

Tipos de Relatório
Diário
Resumo das movimentações realizadas no dia.

Semanal
Consolidação dos gastos e receitas da semana.

Mensal
Análise completa do desempenho financeiro do período.

Exemplos de Insights
Você economizou R$ 300 em relação ao mês anterior.
Sua categoria com maior gasto foi Alimentação.
Os gastos com transporte aumentaram 15% neste mês.
 Gestão de Usuário
O sistema possui autenticação e identificação do usuário logado.

Recursos
Login;
Sessão autenticada;
Encerramento de sessão (Sair).
Experiência do Usuário
O projeto foi concebido com foco em:

Simplicidade
Navegação intuitiva;
Linguagem acessível;
Poucas etapas por fluxo.
Clareza
Indicadores financeiros facilmente compreensíveis;
Componentes organizados em cartões;
Hierarquia visual bem definida.
Acessibilidade
Seguindo os princípios de Design Universal:

Interface amigável para iniciantes;
Contraste adequado;
Textos legíveis;
Componentes acessíveis;
Baixa carga cognitiva.
Arquitetura Funcional do MVP
Conta Amiga
│
├── Conversa
│   ├── Registro de receitas
│   ├── Registro de despesas
│   └── Interação com assistente
│
├── Painel
│   ├── Saldo atual
│   ├── Recebido no mês
│   ├── Gasto no mês
│   ├── Categorias de gastos
│   └── Histórico financeiro
│
├── Metas
│   ├── Cadastro de metas
│   ├── Acompanhamento
│   └── Evolução financeira
│
└── Relatórios
    ├── Diário
    ├── Semanal
    └── Mensal
Próximas Evoluções Previstas
Agente Financeiro Inteligente
Sugestões automáticas de economia;
Alertas de gastos excessivos;
Recomendações personalizadas;
Educação financeira contextual.
Exemplo
Você gastou 20% mais com delivery neste mês.
Deseja definir um limite para essa categoria?
Classificação Automática de Gastos
Categorias previstas:

Alimentação
Transporte
Moradia
Saúde
Educação
Lazer
Compras
Assinaturas
Outros
Insights Financeiros Inteligentes
Comparações mensais;
Tendências de consumo;
Evolução patrimonial;
Recomendações financeiras personalizadas.
Avaliação do MVP
✅ Estrutura principal implementada

✅ Navegação simples

✅ Interface alinhada ao conceito de Design Universal

✅ Organização financeira centrada no usuário

✅ Base preparada para evolução do Agente Financeiro Inteligente

O MVP já entrega os pilares fundamentais da proposta do produto: simplicidade, clareza, acessibilidade e controle financeiro por meio de uma experiência amigável e intuitiva.

##Reflexão
O que funcionou bem?
O PRD feito no Copilot ajudou muito, pois os créditos do Lovable acabaram um pouco antes do projeto ser finalizado e após 2h quando os créditos voltaram eu consegui finalizar.

O que não funcionou como esperado?
Esperava interagir mais vezes com o Lovable, achei muito pouco a utilização dos créditos iniciais.


O que aprendeu sobre conversar com IAs?
Aprendi que é praticamente a mesma forma que conversar com outra pessoa, quanto mais detalhes e clareza eu apresenta mais assertivo e coeso será o retorno.






