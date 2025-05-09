# Estrutura e Organização do Microsoft Azure 

Este repositório foi criado como parte de um estudo prático para entender a organização, os recursos e a hierarquia de gerenciamento no Microsoft Azure, uma das principais plataformas de computação em nuvem.

## Tópicos explorados

O estudo abordou os seguintes conceitos:

- **Regiões, pares de regiões e regiões soberanas do Azure**:
  - Regiões são localizações geográficas com datacenters, como "East US" ou "South Brazil".
  - Pares de regiões, como "East US" e "West US", garantem redundância para recuperação de desastres.
  - Regiões soberanas atendem a requisitos de conformidade locais, como Azure Government para os EUA.
- **Zonas de disponibilidade e datacenters do Azure**:
  - Zonas de disponibilidade são áreas isoladas dentro de uma região, com energia e rede independentes.
  - Datacenters dentro dessas zonas hospedam os serviços, garantindo alta disponibilidade e tolerância a falhas.
- **Recursos e grupos de recursos do Azure**:
  - Recursos são instâncias específicas, como máquinas virtuais, bancos de dados ou redes.
  - Grupos de recursos organizam recursos relacionados, facilitando gerenciamento e aplicação de políticas.
- **Assinaturas e grupos de gerenciamento**:
  - Assinaturas definem o escopo de cobrança e acesso, permitindo controle de custos e permissões.
  - Grupos de gerenciamento organizam assinaturas em uma hierarquia para aplicar políticas em larga escala.
- **Hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento**:
  - Grupos de gerenciamento estão no topo, agrupando várias assinaturas.
  - Assinaturas contêm grupos de recursos, que, por sua vez, reúnem os recursos individuais.
