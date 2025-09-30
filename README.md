Projeto: PREVISÃO DE CHUVAS EM  ÁREAS DE RISCO

Este projeto foi desenvolvido na disciplina Engenharia de Dados em Nuvem, com o objetivo de construir uma solução de previsão de chuvas em áreas de risco, utilizando serviços on-demand da AWS.

O pipeline implementado contempla duas abordagens complementares:

Processamento em tempo real (streaming)

Processamento em batch (em lotes)

- PROCESSAMENTO EM TEMPO REAL (Streaming)

Ingestão de dados via AWS Lambda (Producer e Consumer).

Transmissão de eventos em tempo real utilizando Kinesis Data Streams.

Processamento contínuo e integração com CloudWatch para monitoramento e alertas.

Geração de alertas críticos em tempo real via SNS (SMS e e-mail).

- PROCESSAMENTO EM BATCH (Lotes)

Dados armazenados em S3 nas camadas raw (dados brutos) e gold (dados tratados).

Utilização do AWS Glue para ETL (extração, transformação e carga).

Consultas analíticas e exploração de dados com Athena.

Preparação de datasets históricos para análises preditivas.

Integração com pipelines de machine learning para previsão de chuvas.

 SEGURANÇA E GOVERNANÇA

Implementação de boas práticas de IAM Roles para controle de acesso.

Gestão de políticas de segurança e governança de dados em nuvem.

- Monitoramento e Custos

Monitoramento e automação com CloudWatch.

Experiência prática com custos on-demand e otimização de recursos.

- PRINCIPAIS APRENDIZADOS

Construção de pipelines escaláveis em nuvem.

Processamento híbrido (tempo real + batch).

Boas práticas de segurança e governança.

Monitoramento e otimização de custos.

Entrega de alertas críticos em tempo real.

- IMPACTO E PRÓXIMOS PASSOS

Este projeto reforça a importância da engenharia de dados em nuvem para áreas como logística, agricultura e defesa civil, ao permitir análises históricas (batch) e reativas (streaming).

Os próximos passos incluem:

Expansão do pipeline para suportar dados de diferentes fontes meteorológicas.

Integração com modelos de machine learning para previsões mais precisas.

Criação de dashboards interativos para acompanhamento em tempo real.
