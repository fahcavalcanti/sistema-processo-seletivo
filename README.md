# Projeto de Processo Seletivo de Candidatos - DIO

Este é um projeto Java que simula um processo seletivo de candidatos. Ele inclui várias funções que demonstram diferentes aspectos de um processo de seleção, como entrar em contato com candidatos, imprimir a lista de candidatos e selecionar candidatos com base em critérios de salário.
Apresentado para o módulo de Dominando a Linguagem de Programação Java no Santander Bootcamp 2023 - Fullstack Java+Angular ministrado pela DIO - Digital Innovation One.

## Funcionalidades

### Entrando em Contato com Candidatos
O método `entrandoEmContato(String candidato)` simula a tentativa de entrar em contato com um candidato. Ele realiza até três tentativas de contato e exibe mensagens de sucesso ou falha.

### Imprimir Lista de Candidatos
O método `imprimirSelecionados()` exibe a lista de candidatos com seus índices.

### Seleção de Candidatos
O método `selecaoCandidatos()` simula a seleção de candidatos com base em seus salários pretendidos. Ele seleciona até 5 candidatos com salários compatíveis com um salário base de 2000.0.

### Análise de Candidato
O método `analisarCandidato(double salarioPretendido)` verifica se é necessário ligar para um candidato com base em seu salário pretendido e no salário base.

## Como Executar
1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/fahcavalcanti/sistema-processo-seletivo.git

2. Navegue até o diretório do projeto: 

   ```bash
   cd controleCandidatos

3. Compile o código Java: `javac candidatura/ProcessoSeletivo.java`
4. Execute o programa: `java candidatura.ProcessoSeletivo`
5. Observe as sáidas no terminal e caso queira ver outras funções basta alterar a class main.


