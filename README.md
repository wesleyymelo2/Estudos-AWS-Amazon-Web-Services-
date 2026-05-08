# ☁️ Estudos em Computação em Nuvem

Bem-vindo ao meu repositório de estudos focado no processo e na continuidade do meu aprendizado em infraestrutura e soluções de nuvem. Sou estudante de Análise e Desenvolvimento de Sistemas e criei este espaço para registrar minha evolução prática e teórica ao longo da disciplina de Computação em Nuvem.

O objetivo aqui é aplicar e documentar arquiteturas, plataformas e serviços (IaaS, PaaS, SaaS), explorando escalabilidade, segurança e gerenciamento nas principais provedoras do mercado (AWS, Azure e Google Cloud).

---

## 🛠️ Ferramentas e Tecnologias Utilizadas no Processo

Ao longo desta jornada, utilizarei diversas ferramentas gratuitas e ambientes de simulação para construir e testar os laboratórios:

*   **Cloud Providers:** AWS Free Tier, Azure for Students, Google Cloud Free Tier.
*   **Containers & Orquestração:** Docker Desktop, Minikube (Kubernetes local).
*   **Simulação Local:** LocalStack (AWS localmente).
*   **Arquitetura & Versionamento:** Draw.io (Diagramas) e GitHub (Repositório).

---

## 🚀 Laboratórios e Entregas Práticas

Os exercícios práticos desenvolvidos durante as aulas estão organizados nas pastas abaixo:

### 📁 [01-seguranca-iam](./01-seguranca-iam/)
**Tema:** Segurança - Políticas IAM (Aula 01 a 03)
*   Criação de usuários e grupos (Administradores e SomenteLeitura) no AWS IAM.
*   Aplicação das políticas `AdministratorAccess` e `ReadOnlyAccess`.
*   Documentação detalhando o Princípio do Menor Privilégio.

### 📁 [02-escalabilidade-alta-disponibilidade](./02-escalabilidade-alta-disponibilidade/)
**Tema:** Escalabilidade e Alta Disponibilidade (Aula 03 a 05)
*   Simulação de ambiente com Docker e Docker Compose.
*   Deploy de um servidor Nginx com balanceamento de carga.
*   Testes de escalabilidade horizontal e vertical (scale up / scale out) lidando com falhas.

### 📁 [03-armazenamento-arquivos-s3](./03-armazenamento-arquivos-s3/)
**Tema:** Armazenamento e Banco de Dados (Aula 05 a 07)
*   Criação e organização de Buckets no Amazon S3.
*   Diferenciação entre armazenamento de objetos (S3) e de bloco (EBS).
*   Geração de links de acesso temporário (Presigned URLs).

### 📁 [04-containers-serverless](./04-containers-serverless/)
**Tema:** Containers e Serverless (Aula 07 a 09)
*   Criação de uma função Serverless utilizando AWS Lambda (Python 3.x).
*   Exposição da função via API Gateway.
*   Análise de vantagens e desvantagens de arquiteturas sem servidor em comparação ao EC2.

### 📁 [05-projeto-final-arquitetura](./05-projeto-final-arquitetura/)
**Tema:** Projeto Final - Arquitetura em Nuvem (Aula 09)
*   **Objetivo:** Planejamento arquitetural completo para um cenário real (ex: E-commerce na Black Friday, App de Saúde, ou IA).
*   Diagrama de arquitetura via Draw.io contemplando computação, armazenamento e segurança.
*   Estimativa de custos utilizando a Calculadora de Preços da AWS e plano de recuperação de desastres (DR).

---

## 📚 Roteiro Teórico Contínuo

Este repositório acompanha o seguinte cronograma de tópicos teóricos:

*   **Aula 01:** Segurança em Nuvem (Políticas, IAM, Modelo de Responsabilidade Compartilhada).
*   **Aula 02:** Monitoramento e Resposta a Incidentes (CloudTrail, Logs de Auditoria).
*   **Aula 03:** Escalabilidade e Alta Disponibilidade (Autoescalonamento, Balanceamento de Carga).
*   **Aula 04:** Recuperação de Desastres em Nuvem (RPO, RTO, Planos de Contingência).
*   **Aula 05:** Armazenamento e Banco de Dados (S3, EBS, RDS, NoSQL).
*   **Aula 06:** Implementação de Aplicações (Monolitos, Microserviços, Docker, Kubernetes).
*   **Aula 07:** Performance e Gerenciamento de APIs (Caching, CDN, API Gateway).
*   **Aula 08:** Custos e Faturamento (Pay-per-use, Cost Explorer, Instâncias Spot).
*   **Aula 09:** Tendências Emergentes (Multicloud, Edge Computing, IA/ML, Big Data).

---
*Documentação criada por Wesley Melo.*
