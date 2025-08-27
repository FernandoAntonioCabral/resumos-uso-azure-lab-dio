# Resumos-uso-azure-lab-dio
**Repositório com resumos, anotações e dicas sobre o uso da Azure**

* **Computação em Nuvem**: é o fornecimento de recursos virtualizados via internet, como servidores, armazenamento, redes, etc. Eliminando a necessidade de infraestrutura local.
* **Modelos de Nuvem**:
  * **Pública**: Infraestrutura compartilhada, oferecida por provedores como AWS, Azure e Google Cloud, acessível a múltiplos clientes.
  * **Privada**: Infraestrutura dedicada a uma única organização que contém um maior controle e segurança. (fornecida pela própria organização).
  * **Híbrida**: Combinação de nuvem pública e privada, permitindo flexibilidade e aproveitamento do melhor dos dois mundos.

* **Modelo Baseado no Consumo**: Onde se paga somente pelo que é realmente usado (um software online 10 dias, será cobrado somente pelos 10 dias usados).

# Benefícios da Computação em Nuvem
* **Benefícios da alta disponibilidade e da escalabilidade na nuvem**:
  * A **Alta disponibilidade** que garante que os serviços e aplicações fiquem acessíveis praticamente sem interrupções.
  * A **Escalabilidade** que permite aumentar ou reduzir recursos conforme a demanda, tornando-o **elástico** se preciso.

* **Benefícios da confiabilidade e da previsibilidade na nuvem**:
  * A **Confiabilidade** que assegura que os serviços rodem de forma consistente, com redundância e mecanismos de recuperação. (associado a **resiliência** onde um sistema que se recupera falhas e continua funcionando).
  * A **Previsibilidade** que possibilita estimar custos e desempenho de maneira mais estável, permitindo que você avance com confiança.

* **Benefícios da segurança e da governança na nuvem**:
  * A **Segurança** que a nuvem oferece, são ferramentas que atendem às necessidades dos clientes. (mas o cliente tambem tem responsabilidades e entender como melhor utilizá-lo).
  * A **Governança** que ajuda a manter conformidade com normas e políticas, garantindo uso responsável e controlado dos recursos.

# Tipos de Serviços de nuvem na Azure
#### IaaS: São recursos, serviços aonde o cliente tem mais acesso (atualizações e monitoramento são responsabilidades do cliente).
#### PaaS: Oferece uma plataforma pronta para desenvolvimento e hospedagem de aplicações, incluindo banco de dados e ferramentas de desenvolvimento. O cliente só gerencia o código e os dados para entrada.
#### SaaS: Entrega aplicações prontas, sem necessidade de instalação ou gerenciamento de infraestrutura. O cliente apenas usa o serviço. (Ex. Microsoft 365).

## Modelo de responsabilidade compartilhada
* **Define quem é responsável pela segurança e gerenciamento de cada camada:**
  * **Provedor de nuvem**: cuida da infraestrutura física e, dependendo do modelo, do sistema operacional e da plataforma.
  * **Cliente**: é responsável pelos dados, acessos, configurações.

## Casos de uso
* **IaaS**: Ideal para empresas que precisam de flexibilidade total na infraestrutura.
* **PaaS**: Focado no desenvolvimento de aplicativos, banco de dados. O gerenciamento de plataforma é realizado pelo provedor de nuvem.
* **SaaS**: Modelo de preço de pagamento conforme o uso. (licenciamento).
