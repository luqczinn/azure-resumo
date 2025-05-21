# Resumo do Lab - Máquinas Virtuais e Áreas de Trabalho Virtuais no Azure

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, focado na criação e gerenciamento de máquinas virtuais (VMs) e áreas de trabalho virtuais (WVD) na plataforma Microsoft Azure.

## ✅ O que aprendi

### 1. **Criação de Máquinas Virtuais no Azure**
- Compreendi os principais componentes de uma VM no Azure: imagem do sistema operacional, tamanho da VM (SKU), disco de armazenamento, rede virtual (VNet) e grupo de recursos.
- Aprendi a configurar VMs pelo portal do Azure, definindo parâmetros como:
  - Nome da máquina
  - Região de implantação
  - Usuário administrador
  - Tipo de autenticação (senha ou chave SSH)
- Experimentei a conexão remota à VM via RDP (Remote Desktop Protocol).

### 2. **Configuração de Rede Virtual**
- Aprendi a importância da VNet e da criação de **sub-redes** para isolar recursos.
- Entendi o papel dos **grupos de segurança de rede (NSG)** para controlar o tráfego de entrada e saída.

### 3. **Implantação de Área de Trabalho Virtual (WVD - Windows Virtual Desktop)**
- Entendi como o Azure Virtual Desktop (AVD) permite oferecer um ambiente de trabalho completo baseado em nuvem.
- Aprendi a:
  - Criar um **host pool** com múltiplas VMs.
  - Configurar um **workspace** para os usuários acessarem as áreas de trabalho virtuais.
  - Atribuir usuários para acessarem os desktops virtuais.

### 4. **Boas Práticas e Segurança**
- Utilização do conceito de **defesa em profundidade** para proteger o ambiente.
- Importância do uso de autenticação multifator (MFA) e monitoramento de atividades.
- Comparação entre VMs e contêineres, entendendo suas diferenças de isolamento e uso.


