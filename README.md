# abstergo-industries
Desafio - Fazendo o curso para a certificação AWS Practitioner uma das etapas é criar um relatório para o gerente financeiro citando ferramentas para economizar na implementação de cloud em uma rede de farmácias.

## Relatório de implementação de serviços AWS

Data: 18/06/2025  
Empresa: Abstergo Industries  
Responsável: Ana Luiza Santos  

### Introdução

Este relatório apresenta o processo de implantação de ferramentas na empresa Abstergo Industries, realizado por Ana Luiza Santos. O objetivo do projeto foi elencar três serviços AWS com foco na redução de custos imediatos, aumento da eficiência operacional e escalabilidade dos recursos de TI, considerando o contexto de uma rede de farmácias.

### Descrição do projeto

O projeto de implementação de ferramentas foi realizado em três etapas, cada uma com  seus objetivos específicos. A seguir, serão descritas as etapas do projeto e seus respectivos casos de uso:

Etapa 1:
 - Nome da ferramenta: Elastic Compute Cloud - EC2 Autoscaling
 - Foco da ferramenta: Capacidade computacional segura e redimensionável.  Computação: CPU, memória, rede, armazenamento, sistema operacional. Permite ajustar automaticamente a quantidade de instâncias EC2 de acordo com a demanda de uso, garantindo capacidade computacional segura e redimensionável. Proporciona melhor gerenciamento de custos, alta disponibilidade e tolerância a falhas, com implantação multi-AZ (zonas de disponibilidade).
 - Descrição de caso de uso: Farmácias com picos de acesso em horários específicos (ex: campanhas de vacinação ou promoções) podem escalar automaticamente os servidores para atender à demanda, reduzindo custos em períodos de baixa utilização e evitando indisponibilidade em horários de pico.

Etapa 2:
 - Nome da ferramenta: Virtual Private Cloud - VPC
 - Foco da ferramenta: Permite construir e configurar redes virtuais na AWS  Subredes privadas e públicas, controle de roteamento, firewalls e políticas de segurança.
 - Descrição de caso de uso: Separação de ambientes sensíveis, como sistemas de pagamento e dados de clientes, em sub-redes privadas, enquanto aplicações públicas (ex: site institucional) ficam em sub-redes públicas. Isso aumenta a segurança e reduz riscos de exposição de dados, além de permitir segmentação de recursos para otimizar custos.

Etapa 3:
 - Nome da ferramenta: S3 Standard
 - Foco da ferramenta: Serviço de armazenamento de objetos projetado para dados acessados com frequência, com alta durabilidade, disponibilidade e escalabilidade.
 - Descrição de caso de uso: Armazenamento centralizado de documentos, imagens de receitas, notas fiscais eletrônicas e backups de sistemas das farmácias, com acesso rápido e seguro. O uso de políticas de ciclo de vida pode mover dados antigos para classes de armazenamento mais baratas, otimizando ainda mais os custos.

### Recomendações Adicionais
- Segurança:

AWS Identity and Access Management (IAM): Gerencie permissões e acesso de usuários e serviços de forma granular.  
AWS Key Management Service (KMS): Gerencie chaves de criptografia para proteger dados sensíveis.  
AWS GuardDuty: Serviço de detecção de ameaças para monitorar atividades maliciosas e comportamento não autorizado.

- Observabilidade:

Amazon CloudWatch: Monitore métricas, logs e alarmes para identificar e responder rapidamente a incidentes.  
AWS CloudTrail: Audite e registre todas as ações realizadas na conta AWS, garantindo rastreabilidade e conformidade.  

- Governança e Melhores Práticas:

AWS Cloud Adoption Framework (AWS CAF): Utilize o AWS CAF para alinhar a estratégia de adoção de cloud com os objetivos de negócio, abordando seis perspectivas: negócios, pessoas, governança, plataforma, segurança e operações.
- Monitoramento e Otimização Contínua:

AWS Cost Explorer e AWS Budgets: Monitore gastos e identifique oportunidades de economia contínua.  
Automação de Backups e Políticas de Retenção: Implemente automação para backups e políticas de retenção de dados, reduzindo riscos e custos operacionais.
- Treinamento e Capacitação:

Invista em capacitação da equipe para uso eficiente dos recursos AWS, evitando desperdícios e melhorando a governança.


### Conclusão

A implementação dos serviços AWS na Abstergo Industries proporcionará maior eficiência, escalabilidade e segurança, além de significativa redução de custos operacionais. A adoção dessas ferramentas é fundamental para o crescimento sustentável da rede de farmácias, permitindo que a empresa acompanhe as demandas do mercado com flexibilidade e controle financeiro. Recomenda-se a continuidade da utilização das soluções implementadas, a avaliação periódica de novas tecnologias e a adoção das melhores práticas de segurança, observabilidade e governança para garantir a evolução contínua dos processos da empresa.

Ana Luiza Santos  
Responsável pelo Projeto de Implementação Cloud

Abstergo Industries
