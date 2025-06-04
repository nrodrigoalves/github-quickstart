
# Repositório de Estudos: Gerenciamento de Máquinas Virtuais no Microsoft Azure

## 1. Introdução ao Azure e Máquinas Virtuais (VMs)
- Azure é uma plataforma de nuvem da Microsoft que oferece serviços como VMs, bancos de dados, redes e mais.
- Máquinas virtuais são recursos computacionais que permitem executar sistemas operacionais e aplicativos na nuvem.
- Principais vantagens: escalabilidade, alta disponibilidade, flexibilidade e pagamento conforme uso.

## 2. Conceitos Essenciais

### Conjuntos de Disponibilidade (Availability Sets)
- Agrupamento lógico que distribui VMs em domínios de falha e de atualização.
- Garante alta disponibilidade, minimizando riscos em falhas de hardware ou atualizações.

### Zonas de Disponibilidade (Availability Zones)
- Áreas fisicamente separadas dentro de uma região Azure.
- Protegem contra falhas de datacenter inteiro, aumentando a resiliência.

### Escalabilidade
- **Escalonamento vertical:** aumentar recursos (CPU, memória) de uma VM.
- **Escalonamento horizontal:** adicionar ou remover instâncias de VMs para lidar com a demanda.

### Conjuntos de Dimensionamento de Máquinas Virtuais (VM Scale Sets)
- Criam e gerenciam grupos de VMs idênticas com escalabilidade automática.
- Permitem balanceamento de carga e resposta dinâmica ao uso.

## 3. Gerenciamento de VMs no Azure

### Criação de VM
- Escolha da imagem (Windows, Linux)
- Definição do tamanho da VM (CPU, RAM)
- Configuração de rede e armazenamento

### Alta Disponibilidade
- Uso de Availability Sets ou Availability Zones
- Implementação de balanceadores de carga para distribuir tráfego

### Escala Automática (Auto-scaling)
- Configuração de regras baseadas em métricas (CPU, memória)
- Ajuste automático do número de VMs conforme a demanda

### Manutenção e Atualizações
- Manutenção planejada pode exigir realocação ou reinício das VMs
- Importância de acompanhar notificações da Microsoft e preparar o ambiente

## 4. Dicas e Boas Práticas
- Sempre configure conjuntos de disponibilidade para cargas críticas.
- Use VM Scale Sets para aplicativos que precisam escalar automaticamente.
- Monitore métricas para ajustar regras de auto-scaling corretamente.
- Teste atualizações e failover para garantir continuidade do serviço.
- Use tags para organizar recursos e facilitar o gerenciamento.

## 5. Recursos Úteis
- [Documentação oficial do Azure VMs](https://learn.microsoft.com/azure/virtual-machines/)
- [Guias rápidos e tutoriais do Azure](https://azure.microsoft.com/pt-br/resources/)
- [Azure CLI e PowerShell para gerenciamento de VMs](https://learn.microsoft.com/azure/virtual-machines/linux/cli-ps-get-started)
