# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27/02/2026

Empresa: Abstergo Industries

Responsável: João Eduardo Alves

## Introdução
Este relatório apresenta o processo de implementação de ferramentas de cloud na empresa farmaceutica (ficticia) *Abstergo Industries*, realizado por João Eduardo Alves, como parte de um desafio de projeto do bootcamp "Backend com JAVA e AWS, da CI&T na plataforma DIO. O objetivo do desafio de projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediato para a empresa, dado o contexto ficticio de que o gestor da empresa solicitou este relatório.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Nome da ferramenta**: Amazon EC2 Spot Instances
  
- **Foco da ferramenta**: Redução de custos em processamento computacional
  
- **Descrição de caso de uso**: A empresa utiliza servidores EC2 para análises de dados farmacêuticos. Com o uso de Spot Instances, é possível aproveitar capacidade ociosa da AWS com descontos de até 90% em relação às instâncias sob demanda, mantendo operações de batch, testes e cargas de trabalho flexíveis de forma econômica.

Etapa 2: 
- **Nome da ferramenta**: Amazon S3 Intelligent-Tiering

- **Foco da ferramenta**: Redução de custos com armazenamento de dados

- **Descrição de caso de uso**: A empresa armazena grandes volumes de dados clínicos e relatórios. Ao migrar para S3 Intelligent-Tiering, os dados acessados com frequência permanecem em camadas de menor custo, e dados pouco acessados são movidos automaticamente para camadas mais baratas, reduzindo significativamente a despesa com armazenamento sem necessidade de gerenciamento manual.

Etapa 3: 
- **Nome da ferramenta**: AWS Lambda

- **Foco da ferramenta**: Otimização de recursos computacionais e custo de execução de aplicações

- **Descrição de caso de uso**: Algumas tarefas internas da empresa, como processamento de arquivos e execução de funções de ETL, eram realizadas em servidores dedicados que ficavam ociosos grande parte do tempo. Com AWS Lambda, essas tarefas são executadas sob demanda, eliminando custos de servidores ociosos e permitindo pagar apenas pelo tempo de execução efetivo.

## Conclusão
A implementação das ferramentas AWS na empresa *Abstergo Industries* resultará em redução imediata de custos operacionais, otimização do uso de recursos computacionais e armazenamento eficiente de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas, bem como a exploração de novas tecnologias AWS para melhorar ainda mais os processos e reduzir custos.

## Anexos

- Manuais de configuração do Amazon EC2 Spot Instances

- Documentação do Amazon S3 Intelligent-Tiering

- Guia de boas práticas do AWS Lambda

Assinatura do Responsável pelo Projeto:
João Eduardo Alves
