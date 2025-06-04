# Documentação das Atividades Cursadas - Aplicações Contêinerizadas com Azure Container Apps

## Visão Geral
Este documento resume os principais conceitos e aprendizados sobre Azure Container Apps, cobrindo desde fundamentos até implementação prática.

## Módulo 1: Introdução ao Azure Container Apps

### O que são Container Apps?
- Serviço totalmente gerenciado para executar aplicações em contêineres
- Permite executar microserviços e aplicações em contêineres sem gerenciar infraestrutura complexa
- Baseado no Kubernetes, mas abstrai a complexidade do gerenciamento de clusters
- Suporte a autoescala automática baseada em tráfego

### Casos de uso para Container Apps
- APIs e microserviços
- Aplicações orientadas a eventos
- Processamento em background
- Frontends web
- Aplicações com arquitetura de microsserviços

### Container Apps vs. AKS (Azure Kubernetes Service)
| Característica       | Azure Container Apps | AKS |
|----------------------|----------------------|-----|
| Complexidade         | Baixa                | Alta|
| Gerenciamento        | Totalmente gerenciado| Requer gerenciamento do cluster|
| Escala automática    | Nativa               | Configurável mas mais complexa|
| Casos de uso         | Aplicações simples a moderadas | Cargas de trabalho complexas e personalizadas|
| Custo                | Geralmente menor     | Geralmente maior|

## Módulo 2: Implantar um aplicativo de contêiner

### Explorar Aplicativos de Contêiner do Azure
- Criação de ambiente de Container Apps
- Configuração básica de um aplicativo
- Opções de implantação (imagem de contêiner, registry)
- Configuração de rede e acesso

### Explorar Contêineres nos Aplicativos de Contêiner do Azure
- Suporte a contêineres únicos ou múltiplos (sidecars)
- Configuração de variáveis de ambiente
- Definição de recursos (CPU, memória)
- Configuração de probes (readiness, liveness)

### Gerenciar revisões e segredos
- Sistema de revisões para versionamento e rollback
- Modos de tráfego (última revisão, revisão específica, divisão de tráfego)
- Gerenciamento de segredos (armazenamento seguro de credenciais)
- Integração com Azure Key Vault

## Verificação de Conhecimentos
Os questionários abordaram:
- Diferenças entre serviços de contêiner no Azure
- Seleção do serviço apropriado para diferentes cenários
- Configuração básica de um Container App
- Gerenciamento de revisões e tráfego
- Boas práticas para segurança com segredos

## Próximos Passos
- Explorar integração com outros serviços Azure
- Experimentar cenários de autoescala avançada
- Testar implantações blue-green com divisão de tráfego
- Implementar monitoramento e logging avançados
