# Otimizando Custos no Azure

O Microsoft Azure oferece diversos serviços que variam em preço conforme o uso e a configuração. Para garantir que os recursos sejam bem aproveitados, é crucial implementar estratégias de otimização de custos.

## Principais Práticas:

  - Dimensionamento Correto dos Recursos (Right-sizing) - Analise o uso de máquinas virtuais, bancos de dados e outros serviços para garantir que não estão superdimensionados. Ajuste os tamanhos das instâncias com base na demanda real.
  - Reservas de Instâncias - Utilize instâncias reservadas (Reserved Instances) para obter descontos significativos em máquinas virtuais e outros serviços. Isso é ideal para cargas de trabalho previsíveis e de longo prazo.
  - Uso de Spot Instances - Spot VMs oferecem capacidade a preços reduzidos para workloads que podem ser interrompidas. Isso é especialmente útil para tarefas temporárias ou processos em lote.
  - Autoescalonamento - Configure autoescalonamento em recursos como VMs e clusters Kubernetes para aumentar ou diminuir automaticamente os recursos com base na demanda.
  - Desligamento de Recursos Ociosos - Automatize o desligamento de máquinas virtuais ou outros recursos que não estejam sendo utilizados fora do horário de trabalho ou durante fins de semana.
  - Uso de Containers -Considere a migração de cargas de trabalho para contêineres, que podem ser executados de maneira mais eficiente em termos de custo em plataformas como o Azure Kubernetes Service (AKS).

## Previsão e Monitoramento:

Use ferramentas como a Calculadora de Preços do Azure e a Calculadora de Custo Total de Propriedade (TCO) para estimar os custos de seus próximos projetos do Azure.



## Ferramentas de Monitoramento de Custos

  - Azure Cost Management + Billing - Permite monitorar e controlar os gastos no Azure. Com ela, é possível visualizar tendências de custos, configurar alertas e criar relatórios detalhados.
  - Azure Advisor - O Azure Advisor fornece recomendações personalizadas para ajudar a otimizar os recursos em termos de performance, segurança e custos.
  - Azure Pricing Calculator - Para estimar os custos de novos recursos antes de implementá-los e garantir que estejam dentro do orçamento planejado.
    ![image](https://github.com/user-attachments/assets/868aa64d-e17f-4873-8c64-cc41ed7cfb04)
    
  - Azure Budgets - Configure orçamentos mensais para diferentes serviços ou assinaturas, com alertas quando o gasto estiver próximo de atingir o limite definido.

## Links Úteis e Recursos
https://azure.microsoft.com/pt-br/pricing/
https://azure.microsoft.com/pt-br/services/cost-management/
https://azure.microsoft.com/pt-br/services/advisor/
https://azure.microsoft.com/pt-br/pricing/calculator/
