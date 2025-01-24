# Plano de Estudos: Roadmap para DevOps Engineer

## Semana 1: Terraform
- [ ] **Dia 1:** Introdução ao Terraform
  - [ ] Princípios básicos de infraestrutura como código (IaC)
  - [ ] Instalação e configuração do Terraform
  - [ ] Estrutura de arquivos HCL (HashiCorp Configuration Language)
  - **Recursos Adicionais:**
    - [Documentação Oficial do Terraform](https://developer.hashicorp.com/terraform/docs)
    - [Tutorial: Introdução ao Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started)
- [ ] **Dia 2:** Providers e Configuração de Recursos
  - [ ] Uso de providers (AWS, Azure, GCP)
  - [ ] Configuração básica de recursos como VPC, EC2 e S3 na AWS
  - **Recursos Adicionais:**
    - [Exemplos de Configuração de Providers](https://developer.hashicorp.com/terraform/docs/providers)
- [ ] **Dia 3:** State Management
  - [ ] Conceitos de state no Terraform
  - [ ] Remote state e locking
  - **Recursos Adicionais:**
    - [Gerenciamento de State no Terraform](https://developer.hashicorp.com/terraform/docs/state)
- [ ] **Dia 4:** Módulos e Reutilização de Código
  - [ ] Criação de módulos reutilizáveis
  - [ ] Compartilhamento e versionamento de módulos
  - **Recursos Adicionais:**
    - [Desenvolvimento de Módulos no Terraform](https://developer.hashicorp.com/terraform/docs/modules)
- [ ] **Dia 5:** Workspaces e Ciclo de Vida
  - [ ] Uso de workspaces para múltiplos ambientes
  - [ ] Configuração de dependências e ciclo de vida de recursos
  - **Recursos Adicionais:**
    - [Workspaces no Terraform](https://developer.hashicorp.com/terraform/docs/state/workspaces)
- [ ] **Dia 6:** Troubleshooting e Boas Práticas
  - [ ] Debugging de erros comuns
  - [ ] Estruturação de código e boas práticas
  - **Recursos Adicionais:**
    - [Boas Práticas no Terraform](https://developer.hashicorp.com/terraform/docs/best-practices)
- [ ] **Dia 7:** Revisão e Projeto Prático
  - [ ] Aplicar Terraform para criar uma infraestrutura simples na AWS
  - **Recursos Adicionais:**
    - [Repositório: Estudo de Terraform](https://github.com/tdsantos/estudo-terraform)

## Semana 2: Docker
- [ ] **Dia 1:** Revisão de Conceitos e Práticas
  - [ ] Configuração de volumes para persistência de dados
  - [ ] Montagem de containers otimizados por tipo de aplicação
  - **Recursos Adicionais:**
    - [Documentação Oficial do Docker](https://docs.docker.com/)
    - [Guia de Melhores Práticas para Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
- [ ] **Dia 2:** Teste Prático
  - [ ] Montar um container que inclui volumes e configuração personalizada
  - **Recursos Adicionais:**
    - [Exemplos de Docker no GitHub](https://github.com/docker)

## Semana 3: Kubernetes
- [ ] **Dia 1:** Conceitos Básicos
  - [ ] Estrutura do Kubernetes (Pods, Nodes, Deployments)
  - [ ] Instalação de um cluster local (Minikube ou Kind)
  - **Recursos Adicionais:**
    - [Documentação Oficial do Kubernetes](https://kubernetes.io/docs/home/)
    - [Guia de Início Rápido com Minikube](https://kubernetes.io/docs/start/)
- [ ] **Dia 2:** Configuração e Gerenciamento de Recursos
  - [ ] Criação de Pods e Deployments
  - [ ] Configuração de Services e Ingress
  - **Recursos Adicionais:**
    - [Tutoriais de Kubernetes](https://kubernetes.io/docs/tutorials/)
- [ ] **Dia 3:** Escalabilidade e Manutenção
  - [ ] Configuração de autoscaling
  - [ ] Atualizações e rollback de deployments
  - **Recursos Adicionais:**
    - [Escalonamento Horizontal de Pods](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)
- [ ] **Dia 4:** Persistência e Configuração
  - [ ] Configuração de volumes persistentes (Persistent Volumes e Persistent Volume Claims)
  - [ ] ConfigMaps e Secrets
  - **Recursos Adicionais:**
    - [Gerenciamento de Configuração no Kubernetes](https://kubernetes.io/docs/concepts/configuration/)
- [ ] **Dia 5:** Monitoramento e Troubleshooting
  - [ ] Ferramentas de monitoramento como Prometheus e Grafana
  - [ ] Debugging de aplicações no cluster
  - **Recursos Adicionais:**
    - [Monitoramento de Aplicações no Kubernetes](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-metrics-pipeline/)
- [ ] **Dia 6:** Prática e Projeto
  - [ ] Deploy de uma aplicação completa com escalabilidade e volumes persistentes
  - **Recursos Adicionais:**
    - [Repositório: Docker Desktop - Kubernetes - Terraform Examples](https://github.com/greg-reese/docker-desktop-kubernetes-terraform-examples)
- [ ] **Dia 7:** Revisão Geral
  - [ ] Revisão de todos os conceitos e execução de testes práticos
  - **Recursos Adicionais:**
    - [Curso: Deploy de Aplicações com Docker, Kubernetes e Terraform](https://www.udemy.com/course/deploy-de-aplicacoes-com-docker-k8s-terraform-kubernetes-e-terraform/)

## Semana 4: GitHub Actions
- [ ] **Dia 1:** Introdução ao GitHub Actions
  - [ ] Estrutura de workflows (YAML)
  - [ ] Eventos e gatilhos
  - **Recursos Adicionais:**
    - [Documentação Oficial do GitHub Actions](https://docs.github.com/pt/actions)
    - [O que é o GitHub Actions? Como CI/CD e automação funcionam no GitHub](https://resources.github.com/pt-BR/devops/tools/automation/actions/)
- [ ] **Dia 2:** Criação de Workflows Básicos
  - [ ] Testes automatizados
  - [ ] Deploy contínuo
  - **Recursos Adicionais:**
    - [Gerenciamento e automação de workflow com o GitHub Actions](https://resources.github.com/pt-br/learn/pathways/automation/intermediate/workflow-automation-with-github-actions/)
- [ ] **Dia 3:** Workflows Avançados
  - [ ] Uso de secrets
  - [ ] Criação de jobs paralelos
  - **Recursos Adicionais:**
    - [Sobre as GitHub Actions](https://docs.github.com/pt/actions/about-github-actions)
- [ ] **Dia 4:** Integração com AWS
  - [ ] Deploy de infraestrutura e aplicações na AWS via Actions
  - **Recursos Adicionais:**
    - [AWS para GitHub Actions](https://github.com/aws-actions)
    - [Configure fluxos de trabalho do GitHub Actions com uma nova Ação GitHub para criar aplicações sem servidor](https://aws.amazon.com/pt/about-aws/whats-new/2021/06/configure-github-actions-workflows-with-new-github-action-for-building-serverless-applications/)
- [ ] **Dia 5:** Troubleshooting e Boas Práticas
  - [ ] Debugging de workflows
  - [ ] Estruturação e organização de repositórios
  - **Recursos Adicionais:**
    - [Implantação automatizada avançada no GitHub Actions](https://resources.github.com/pt-br/learn/pathways/automation/intermediate/advanced-automated-deployment-in-github-actions/)

## Semana 5: Linux
- [ ] **Dia 1:** Revisão de Comandos Essenciais
  - [ ] Navegação no sistema de arquivos
  - [ ] Gerenciamento de processos
  - **Recursos Adicionais:**
    - [Guia Básico de Comandos Linux](https://www.hostinger.com.br/tutoriais/comandos-basicos-linux)
- [ ] **Dia 2:** Scripting Básico
  - [ ] Criação de scripts Bash para automação
  - **Recursos Adicionais:**
    - [Introdução ao Shell Scripting](https://aurelio.net/shell/)
- [ ] **Dia 3:** Troubleshooting de Rede
  - [ ] Comandos para análise de rede (netstat, ping, traceroute)
  - [ ] Configuração de interfaces e roteamento
  - **Recursos Adicionais:**
    - [Diagnóstico de Rede no Linux](https://www.redhat.com/sysadmin/basic-network-troubleshooting)
- [ ] **Dia 4:** Gerenciamento de Permissões e Usuários
  - [ ] Comandos chmod, chown e usermod
  - **Recursos Adicionais:**
    - [Gerenciamento de Usuários e Permissões no Linux](https://www.tecmint.com/manage-users-and-groups-in-linux/)
- [ ] **Dia 5:** Prática e Projeto
  - [ ] Resolver problemas comuns simulados no ambiente Linux
  - **Recursos Adicionais:**
    - [Desafios Práticos de Linux](https://linuxjourney.com/)

## Semana 6: AWS para Certificação SAA
- [ ] **Dia 1:** Introdução e Serviços Essenciais
  - [ ] EC2, S3, RDS, e IAM
  - **Recursos Adicionais:**
    - [AWS Certified Solutions Architect – Associate SAA-C03 Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions_Architect_Associate_Exam_Guide.pdf)
- [ ] **Dia 2:** Networking na AWS
  - [ ] VPC, subnets, security groups
  - **Recursos Adicionais:**
    - [Amazon VPC Documentation](https://docs.aws.amazon.com/vpc/index.html)
- [ ] **Dia 3:** Ferramentas de Automação
  - [ ] AWS CLI e CloudFormation
  - **Recursos Adicionais:**
    - [AWS Command Line Interface Documentation](https://docs.aws.amazon.com/cli/index.html)
    - [AWS CloudFormation Documentation](https://docs.aws.amazon.com/cloudformation/index.html)
- [ ] **Dia 4:** Escalabilidade e Alta Disponibilidade
  - [ ] Load Balancers, Auto Scaling
  - **Recursos Adicionais:**
    - [Elastic Load Balancing Documentation](https://docs.aws.amazon.com/elasticloadbalancing/index.html)
    - [Amazon EC2 Auto Scaling Documentation](https://docs.aws.amazon.com/autoscaling/ec2/index.html)
- [ ] **Dia 5:** Revisão e Simulados
  - [ ] Testes práticos e simulados da certificação
  - **Recursos Adicionais:**
    - [AWS Certified Solutions Architect – Associate Sample Questions](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions_Architect_Associate_Sample_Questions.pdf)

## Semana 7: Inteligência Artificial para DevOps
- [ ] **Dia 1:** Introdução à IA no DevOps
  - [ ] Casos de uso e ferramentas principais
  - **Recursos Adicionais:**
    - [Inteligência Artificial aplicada ao DevOps](https://www.redhat.com/pt-br/topics/devops/ai-devops)
- [ ] **Dia 2:** Integração com Monitoramento
  - [ ] Uso de IA para análise de logs
  - **Recursos Adicionais:**
    - [Análise de Logs com IA](https://www.ibm.com/cloud/blog/ai-powered-log-analysis)
- [ ] **Dia 3:** Automação com IA
  - [ ] Ferramentas para automação inteligente
  - **Recursos Adicionais:**
    - [AI-Infra-Automation-Toolbox](https://github.com/chaos4455/AI-Infra-Automation-Toolbox)

## Semana 8: Agentes e Tecnologias Correlatas
- [ ] **Dia 1:** Overview de Agentes
  - [ ] Conceito de swarm e agentes multi-inteligentes
  - **Recursos Adicionais:**
    - [OpenAI Swarm: Um Framework para Sistemas Multiagentes](https://lablab.ai/blog/understanding-openai-swarm-a-framework-for-multi-agent-systems)
    - [Revisão da CrewAI: Uma Plataforma Multiagente de Código Aberto](https://textcortex.com/pt/post/crewai-review)

## Semana 9: Python para DevOps
- [ ] **Dia 1:** Revisão de Python
  - [ ] Estruturas básicas e manipulação de arquivos
  - **Recursos Adicionais:**
    - [W3Schools: Tutorial de Python](https://www.w3schools.com/python/)
    - [Python.org: Tutorial Oficial](https://docs.python.org/3/tutorial/)
- [ ] **Dia 2:** CrewAI e Pydantic AI
  - [ ] Uso prático e integração
  - **Recursos Adicionais:**
    - [CrewAI: Um Guia com Exemplos de Sistemas de Múltiplos Agentes](https://www.datacamp.com/pt/tutorial/crew-ai)
    - [Pydantic: Validação de Dados para Python](https://docs.pydantic.dev/)

## Semana 10: Ferramentas de Fluxo de Trabalho
- [ ] **Dia 1:** Langflow e Flowise
  - [ ] Introdução e casos de uso
  - **Recursos Adicionais:**
    - [Langflow: Interface de Usuário para LangChain](https://github.com/logspace-ai/langflow)
    - [Flowise: Ferramenta de Fluxo de Trabalho para LLMs](https://github.com/FlowiseAI/Flowise)
- [ ] **Dia 2:** Dify e N8N
  - [ ] Integração e automação de processos
  - **Recursos Adicionais:**
    - [Dify: Plataforma para Aplicações de IA](https://dify.ai/)
    - [N8N: Ferramenta de Automação de Fluxo de Trabalho](https://n8n.io/)

