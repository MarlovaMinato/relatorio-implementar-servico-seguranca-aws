# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 20/11/2023
Empresa: SecureGuard Solutions 
Responsável: Marlova Minato

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa SecureGuard Solutions, realizado por Marlova Minato. O objetivo do projeto foi elencar 4 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 4 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Criptografia para Proteger Dados em Trânsito e em Repouso

- [Descrição de caso de uso] 
A SecureGuard Solutions implementou o Amazon S3 para armazenamento de dados confidenciais na nuvem. Para proteger esses dados, foi configurada a criptografia no nível do serviço para garantir que os dados em reserva sejam criptografados. Além disso, a empresa implementou o Amazon CloudFront para a entrega segura de conteúdo, utilizando o protocolo HTTPS para proteger dados em trânsito.

- [Passos de implementação] 
1. Configuração de criptografia no Amazon S3, utilizando chaves gerenciadas pelo AWS Key Management Service (KMS).
2. Habilitação do suporte HTTPS no Amazon CloudFront para garantir a segurança durante a entrega de conteúdo.
3- Realização de testes para garantir que a criptografia esteja ativa tanto em segurança quanto em trânsito.


Medida 2: Autenticação Multifatorial para Restringir Acesso a Dados Sensíveis

- [Descrição de caso de uso]
A SecureGuard Solutions implementa autenticação multifatorial (MFA) para fortalecer o controle de acesso a sistemas e dados sensíveis. O AWS Identity and Access Management (IAM) foi configurado para exigir MFA ao acessar recursos críticos na nuvem.

- [Passos de implementação] 
1. Ativação do MFA no nível de conta da AWS e para usuários específicos do IAM.
2. Configuração de políticas do IAM para exigir MFA ao acesso a recursos identificados como sensíveis.
3. Treinamento dos usuários sobre o uso seguro do MFA e comunicação eficaz sobre a mudança nas políticas de acesso.


Medida 3: Monitoramento de Atividades na Nuvem para Detectar Sinais de Atividade Maliciosa

- [Descrição de caso de uso]
A SecureGuard Solutions desenvolveu o Amazon CloudWatch para monitoramento contínuo de atividades na nuvem. A empresa configurou alarmes para detectar comportamentos anômalos, como acessos não autorizados, e implementou o AWS CloudTrail para rastrear detalhadamente as ações realizadas nas contas da AWS.

- [Passos de implementação] 
1. Configuração de alarmes no Amazon CloudWatch para alertar sobre atividades suspeitas, como acesso fora do horário comercial.
2. Ativação do AWS CloudTrail para rastrear todas as ações realizadas nas contas da AWS.
3. Análise regular dos logs do CloudTrail para identificar padrões de comportamento e possíveis indicadores de comprometimento.

Medida 4: Implementação de Políticas de Segurança para Orientar o Uso de Dados Sensíveis

- [Descrição de caso de uso]
A SecureGuard Solutions desenvolveu e implementou políticas de segurança claras para orientar o uso de dados sensíveis. Essas políticas abordam a classificação de dados, o acesso autorizado, o compartilhamento seguro e a responsabilidade dos usuários.

- [Passos de implementação] 
1. Desenvolvimento de políticas de segurança em colaboração com as partes interessadas, incluindo a equipe de segurança da informação e dos usuários finais.
2. Comunicação ativa das políticas aos funcionários, incluindo treinamentos regulares sobre boas práticas de segurança.
3. Monitoramento contínuo do cumprimento das políticas e ajustes conforme necessário.



## Conclusão
A implementação dessas medidas na AWS fortalece significativamente a postura de segurança da SecureGuard Solutions. A empresa agora está mais bem equipada para proteger dados sensíveis, restringir o acesso não autorizado, detectar atividades maliciosas e garantir o uso seguro dessas informações. O compromisso contínuo com boas práticas de segurança e monitoramento regular garantirá a eficácia contínua dessas medidas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Medida 1: Criptografia para Proteger Dados em Trânsito e em Repouso

Serviço AWS:

Amazon S3 (serviço de armazenamento simples)
Amazon Cloud Front
Link para Documentação:

Documentação do Amazon S3 
(https://docs.aws.amazon.com/s3/)
Documentação do Amazon CloudFront 
(https://docs.aws.amazon.com/cloudfront/)

Medida 2: Autenticação Multifatorial para Restringir Acesso a Dados Sensíveis

Serviço AWS:

AWS Identity and Access Management (IAM)
Link para Documentação:

Documentação do AWS IAM 
(https://docs.aws.amazon.com/iam/)

Medida 3: Monitoramento de Atividades na Nuvem para Detectar Sinais de Atividade Maliciosa

Serviço AWS:

Amazon CloudWatch 
AWS CloudTrail 
Link para Documentação:

Documentação do Amazon CloudWatch 
(https://docs.aws.amazon.com/cloudwatch/)
Documentação do AWS CloudTrail 
(https://docs.aws.amazon.com/awscloudtrail/)

Medida 4: Implementação de Políticas de Segurança para Orientar o Uso de Dados Sensíveis

Serviço AWS:

AWS Identity and Access Management (IAM)
Link para Documentação:

Documentação do AWS IAM 
(https://docs.aws.amazon.com/iam/)

Observações Adicionais:

Verifique a documentação para obter informações detalhadas sobre configurações específicas e práticas recomendadas para cada serviço.
A implementação dessas medidas deve levar em consideração as características específicas do ambiente da SecureGuard Solutions e ser adaptada conforme necessário.

Assinatura do Responsável pelo Projeto:

Marlova Minato