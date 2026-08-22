# Estrutura Analítica do Projeto (EAP)

## 1. Gerenciamento do Projeto

### 1.1 Planejamento do Projeto

* 1.1.1 Elaboração do TAP
* 1.1.2 Definição do escopo e não-escopo
* 1.1.3 Identificação das restrições e premissas
* 1.1.4 Identificação dos riscos iniciais
* 1.1.5 Definição do cronograma do projeto

### 1.2 Monitoramento e Controle

* 1.2.1 Acompanhamento do cronograma
* 1.2.2 Acompanhamento do escopo
* 1.2.3 Acompanhamento dos riscos
* 1.2.4 Registro das alterações do projeto
* 1.2.5 Acompanhamento dos resultados

### 1.3 Gerenciamento de Riscos

* 1.3.1 Identificação dos riscos
* 1.3.2 Análise dos riscos
* 1.3.3 Definição das estratégias de resposta
* 1.3.4 Monitoramento dos riscos
* 1.3.5 Atualização do registro de riscos

## 2. Análise e Definição da Solução

### 2.1 Pesquisa Tecnológica

* 2.1.1 Pesquisa sobre Docker
* 2.1.2 Pesquisa sobre Podman
* 2.1.3 Pesquisa sobre gerenciamento de containers
* 2.1.4 Pesquisa sobre servidores de jogos conteinerizados
* 2.1.5 Pesquisa sobre Whitelist/Allowlist
* 2.1.6 Pesquisa sobre backup de volumes
* 2.1.7 Pesquisa sobre acesso remoto seguro

### 2.2 Análise das Soluções de Gerenciamento

* 2.2.1 Análise do Pterodactyl
* 2.2.2 Análise do Portainer
* 2.2.3 Análise do Crafty
* 2.2.4 Comparação das soluções
* 2.2.5 Definição do painel de gerenciamento

### 2.3 Análise das Soluções de Acesso Remoto

* 2.3.1 Análise de DDNS
* 2.3.2 Análise de Tailscale
* 2.3.3 Análise de túneis
* 2.3.4 Comparação das soluções
* 2.3.5 Definição da solução de acesso remoto

### 2.4 Levantamento de Requisitos

* 2.4.1 Levantamento dos requisitos funcionais
* 2.4.2 Levantamento dos requisitos não funcionais
* 2.4.3 Definição dos requisitos de segurança
* 2.4.4 Definição dos requisitos de desempenho
* 2.4.5 Definição dos requisitos de usabilidade
* 2.4.6 Definição dos requisitos de persistência
* 2.4.7 Definição dos requisitos de recuperação

### 2.5 Seleção das Tecnologias

* 2.5.1 Seleção do motor de containers
* 2.5.2 Seleção do painel de gerenciamento
* 2.5.3 Seleção das imagens-base
* 2.5.4 Seleção da solução de acesso remoto
* 2.5.5 Seleção das ferramentas de backup

## 3. Projeto da Infraestrutura

### 3.1 Arquitetura do Homelab

* 3.1.1 Definição do hardware do servidor
* 3.1.2 Definição da quantidade de RAM
* 3.1.3 Definição do armazenamento
* 3.1.4 Definição da estrutura de diretórios
* 3.1.5 Definição dos requisitos mínimos do hardware

### 3.2 Arquitetura de Containers

* 3.2.1 Definição da estrutura dos containers
* 3.2.2 Definição das redes dos containers
* 3.2.3 Definição dos volumes persistentes
* 3.2.4 Definição dos limites de recursos
* 3.2.5 Definição das configurações de funcionamento

### 3.3 Arquitetura de Rede

* 3.3.1 Definição da topologia de rede
* 3.3.2 Definição do endereçamento IP
* 3.3.3 Definição das portas de comunicação
* 3.3.4 Definição das regras de firewall
* 3.3.5 Definição do acesso remoto

### 3.4 Arquitetura de Segurança

* 3.4.1 Definição do modelo de controle de acesso
* 3.4.2 Definição das Whitelists/Allowlists
* 3.4.3 Definição das permissões de usuários
* 3.4.4 Definição da proteção do painel administrativo
* 3.4.5 Definição das políticas de atualização

### 3.5 Arquitetura de Armazenamento e Backup

* 3.5.1 Definição dos dados persistentes
* 3.5.2 Definição da estrutura dos volumes
* 3.5.3 Definição da política de backup
* 3.5.4 Definição da política de retenção
* 3.5.5 Definição do procedimento de restauração

### 3.6 Documentação da Arquitetura

* 3.6.1 Criação do diagrama da infraestrutura
* 3.6.2 Criação do diagrama dos containers
* 3.6.3 Criação do diagrama de rede
* 3.6.4 Documentação das tecnologias
* 3.6.5 Documentação das decisões arquiteturais

## 4. Preparação da Infraestrutura

### 4.1 Preparação do Hardware

* 4.1.1 Seleção do equipamento reaproveitado
* 4.1.2 Verificação da CPU
* 4.1.3 Verificação da memória RAM
* 4.1.4 Verificação do armazenamento
* 4.1.5 Teste de estabilidade do hardware

### 4.2 Instalação do Sistema Operacional

* 4.2.1 Instalação do Linux
* 4.2.2 Configuração de usuários
* 4.2.3 Configuração do armazenamento
* 4.2.4 Configuração das atualizações
* 4.2.5 Configuração básica de segurança

### 4.3 Configuração da Rede

* 4.3.1 Configuração do endereço IP
* 4.3.2 Configuração do firewall
* 4.3.3 Configuração das portas necessárias
* 4.3.4 Configuração do acesso local
* 4.3.5 Testes de conectividade

## 5. Implementação do Ambiente de Containers

### 5.1 Instalação do Motor de Containers

* 5.1.1 Instalação do motor de containers escolhido
* 5.1.2 Configuração do serviço
* 5.1.3 Configuração das permissões
* 5.1.4 Configuração das redes
* 5.1.5 Teste do ambiente de containers

### 5.2 Criação e Configuração das Imagens

* 5.2.1 Seleção das imagens-base
* 5.2.2 Criação dos Dockerfiles
* 5.2.3 Configuração das dependências
* 5.2.4 Configuração das variáveis de ambiente
* 5.2.5 Teste das imagens
* 5.2.6 Documentação das imagens

### 5.3 Configuração das Instâncias de Servidores

* 5.3.1 Implantação de uma instância de servidor
* 5.3.2 Configuração de múltiplas instâncias
* 5.3.3 Configuração dos volumes persistentes
* 5.3.4 Configuração das redes
* 5.3.5 Configuração dos limites de recursos
* 5.3.6 Validação do funcionamento das instâncias

## 6. Painel de Gerenciamento

### 6.1 Implantação do Painel

* 6.1.1 Instalação do painel escolhido
* 6.1.2 Configuração inicial
* 6.1.3 Integração com os containers
* 6.1.4 Configuração do acesso administrativo
* 6.1.5 Teste de funcionamento do painel

### 6.2 Gerenciamento dos Servidores

* 6.2.1 Criação de servidores
* 6.2.2 Inicialização dos servidores
* 6.2.3 Desligamento dos servidores
* 6.2.4 Reinicialização dos servidores
* 6.2.5 Visualização de logs
* 6.2.6 Gerenciamento dos arquivos
* 6.2.7 Monitoramento dos recursos

### 6.3 Usabilidade

* 6.3.1 Avaliação da interface
* 6.3.2 Simplificação das configurações
* 6.3.3 Teste com usuário não técnico
* 6.3.4 Identificação das dificuldades
* 6.3.5 Correção das dificuldades encontradas
* 6.3.6 Validação da usabilidade

## 7. Segurança e Controle de Acesso

### 7.1 Controle de Jogadores

* 7.1.1 Configuração da Whitelist/Allowlist
* 7.1.2 Cadastro de jogadores autorizados
* 7.1.3 Remoção de jogadores autorizados
* 7.1.4 Teste de acesso autorizado
* 7.1.5 Teste de bloqueio de acesso não autorizado

### 7.2 Segurança da Infraestrutura

* 7.2.1 Configuração do firewall
* 7.2.2 Restrição das portas
* 7.2.3 Configuração dos usuários e permissões
* 7.2.4 Proteção do painel administrativo
* 7.2.5 Atualização dos componentes
* 7.2.6 Verificação das configurações de segurança

### 7.3 Acesso Remoto Seguro

* 7.3.1 Configuração da solução de acesso remoto escolhida
* 7.3.2 Configuração das permissões de acesso
* 7.3.3 Configuração das regras de comunicação
* 7.3.4 Teste de acesso remoto autorizado
* 7.3.5 Teste de bloqueio de acesso não autorizado
* 7.3.6 Validação da segurança do acesso remoto

## 8. Backup, Persistência e Recuperação

### 8.1 Configuração do Armazenamento

* 8.1.1 Definição dos diretórios persistentes
* 8.1.2 Configuração dos volumes
* 8.1.3 Organização dos mapas e configurações
* 8.1.4 Organização dos logs
* 8.1.5 Validação da persistência dos dados

### 8.2 Automação dos Backups

* 8.2.1 Definição da política de backup
* 8.2.2 Criação do script de backup
* 8.2.3 Definição do local de armazenamento dos backups
* 8.2.4 Agendamento dos backups
* 8.2.5 Definição da retenção dos backups
* 8.2.6 Teste de execução automática

### 8.3 Restauração

* 8.3.1 Simulação de perda de dados
* 8.3.2 Restauração dos volumes
* 8.3.3 Validação dos mundos e configurações
* 8.3.4 Validação da integridade dos dados
* 8.3.5 Documentação do procedimento de recuperação

## 9. Testes e Validação

### 9.1 Testes Funcionais

* 9.1.1 Criação de servidor
* 9.1.2 Inicialização do servidor
* 9.1.3 Conexão de jogadores autorizados
* 9.1.4 Bloqueio de jogadores não autorizados
* 9.1.5 Reinicialização do servidor
* 9.1.6 Persistência dos dados
* 9.1.7 Funcionamento do painel de gerenciamento

### 9.2 Testes de Desempenho

* 9.2.1 Medição do consumo de CPU
* 9.2.2 Medição do consumo de RAM
* 9.2.3 Medição do consumo de armazenamento
* 9.2.4 Teste com três instâncias simultâneas
* 9.2.5 Teste de carga
* 9.2.6 Identificação de gargalos
* 9.2.7 Análise da estabilidade do ambiente

### 9.3 Testes de Segurança

* 9.3.1 Teste de acesso autorizado
* 9.3.2 Teste de acesso não autorizado
* 9.3.3 Teste das regras de firewall
* 9.3.4 Teste do acesso administrativo
* 9.3.5 Teste do acesso remoto
* 9.3.6 Teste das permissões dos usuários

### 9.4 Testes de Recuperação

* 9.4.1 Simulação de desligamento incorreto
* 9.4.2 Simulação de perda de dados
* 9.4.3 Recuperação através do backup
* 9.4.4 Validação da integridade dos dados
* 9.4.5 Registro dos resultados da recuperação

### 9.5 Testes de Usabilidade

* 9.5.1 Teste de configuração inicial
* 9.5.2 Teste de criação de servidor
* 9.5.3 Teste de gerenciamento de servidor
* 9.5.4 Teste de cadastro de jogadores
* 9.5.5 Teste de realização de backup
* 9.5.6 Identificação das dificuldades do usuário

### 9.6 Validação dos Requisitos

* 9.6.1 Verificação do provisionamento em menos de 5 minutos
* 9.6.2 Verificação das três instâncias simultâneas
* 9.6.3 Verificação do bloqueio de acessos não autorizados
* 9.6.4 Verificação dos requisitos funcionais
* 9.6.5 Verificação dos requisitos não funcionais
* 9.6.6 Verificação dos requisitos de segurança
* 9.6.7 Verificação dos requisitos de desempenho
* 9.6.8 Verificação dos requisitos de usabilidade

### 9.7 Critérios de Aceitação

* 9.7.1 Validação do tempo de provisionamento
* 9.7.2 Validação da capacidade de execução simultânea
* 9.7.3 Validação do controle de acesso
* 9.7.4 Validação da persistência dos dados
* 9.7.5 Validação dos backups
* 9.7.6 Validação da restauração dos dados
* 9.7.7 Validação da usabilidade
* 9.7.8 Validação final do protótipo

### 9.8 Correção de Não Conformidades

* 9.8.1 Registro das não conformidades
* 9.8.2 Análise das causas
* 9.8.3 Correção dos problemas
* 9.8.4 Reexecução dos testes
* 9.8.5 Validação das correções

## 10. Documentação e Entrega

### 10.1 Documentação Técnica

* 10.1.1 Documentação da arquitetura
* 10.1.2 Documentação da instalação
* 10.1.3 Documentação dos containers
* 10.1.4 Documentação do painel
* 10.1.5 Documentação da segurança
* 10.1.6 Documentação dos backups
* 10.1.7 Documentação da restauração
* 10.1.8 Documentação dos testes

### 10.2 Guia do Administrador Doméstico

* 10.2.1 Requisitos mínimos de hardware
* 10.2.2 Instalação do sistema
* 10.2.3 Configuração da rede
* 10.2.4 Instalação dos containers
* 10.2.5 Configuração do painel
* 10.2.6 Criação de servidores
* 10.2.7 Cadastro de jogadores
* 10.2.8 Configuração de segurança
* 10.2.9 Realização de backups
* 10.2.10 Restauração de backups
* 10.2.11 Solução de problemas comuns

### 10.3 Consolidação dos Resultados

* 10.3.1 Consolidação dos resultados dos testes
* 10.3.2 Consolidação dos indicadores de desempenho
* 10.3.3 Registro dos resultados de segurança
* 10.3.4 Registro dos resultados de usabilidade
* 10.3.5 Registro das limitações do projeto
* 10.3.6 Registro das conclusões

### 10.4 Entrega do Protótipo

* 10.4.1 Preparação do ambiente final
* 10.4.2 Verificação da documentação
* 10.4.3 Verificação dos componentes da solução
* 10.4.4 Validação final do protótipo
* 10.4.5 Preparação da demonstração

### 10.5 Apresentação Final

* 10.5.1 Preparação dos slides
* 10.5.2 Preparação da demonstração
* 10.5.3 Organização dos resultados
* 10.5.4 Preparação para a defesa
* 10.5.5 Apresentação do projeto