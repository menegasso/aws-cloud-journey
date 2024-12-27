
## Introdução ao Cloud 101

### Sobre o Curso
O objetivo deste curso é estabelecer uma base para o conhecimento da nuvem.

Conteúdos:
* Definir a computação em nuvem e descrever seus benefícios
* Comparar os modelos de implantação e serviços de computação em nuvem
* Identificar a infraestrutura global da AWS
* Discutir o modelo de responsabilidade compartilhada
* Descrever o Well-Architected Framework e sua função na construção de arquiteturas flexíveis e confiáveis
* Identificar o uso, os recursos e os benefícios dos principais serviços da Amazon Web Services (AWS)
* Praticar o uso dos principais serviços da AWS em um ambiente de laboratório
* Descrever quatro carreiras de computação em nuvem de nível básico

## Módulo I - Certificações
Sobre carreiras dentro de cloud computing:
* Cloud Practitioner
* Arquiteto de soluções: Associate
* Arquiteto de soluções: Professional
* Desenvolvedor: Associate
* Administrador SysOps: Associate
* Engenheiro DevOps: Professional

## Módulo II - Introdução à computação em Nuvem
O  serviço de nuvem e os métodos de implementação fornecem diferentes níveis de controle, flexibilidade e gerenciamento.

### Os modelos de serviço incluem:
* Infraestrutura como serviço (IaaS)
* Plataforma como serviço (PaaS)
* Software como serviço (SaaS)

### As modelos de implementação incluem
* Nuvem
* Híbrida
* On-premises

### Modelo de serviço IaaS
A infraestrutura como serviço (IaaS) engloba os componentes básicos de TI na nuvem. Normalmente, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço de armazenamento de dados. Produtos considerados IaaS AWS: Amazem EC2, Amazon Simple Storage Service (Amazon S3), Amazon Relational Database Service (Amazon RDS) e Amazon Route 53.

### Modelo de serviço PaaS
A plataforma como serviço (PaaS) elimina a necessidade das organizações gerenciarem a infraestrutura subjacente (geralmente hardware e sistemas operacionais). Um exemplo é o AWS Elastic Beanstalk.

### Modelo de serviço SaaS
Software como serviço (SaaS) é um produto de software completo que o provedor de serviços executa e gerencia. Com uma oferta de SaaS, não é necessário pensar na manutenção do serviço ou no gerenciamento da infraestrutura subjacente. Você só precisa pensar em como utilizará um item específico. Exemplos desse modelo são sites de vidoconferência, sites de email e etc. 

### Modelo de implementação em Nuvem
Em um modelo de implementação baseado em nuvem, você pode migrar as aplicações existentes para a nuvem ou criar novas aplicações na nuvem.

### Modelo de implementação Híbrida
Em uma implementação Híbrida, os recursos baseados na nuvem são conectados a uma infraestrutura on-premises, integrando recursos baseados na nuvem a aplicações de TI legadas.

### Modelo de implementação On-premises
Implementação em nuvem privada. Nesse modelo os recursos são implantados on=premisses por meio de ferramentas de virtualização e gerenciamento de recursos.

## Módulo III - Introdução à AWS
* Conceito de Região: local físico com agrupamento de datacenters. Cada grupo de datacenters lógico é chamado de zona de disponibilidade. Cada Região consiste em várias zonas de disponibilidade isoladas e separadas fisicamente em uma área geográfica.

* Conceito de Zona de disponibilidade: é uma área circunscrita dentro de uma região que pode abrigar um ou mais datacenters (geralmente três);

* Local de Borda (edge locations): são conectadas as regiões da aws por meio da rede da AWS.

### AWS Well-Architected Framework
São os 5 pilares da aws:
* Excelência Operacional
* Segurança
* Confiabilidade
* Eficiência de performance
* Otimização de custos

-- Você pode utilizar para criar a sua arquitetura na nuvem.

## Módulo IV - Principais Serviços da AWS (Core services)

## Amazon Virtual Private Cloud (VPC)
O Amazon Virtual Private Cloud (Amazon VPC) é um serviço que permite executar recursos da AWS em uma rede virtual isolada logicamente definida por você.

### O Amazon Elastic Compute Cloud (Amazon EC2) 
É um serviço da Web que disponibiliza capacidade computacional segura e redimensionável na nuvem. Ele foi projetado para facilitar a computação em nuvem na escala da Web para os desenvolvedores.

### O Amazon CloudWatch 
É um serviço de monitoramento e observação criado para engenheiros de DevOps, desenvolvedores, engenheiros de segurança de sites e gerentes de TI. O CloudWatch fornece dados e
insights factíveis para monitorar suas aplicações.

### Amazon Simple Notification Service (Amazon SNS) 
É um serviço da Web que facilita a configuração, a operação e o envio de notificações usando a nuvem. Ele fornece aos desenvolvedores um recurso altamente escalável, flexível e econômico para publicar mensagens de uma aplicação e imediatamente entregá-las aos assinantes. Esses assinantes podem ser destinatários de notificação ou outras aplicações.

### Identity and Access Management (IAM)
É um sistema de gerenciamento de segurança centralizado incluído em todas as contas da AWS para controlar o acesso de identidade aos produtos da AWS. Ao anexar políticas de permissão do IAM a identidades, você pode gerenciar quais serviços cada identidade pode acessar e o tipo de ação que a identidade pode executar.

### Amazon Simple Storage Service (S3)
É um armazenamento de objetos projetado para armazenar e recuperar qualquer quantidade de dados de qualquer lugar e a qualquer momento. É um serviço de armazenamento simples que oferece escalabilidade praticamente ilimitada, durabilidade, disponibilidade, performance e segurança líderes do setor por um custo muito baixo.

### AWS Lambda 
É um serviço computacional sem servidor que você pode usar para executar código de role sem provisionar nem gerenciar servidores. Você pode usar o Lambda para executar código de role para praticamente qualquer tipo de aplicação ou serviço de backend. Faça upload de seu código que o Lambda se encarrega de todos os itens necessários para executar e dimensionar seu código para alta disponibilidade.

### Amazon DynamoDB 
É um banco de dados nao relacional sem servidor que pode armazenar e recuperar qualquer quantidade de dados e atender a qualquer nível de tráfego de solicitações. Você pode expandir verticalmente ou horizontalmente a capacidade de taxa de transferência das tabelas de banco de dados sem tempo de inatividade. Você pode usar o Console de Gerenciamento da AWS para monitorar a utilização de recursos e as métricas de performance.