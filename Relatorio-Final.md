# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 11/10/2024

Empresa: Abstergo Industries 

Responsável: Cinthia Rocha

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na nuvem na empresa Abstergo Industries, realizado por Cinthia Rocha. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 

Amazon S3 (Simple Storage Service) é um serviço de armazenamento de objetos na nuvem, projetado para armazenar e recuperar qualquer volume de dados a partir de qualquer lugar da web. Seu foco principal é oferecer:

- Escalabilidade: o S3 permite que você armazene desde pequenos arquivos até grandes conjuntos de dados, adaptando-se às suas necessidades de forma flexível e escalável; 
- Disponibilidade: Os dados armazenados no S3 são altamente duráveis e disponíveis, com redundância em múltiplas regiões geográficas para garantir a segurança dos seus dados; 
- Segurança: o S3 oferece diversas opções de segurança, como criptografia de dados em trânsito e em repouso, controle de acesso baseado em políticas e autenticação multi-fator; 
- Performance: o S3 oferece alta performance para leitura e escrita de dados, permitindo o acesso rápido aos seus arquivos; e
- Custo-benefício: o modelo de pagamento por uso do S3 torna-o uma opção econômica para armazenar dados, especialmente para grandes volumes.

O S3 pode ser utilizado para diversas finalidades, como:

- Armazenamento de backups: armazenar cópias de segurança de dados importantes;
- Hospedagem de websites estáticos: hospedar sites e aplicativos web que não requerem um servidor;
- Armazenamento de arquivos de mídia: armazenar imagens, vídeos e outros arquivos de mídia;
- Análise de dados: armazenar dados para análise e processamento; e
- Arquivamento de dados: armazenar dados a longo prazo, com baixo custo.

Etapa 2: 

Amazon DynamoDB é um serviço de banco de dados NoSQL, totalmente gerenciado e sem servidor, projetado para oferecer desempenho consistente em qualquer escala. Seu foco principal é fornecer uma solução de armazenamento de dados altamente escalável, durável e rápida para aplicações modernas.

Em resumo, o foco do DynamoDB está em:

- Desempenho consistente: o DynamoDB garante tempos de resposta baixos e previsíveis, mesmo com cargas de trabalho variáveis;
- Escalabilidade: ele pode escalar automaticamente para acomodar aumentos repentinos no tráfego, sem a necessidade de intervenção manual;
- Disponibilidade: o DynamoDB oferece alta disponibilidade, com replicação em múltiplas regiões para garantir a continuidade dos seus negócios;
- Flexibilidade: permite que você modele seus dados de forma flexível, sem a necessidade de um esquema fixo como em bancos de dados relacionais; e
- Sem servidor: você não precisa gerenciar servidores, o que simplifica a operação e reduz custos.

O DynamoDB é ideal para uma variedade de casos de uso, incluindo:

- Aplicações móveis: armazenar dados de usuários, preferências, e informações de sessões;
- Aplicações de Internet das Coisas (IoT): armazenar dados de sensores e dispositivos conectados;
- Análise de dados em tempo real: processar grandes volumes de dados em tempo real; e
- Sistemas de recomendação: armazenar e consultar dados para personalizar recomendações.

Em comparação com bancos de dados relacionais, o DynamoDB se destaca por:

- Flexibilidade: não exige um esquema fixo, permitindo adaptar-se a mudanças nos requisitos da aplicação;
- Desempenho: oferece latência consistente e alta taxa de transferência, mesmo com grandes volumes de dados; e
- Escalabilidade: pode escalar automaticamente para atender a picos de demanda.

Etapa 3: 

Amazon API Gateway é um serviço gerenciado pela AWS que serve como uma porta de entrada para suas APIs, tanto RESTful quanto WebSocket. Seu foco principal é simplificar a criação, publicação, manutenção, monitoramento e proteção de APIs em qualquer escala.

Em resumo, o API Gateway se concentra em:

- Criar e publicar APIs: permite a criação rápida de APIs, tanto RESTful para aplicações tradicionais, quanto WebSocket para aplicações em tempo real;
- Gerenciar o ciclo de vida da API: facilita o gerenciamento de diferentes versões da sua API, permitindo que você faça alterações e implante novas versões sem afetar as existentes;
- Escalabilidade: o API Gateway se adapta automaticamente à demanda, escalando para atender a um grande número de requisições sem comprometer a performance;
- Segurança: oferece diversas opções de segurança, como autenticação, autorização, e controle de acesso baseado em políticas;
- Monitoramento: permite monitorar o desempenho da sua API, identificando problemas e gargalos; e
- Integração com outros serviços AWS: integra-se facilmente com outros serviços da AWS, como Lambda, DynamoDB e S3, facilitando a criação de aplicações completas.

O API Gateway serve para:

- Front-end para microsserviços: atua como uma camada única de acesso para diversos microsserviços, simplificando a comunicação entre eles;
- Integração de sistemas: permite a integração de sistemas legados com novas aplicações;
- Desenvolvimento de APIs para dispositivos móveis: facilita a criação de APIs para aplicativos móveis; e
- Criação de APIs para aplicações em tempo real: permite a criação de APIs WebSocket para aplicações que exigem comunicação bidirecional em tempo real.

## Conclusão
A implementação de ferramentas na nuvem na empresa *Abstergo Industries tem como benefícios esperados: pagamento por uso, escalabilidade automática, gerenciamento simplificado e alta disponibilidade*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Considerações Adicionais

Como sugestão de novas ferramentas, têm-se: Amazon EC2: se for necessário executar alguma lógica de negócio mais complexa ou integrar com sistemas legados, pode ser necessário utilizar instâncias EC2;
Amazon Lambda: para executar funções sem servidor, como processamento de imagens ou envio de e-mails; e
Amazon CloudFront: para distribuir o conteúdo estático armazenado no S3 com baixa latência.

Assinatura do Responsável pelo Projeto:

Cinthia Rocha
