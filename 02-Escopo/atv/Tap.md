# Termo de abertura de projeto
**Projeto:** Gerenciamento de servidores de jogos com containers.
**Equipe do Projeto:** Gabriel dos Santos Cardozo, Vinicius Rambo Padilha.

## 1. Justificativa
A hospedagem de servidores de jogos multijogador geralmente exige conhecimentos técnicos avançados ou o aluguel de serviços em nuvem, o que afasta o usuário doméstico, paralelamente, o ambiente online público de jogos apresenta riscos crescentes de segurança e exposição a comunidades tóxicas, gerando preocupação para pais e responsáveis que buscam um ambiente de entretenimento seguro para crianças, adolescentes e os proprios adultos.

A adoção da tecnologia de contêineres (como Docker / Podman) em hardwares ociosos ou de baixo custo (Homelabs) justifica-se por democratizar o acesso a infraestruturas privadas. Ela oferece um ambiente leve, isolado, seguro e padronizado, permitindo que usuários comuns reaproveitem computadores antigos para criar "espaços seguros" online.

- **Por que o projeto é necessário?** Para otimizar o uso de hardware reaproveitado (Homelabs), isolar falhas e automatizar o processo de criação de servidores privados, o foco é fornecer um ambiente isolado, seguro e de uso pessoal, onde o administrador (ex: um pai ou responsável) tenha controle total sobre quem acessa o servidor.

- **Quais os motivos que geraram a sua necessidade?** A dificuldade do usuário comum em configurar servidores locais, a falta de privacidade e controle em servidores públicos, a preocupação com a segurança infantil na internet, e a vontade de reaproveitar equipamentos antigos (PCs sobrando) para hospedar serviços locais com baixa latência e custo zero, focados em uso de jogos.

- **Quais os benefícios?** Criação de um ambiente de jogo 100% seguro e controlado (com mapeamento de jogadores permitidos/whitelists), reaproveitamento de hardware descartado (sustentabilidade tecnológica), redução drástica no tempo e complexidade de implantação para usuários leigos e economia de recursos computacionais via conteinerização.

## 2. Objetivo de projeto
### Objetivo Geral:

Implementar e documentar uma arquitetura de infraestrutura ágil, gratuita e acessível para implantação e gerenciamento de servidores privados de jogos utilizando tecnologia de contêineres, voltada para usuários de Homelabs e ambientes domésticos que buscam segurança e controle.

### Objetivo Específico (SMART):

- **Specific (Específico):** Desenvolver um ambiente conteinerizado (ex: via Docker ou Podman) integrado a um painel de gerenciamento simplificado, capaz de hospedar múltiplas instâncias de jogos, com foco na facilidade de uso e na implementação de controles de acesso (listas de permissão/whitelists) para garantir a segurança dos jogadores.

- **Measurable (Mensurável):** O sistema deve ser capaz de provisionar um novo servidor seguro em menos de 5 minutos, manter pelo menos 3 instâncias operando em hardware doméstico de baixo desempenho, e ter 100% de eficácia no bloqueio de conexões não autorizadas durante os testes.

- **Agreed (Acordado):** O escopo, as tecnologias e os propósitos (sem fins lucrativos e foco doméstico) foram acordados entre a equipe executora (Gabriel e Vinicius).

- **Realistic (Realista):** O projeto utilizará ferramentas de código aberto e será testado em hardware reaproveitado já disponível para a equipe (simulando um ambiente real de Homelab), dispensando custos adicionais.

- **Time Bound (Limitado no tempo):** O protótipo funcional, junto com a documentação voltada para o administrador doméstico, será entregue e apresentado no prazo de 24 semanas (aproximadamente 6 meses).

### 3. Escopo

Os resultados esperados e produtos entregues por este projeto incluem:

- Pesquisa e definição da arquitetura de contêineres a ser utilizada, priorizando o baixo consumo de recursos.
- Configuração do servidor hospedeiro (Sistema Operacional Linux orientado a NAS/Homelab).
- Criação e/ou customização de imagens de contêineres (Dockerfile) prontas para uso.
- Implantação de uma interface web de gerenciamento (ex: Pterodactyl, Portainer ou Crafty) que abstraia a complexidade técnica para o usuário final.
- Implementação e documentação de rotinas de segurança e controle de acesso (Whitelist/Allowlist), garantindo que apenas usuários previamente cadastrados possam ingressar nos servidores.
- Configuração de rotinas automatizadas de backup dos volumes de dados (mapas e configurações).
- Documentação técnica didática, contendo um "Guia Rápido" voltado para o usuário doméstico (pais/responsáveis) configurar e proteger o servidor.

### 4. Não-Escopo

O que não será atendido pelo projeto:

- Comercialização da solução, uso corporativo ou adaptação para fins lucrativos de provedores de hospedagem.
- Desenvolvimento de jogos, modificações (mods) ou plugins para os servidores.
- Criação de portais para a comunidade de jogadores ou sites de divulgação pública.
- Fornecimento de infraestrutura em nuvem paga (foco exclusivo em implantação local/Homelab).
- Sistemas de monetização, VIPs ou lojas de itens (billing) dentro dos jogos.

### 5. Restrições

- Prazo: O projeto deve ser concluído e apresentado na data estipulada pelo cronograma acadêmico.
- Orçamento: O projeto possui caráter estritamente não-lucrativo e custo zero, sendo restrito ao uso de softwares open-source e hardware próprio/reaproveitado da equipe.
- Hardware: O desempenho será naturalmente limitado pela capacidade de processamento e RAM do equipamento doméstico ("PC sobrando") utilizado para os testes.

### 6. Projetos inter-relacionados

- **Configuração de Infraestrutura de Redes Domésticas:** Dependência da configuração de redirecionamento de portas (Port Forwarding) em roteadores residenciais e uso de serviços de DNS Dinâmico (DDNS) ou túneis (como Cloudflare Tunnels/Tailscale) para expor o servidor de forma segura sem IP fixo.
- **Sistema de Armazenamento:** Dependência de um disco ou partição no host para o mapeamento seguro e persistência dos mundos e logs.

### 7. Riscos iniciais

- Risco de **Usabilidade**: A interface ou o processo de configuração inicial (como abertura de portas no roteador residencial) ainda se mostrar muito complexa para o público-alvo (pais/leigos).
- Risco **Técnico**: Alta curva de aprendizado inicial da equipe na orquestração de contêineres e na documentação para torná-la acessível.
- Risco de **Desempenho**: Limitação física do hardware antigo utilizado, podendo causar travamentos (OOM Killer) caso os jogos demandem mais RAM do que o Homelab possui.
- Risco de **Integridade**: Perda de dados devido a desligamentos incorretos do computador doméstico (ex: quedas de energia na residência).

### 8. Tempo estimado

O tempo estimado para a conclusão total do projeto é de 24 semanas (aproximadamente 6 meses), distribuídas nas seguintes fases macro:

- Semanas 1 a 6: Planejamento, pesquisa tecnológica com foco em soluções leves para Homelabs, aprofundamento teórico e desenho da arquitetura.
- Semanas 7 a 14: Preparação do ambiente Linux, instalação do motor de contêineres, testes de imagens e configuração de conexões remotas seguras (DDNS/Túneis).
- Semanas 15 a 18: Implantação do painel de gerenciamento, configuração das listas de controle de acesso (Whitelists) e rotinas automatizadas de backup.
- Semanas 19 a 22: Fase de testes práticos no hardware reaproveitado, simulações de estresse, validação de bloqueios de segurança e ajustes de estabilidade.
- Semanas 23 a 24: Criação da documentação didática (guia do usuário administrador/pais), revisão final e preparação de ambiente e slides para a defesa do projeto.