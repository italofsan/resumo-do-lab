# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Módulo 01
- Aprendi sobre como personalizar meu Azure e alguns dos serviços que tem disponíveis na plataforma.

- Aprendi sobre os benefícios da Nuvem:
  - Alta disponibilidade
  - Escalabilidade
  - Elasticidade
  - Confiabilidade
  - Previsibilidade
  - Segurança
  - Governança
  - Gerenciabilidade

- Aprendi sobre os tipos de serviço de nuvem:
  - Iaas -> Servidores, armazenamento, firewalls, segurança, planta física e edifício do datacenter;
  - Paas -> Sistemas operacionais, ferramentas para desenvolvedores;
  - Saas -> Aplicativos e apps hospedados.

- Aprendi sobre componentes de arquitetura do Azure:
  - Regiões
  - Zonas de disponibilidade
  - Pares de regiões
  - Regiões soberanas
   Grupos de gerenciamento -> Assinaturas -> Grupos de recursos -> Recursos

- Aprendi sobre computação e rede:
  - Máquinas Virtuais
  - Conjuntos de dimensionamento de VMs
  - Conjuntos de disponibilidade de VMs
    - Domínio de falha
    - Domínio de atualização
  - Área de trabalho virtual
  - Contêineres do Azure
  - Azure functions
  - Serviços de aplicativos do Azure
  - Serviços de rede do Azure
  - DNS do Azure

- Aprendi sobre armazenamento:
  - Redundância e serviços de armazenamento
    - LRS, ZRS, GRS, GZRS
    - Blob, Disco, Fila, Arquivos, Tabelas
  - Pontos de extremidades públicos
    - blob, dfs, file, queue, table
  - Camadas de acesso
    - Frequente
    - Esporádico
    - Frio
    - Arquivo Morto
  - Migrações
    - Azure Data Box -> 80Tb
    - Azcopy -> linha de comando
    - Gerenciamento de arquivos -> interface

- Aprendi sobre identidade, acesso e segurança
  - Microsoft Entra ID
    - Autenticação
    - Logon Único (SSO) -> Single Sign On
    - Gerenciamento de aplicativos
    - B2B
    - Gerenciamento de dispositivos
  - Autenticação
    - Identifica a pessoa
    - Solicita credenciais de acesso legítimo
  - Autorização
    - Nível de acesso
    - Quais dados podem acessar e o que pode fazer com eles
  - Acesso condicional -> Granularidade
    - Associação de usuário ou grupo
    - Local do IP
    - Dispositivo
    - Aplicativo
    - Detecção de risco
  - Controle de acesso baseado em função (RBAC)
  - Confiança Zero
    - Pressupõe que algo foi violado
    - Camadas de segurança

## Módulo 03
- Aprendi sobre gerenciamento de custos:
  - Fatores que afetam custos
    - Tipo de recurso
    - Consumo -> modelos (pay as you go | reserva)
    - Manutenção
    - Área geográfica
    - Tráfego de rede -> zonas de cobrança
    - Assinatura
  - Azure Marketplace
  - Calculadora de preços
  - Gerenciamento de custos
    - Orçamentos
    - Alertas
    - Recomendação
  - Marcas (Tags)

- Aprendi sobre governança e conformidade:
  - Azure Policy -> ajuda a impor padrões organizacionais | avalia e identifica
    -  Non-complaint
    -  Remediation
    -  Complaint
  - Bloqueios de recursos
  - Portal de Confiança do Serviço
  - Microsoft Purview

- Aprendi sobre Ferramentas de implantação de recursos:
  - Ferramentas
    - Portal do Azure
    - Azure Cloud Shell
    - Azure PowerShell
    - CLI
    - Azure ARC -> local, várias nuvens e borda
  - Azure Resource Manager (ARM)
  - Bicep
