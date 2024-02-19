# AWS - Cloud Practitioner

## O que é Cloud Computing?

A computação em nuvem é a entrega de recursos de TI sob demanda por meio da Internet com definição de preço de pagamento conforme o uso. Em vez de comprar, ter e manter datacenters e servidores físicos, você pode acessar serviços de tecnologia, como capacidade computacional, armazenamento e bancos de dados, conforme a necessidade, usando um provedor de nuvem como a Amazon Web Services (AWS).

## Vantagens da Cloud Computing

1. custo reduzido;
2. escala global (implementar serviços verticalmente e globalmente);
3. performance;
4. velocidade e agilidade;
5. produtividade;
6. segurança;
7. flexibilidade/home-office.

## Tipos de Cloud

IAAS - Servidores; VM; Storage

PAAS - Hospedagem; SO; DB

SAAS - App

# IAM - Identity and Access Management

Gerenciar acesso aos recursos da AWS

organizar os usuários que tem ou não acesso a conta da AWS.

# Infraestrutura

## AZs e SLA

As Zonas de Disponibilidade (Availability Zones - AZs) da AWS são data centers fisicamente separados que são projetados para serem independentes uns dos outros. Cada AZ tem sua própria infraestrutura de rede, energia e resfriamento, e é isolada de outras AZs para garantir a alta disponibilidade e resiliência de aplicativos e serviços implantados na nuvem da AWS.

O Service Level Agreement (SLA) da AWS para as Zonas de Disponibilidade é de 99,99% de disponibilidade em cada região da AWS. Isso significa que a AWS se compromete a manter cada AZ de uma região disponível e operacional 99,99% do tempo em um ciclo de cobrança mensal. Se a disponibilidade de uma AZ for inferior a 99,99%, a AWS pode oferecer créditos de serviço aos clientes afetados.

O SLA da AWS para as AZs é projetado para garantir a continuidade dos negócios e minimizar o impacto de interrupções no serviço. Os clientes podem usar várias estratégias de implantação, como o balanceamento de carga entre as AZs, para aumentar ainda mais a disponibilidade e resiliência de seus aplicativos e serviços na nuvem da AWS.

Em resumo, as Zonas de Disponibilidade da AWS são projetadas para garantir alta disponibilidade e resiliência de aplicativos e serviços na nuvem da AWS, e a AWS oferece um SLA de 99,99% de disponibilidade para cada AZ em uma região da AWS.

## Private Cloud

Private Cloud na AWS refere-se a um ambiente de computação em nuvem configurado para atender exclusivamente as necessidades de uma única organização ou empresa. Diferentemente do modelo de nuvem pública, onde vários usuários compartilham recursos, a nuvem privada é dedicada a uma organização específica e geralmente é implantada em uma infraestrutura de data center privado.

Na AWS, é possível criar uma nuvem privada utilizando as ferramentas de virtualização como o VMware ou o Hyper-V, por exemplo. Com essas ferramentas, é possível criar máquinas virtuais (VMs) e implantá-las em uma nuvem privada. Além disso, é possível configurar recursos de rede e armazenamento para a nuvem privada.

A AWS oferece diversas soluções de nuvem privada, incluindo o Amazon VPC (Virtual Private Cloud), que permite criar uma nuvem privada na AWS isolada da Internet pública, e o AWS Outposts, que permite a criação de uma nuvem privada dentro do data center da própria organização, fornecendo recursos de computação e armazenamento em nuvem de alta qualidade.

A utilização de uma nuvem privada pode trazer benefícios como maior controle sobre a infraestrutura, personalização e segurança. No entanto, é importante lembrar que o custo de implantação e manutenção de uma nuvem privada pode ser elevado

## Backbone

AWS Backbone é a infraestrutura de rede global da Amazon Web Services (AWS) que interliga todos os seus serviços e regiões. Essa rede é composta por uma série de pontos de presença (PoPs) distribuídos em todo o mundo, conectados por uma rede de fibra óptica privada e de alta velocidade.

A AWS Backbone fornece um alto nível de disponibilidade, escalabilidade e desempenho para todos os serviços da AWS. Com essa infraestrutura, a AWS é capaz de oferecer serviços com baixa latência e alta velocidade de transferência de dados em todo o mundo.

Além disso, a AWS Backbone é responsável por fornecer segurança para os serviços da AWS. A rede é projetada para oferecer proteção contra ataques DDoS e outras ameaças à segurança.

A infraestrutura de rede da AWS também oferece suporte a recursos como o Amazon CloudFront, que é uma rede de entrega de conteúdo (CDN) global, permitindo que os clientes entreguem conteúdo rapidamente para seus usuários finais, independentemente de onde eles estejam localizados.

Em resumo, a AWS Backbone é uma infraestrutura de rede global de alta velocidade e segurança que interliga todos os serviços e regiões da AWS. Ela oferece suporte a uma ampla variedade de recursos e serviços, permitindo que as empresas possam executar suas operações de TI em uma escala global.

## Edge Locations

AWS Edge Locations são pontos de presença (POPs) distribuídos globalmente, localizados em cidades estratégicas ao redor do mundo, que fazem parte da infraestrutura da AWS. Essas localidades servem como uma camada intermediária entre os usuários finais e os serviços da AWS, permitindo a entrega de conteúdo de forma mais rápida e eficiente.

Quando um usuário solicita um conteúdo (como um vídeo ou uma imagem) a partir de um servidor da AWS, o conteúdo pode ser armazenado em cache em um Edge Location próximo ao usuário, o que acelera o tempo de resposta e melhora a experiência do usuário final.

Além disso, os Edge Locations também são usados para serviços como Amazon CloudFront, Amazon Route 53 e AWS Global Accelerator, permitindo a entrega de conteúdo de forma global, escalável e segura. Em resumo, os Edge Locations da AWS são essenciais para melhorar a performance e a disponibilidade dos serviços em nuvem da AWS em todo o mundo.

## PoP

Em termos de AWS, PoP significa Point of Presence, que se refere a um local físico onde a AWS possui equipamentos de rede e infraestrutura para fornecer serviços de nuvem aos seus clientes.

A AWS possui PoPs em diversas localidades ao redor do mundo, incluindo América do Norte, Europa, Ásia, Austrália, América Latina, Oriente Médio e África. Esses PoPs são essenciais para permitir que os clientes da AWS acessem os serviços em suas regiões geográficas com baixa latência e alta disponibilidade.

Os PoPs da AWS geralmente incluem servidores, roteadores e outros equipamentos de rede que gerenciam o tráfego de dados e garantem que os serviços da AWS estejam disponíveis e funcionando adequadamente para os usuários finais. Além disso, os PoPs podem incluir recursos de cache, como o Amazon CloudFront, que armazena em cache conteúdo web e distribui esse conteúdo a partir do local mais próximo ao usuário final, reduzindo a latência e melhorando o desempenho.

Em resumo, os PoPs são pontos de presença física da AWS que fornecem recursos de infraestrutura de rede e computação, permitindo que os clientes da AWS acessem os serviços em suas regiões com baixa latência e alta disponibilidade.

## IaaS

AWS IaaS (Infrastructure as a Service) é um modelo de serviço em nuvem da AWS que oferece recursos de infraestrutura, como servidores virtuais, armazenamento, redes, entre outros, como um serviço sob demanda. Com a AWS IaaS, os usuários podem configurar e gerenciar seus próprios recursos de infraestrutura de forma rápida e escalável, sem precisar investir em hardware ou manutenção. A AWS IaaS oferece uma ampla gama de serviços, incluindo EC2 (Elastic Compute Cloud), EBS (Elastic Block Store), VPC (Virtual Private Cloud), Route 53 (serviço de DNS gerenciado), entre outros. Com o modelo IaaS, os usuários têm controle total sobre o ambiente de infraestrutura, desde a escolha do sistema operacional até as configurações de rede e segurança. Isso permite que as empresas adaptem seus ambientes de infraestrutura de acordo com suas necessidades específicas, aumentando a flexibilidade e reduzindo os custos operacionais.

## PaaS

AWS PaaS (Platform as a Service) é um modelo de serviço de nuvem em que a plataforma de desenvolvimento e implantação é fornecida como um serviço gerenciado na nuvem. Isso significa que os desenvolvedores podem criar, implantar e executar aplicativos em uma infraestrutura gerenciada pelo provedor de serviços em nuvem, sem ter que gerenciar o hardware ou o software subjacente.

A AWS oferece diversos serviços de PaaS, como o AWS Elastic Beanstalk, que permite implantar e gerenciar aplicativos na nuvem de maneira fácil e rápida, sem se preocupar com a infraestrutura subjacente. Outros exemplos incluem o AWS Lambda, que permite executar códigos sem servidor, o AWS App Runner, que automatiza o processo de criação, implantação e execução de aplicativos em contêineres, e o AWS Amplify, que oferece uma plataforma de desenvolvimento completa para criar aplicativos móveis e da web.

Em resumo, o AWS PaaS é uma abordagem que oferece às empresas uma maneira mais rápida e eficiente de desenvolver, implantar e gerenciar aplicativos em nuvem, sem ter que se preocupar com a infraestrutura subjacente. Isso permite que as empresas se concentrem mais em inovar e desenvolver novos recursos para seus aplicativos, em vez de se preocupar com a manutenção da infraestrutura.

## SaaS

AWS SaaS (Software as a Service) é um modelo de negócio em que uma empresa oferece seus aplicativos e serviços hospedados na nuvem como um serviço para seus clientes. Com o AWS SaaS, os desenvolvedores e empresas podem criar, implantar e gerenciar seus aplicativos de forma rápida e escalável na infraestrutura da AWS, sem precisar se preocupar com a complexidade da gestão de infraestrutura e da escalabilidade de recursos.

Os clientes podem acessar esses aplicativos e serviços por meio de um navegador web ou de aplicativos específicos, geralmente pagando por uma assinatura mensal ou anual. Alguns exemplos de SaaS populares na AWS são o Salesforce, Microsoft Office 365, Dropbox e Slack.

Em resumo, o AWS SaaS é um modelo de negócio que permite às empresas oferecer seus aplicativos e serviços na nuvem de forma escalável, eficiente e rentável, tornando mais fácil para os clientes utilizá-los sem se preocupar com a infraestrutura por trás.

# Armazenamento

## Object Storage Service (OSS)

Object Storage Service (OSS) é um serviço de armazenamento de objetos oferecido pela Alibaba Cloud. O OSS permite que os usuários armazenem e gerenciem grandes quantidades de dados não estruturados, como imagens, vídeos, arquivos de áudio e outros tipos de conteúdo digital.

O OSS é altamente escalável e pode ser usado para armazenar quantidades ilimitadas de dados com segurança, durabilidade e alta disponibilidade. Ele é projetado para ser altamente durável e tolerante a falhas, com várias cópias de dados armazenados em diferentes locais geográficos para garantir a disponibilidade e a integridade dos dados.

Além disso, o OSS é altamente flexível e oferece recursos avançados, como armazenamento em camadas, compartilhamento de arquivos, criptografia de dados, controle de acesso e muito mais. O OSS é altamente compatível com outras soluções de computação em nuvem da Alibaba Cloud, como o Elastic Compute Service (ECS), Container Service, e funções de servidores.

O OSS pode ser usado para uma ampla gama de aplicativos, desde a hospedagem de sites estáticos até a transmissão de conteúdo de vídeo em larga escala. Ele é usado por empresas de todos os tamanhos e em todos os setores para armazenar e gerenciar grandes quantidades de dados não estruturados.

## S3

O Amazon S3 (Simple Storage Service) é um serviço de armazenamento de objetos na nuvem - AWS. Armazena e recupera grandes quantidades de dados de forma segura e escalável, utilizando uma interface web simples.

O S3 armazena dados como objetos, que podem ser arquivos de qualquer tipo ou tamanho. Esses objetos são armazenados em "buckets", que são como contêineres virtuais que podem ser acessados pela internet. Os buckets podem ser criados e gerenciados pelo usuário, e podem ser configurados para permitir acesso público ou privado.

O S3 oferece várias opções de armazenamento (S3 Standard, S3 Intelligent-Tiering, S3 Standard-Infrequent Access (S3 Standard-IA), S3 One Zone-Infrequent Access (S3 One Zone-IA), S3 Glacier, S3 Glacier Deep Archive, S3 Outposts.

O S3 também oferece recursos de segurança avançados, como criptografia de dados (SSE-S3, SSE-KMS, SSE-C), autenticação de usuários e controle de acesso (POLÍTICAS S3).

O S3 é amplamente utilizado para armazenar e distribuir conteúdo estático em sites e aplicativos, fazer backup e arquivamento de dados, e também para análise de big data e machine learning.

### Processos internos

Os processos internos do Amazon S3 são gerenciados pela infraestrutura da AWS e são automatizados para garantir disponibilidade e durabilidade dos dados armazenados.

Quando um usuário envia um objeto para o S3, o serviço automaticamente o divide em partes menores, chamadas de blocos, e os distribui em vários servidores em diferentes data centers da AWS. Essa técnica de distribuição de dados é conhecida como "sharding". Cada bloco é armazenado em pelo menos três servidores diferentes para garantir a durabilidade dos dados.

Os objetos no S3 são identificados por uma chave única, que é usada para recuperar o objeto posteriormente. O S3 utiliza o conceito de "consistência eventual" para garantir que os objetos estejam sempre disponíveis para leitura, mesmo que tenham sido atualizados recentemente. Isso significa que, após uma atualização, pode haver um pequeno atraso antes que todas as cópias do objeto estejam em sincronia.

O S3 também utiliza a replicação automática para fazer cópias dos dados em diferentes regiões da AWS para garantir a disponibilidade em caso de falhas em um data center ou região. Além disso, o S3 oferece opções de backup e recuperação de desastres, como a criação de snapshots e a replicação de dados para a AWS Glacier.

Em resumo, os processos internos do Amazon S3 são altamente automatizados e projetados para garantir alta disponibilidade, durabilidade e segurança dos dados armazenados, utilizando técnicas como sharding, replicação e consistência eventual.

### Políticas

As políticas do Amazon S3 são usadas para controlar o acesso aos buckets e objetos armazenados no serviço. As políticas são definidas em formato JSON e podem ser aplicadas em vários níveis, desde o nível de conta da AWS até o nível de objeto específico.

As políticas do S3 podem ser usadas para permitir ou negar o acesso a um bucket ou objeto para um ou mais usuários, grupos ou papéis da AWS. Isso inclui a definição de permissões de leitura, gravação e exclusão, bem como a restrição de acesso com base no endereço IP do solicitante.

Além disso, as políticas do S3 podem ser usadas para definir regras de versionamento, criptografia, arquivamento e retenção de objetos. Por exemplo, uma política pode ser usada para especificar que todos os objetos em um bucket devem ser criptografados usando um determinado algoritmo ou chave.

As políticas do S3 são altamente flexíveis e podem ser definidas e gerenciadas por meio do console da AWS, da API ou da linha de comando. A AWS também fornece um conjunto de políticas de exemplo que podem ser usadas como ponto de partida para criar políticas personalizadas.

Em resumo, as políticas do Amazon S3 são usadas para controlar o acesso e definir várias configurações de segurança e gerenciamento de objetos. Elas permitem aos usuários controlar rigorosamente quem pode acessar seus dados armazenados no S3 e como eles podem interagir com esses objetos.

### Encriptação

### SSE-S3

SSE-S3 (Server-Side Encryption with Amazon S3) é um recurso do Amazon S3 que oferece criptografia automática de dados em repouso nos objetos armazenados no S3.

Ao habilitar a criptografia SSE-S3 em um bucket ou objeto específico, o S3 automaticamente criptografa os dados usando chaves gerenciadas pela AWS antes de serem armazenadas. Isso ajuda a proteger os dados contra acesso não autorizado e garante que os dados permaneçam criptografados enquanto estiverem armazenados no S3.

O SSE-S3 é uma opção de criptografia de dados em repouso no S3 e é uma das várias opções de criptografia disponíveis no serviço, incluindo o SSE-KMS (Server-Side Encryption with AWS KMS) e o SSE-C (Server-Side Encryption with Customer-Provided Keys).

### SSE-KMS

SSE-KMS (Server-Side Encryption with AWS Key Management Service) é um recurso do Amazon S3 que oferece criptografia de dados em repouso nos objetos armazenados no S3 usando chaves de criptografia gerenciadas pelo serviço AWS KMS (Key Management Service).

Ao habilitar a criptografia SSE-KMS em um bucket ou objeto específico, o S3 criptografa automaticamente os dados usando uma chave de criptografia gerenciada pelo AWS KMS antes de serem armazenados. Isso ajuda a proteger os dados contra acesso não autorizado e garante que os dados permaneçam criptografados enquanto estiverem armazenados no S3.

O AWS KMS permite que as empresas gerenciem suas próprias chaves de criptografia mestra, que são usadas para criptografar as chaves de criptografia de dados usadas pelo S3. Com isso, as empresas podem controlar o acesso às suas chaves e garantir a conformidade com requisitos de conformidade e regulamentações.

### SSE-C

SSE-C (Server-Side Encryption with Customer-Provided Keys) é um recurso do Amazon S3 que permite aos clientes criptografar objetos no S3 usando suas próprias chaves de criptografia.

Ao habilitar a criptografia SSE-C em um bucket ou objeto específico, o cliente fornece sua própria chave de criptografia, que é usada pelo S3 para criptografar os dados antes de serem armazenados. Isso ajuda a proteger os dados contra acesso não autorizado e garante que os dados permaneçam criptografados enquanto estiverem armazenados no S3.

A criptografia SSE-C é diferente da criptografia SSE-S3 e SSE-KMS, que usam chaves gerenciadas pela AWS para criptografar os dados. Com a criptografia SSE-C, o cliente é responsável por gerar, gerenciar e proteger suas próprias chaves de criptografia.

Ao usar a criptografia SSE-C, o cliente tem controle total sobre suas chaves de criptografia e pode manter a conformidade com requisitos de conformidade e regulamentações, como a Lei Geral de Proteção de Dados (LGPD) ou a Lei Geral de Proteção de Dados Pessoais (LGPD).

| Recurso | SSE-S3 | SSE-KMS | SSE-C |
| --- | --- | --- | --- |
| Chave de criptografia gerenciada pelo cliente | Não | Sim | Sim |
| Tipo de chave de criptografia | Chave de criptografia AES-256 | Chave de criptografia AES-256 gerenciada pelo AWS Key Management Service (KMS) | Chave de criptografia AES-256 gerenciada pelo cliente |
| Gerenciamento de chave de criptografia | AWS gerencia a chave de criptografia | Cliente ou AWS gerencia a chave de criptografia | Cliente gerencia a chave de criptografia |
| Preços | Sem custo adicional | Custo adicional baseado no uso do AWS KMS e das operações de chave | Sem custo adicional |

### Configurações

O Amazon S3 oferece uma ampla gama de configurações para personalizar a funcionalidade e o comportamento do serviço. Algumas das configurações mais importantes incluem:

1. Gerenciamento de acesso: o S3 permite controlar o acesso aos buckets e objetos armazenados usando políticas de acesso, permissões de usuários, grupos e papéis do IAM.
2. Criptografia: o S3 oferece várias opções de criptografia, incluindo o SSE-S3, SSE-KMS e SSE-C, que permitem criptografar objetos armazenados no bucket.
3. Versionamento: o versionamento do S3 permite rastrear as alterações em um objeto e recuperar versões anteriores, se necessário. Isso é útil para proteger os dados contra exclusões acidentais ou maliciosas.
4. Lifecycle: as configurações de ciclo de vida permitem que os objetos sejam movidos automaticamente para classes de armazenamento de custo mais baixo ou excluídos após um determinado período de tempo.
5. Logging: o S3 pode registrar atividades de acesso em logs, o que é útil para fins de auditoria e conformidade.
6. Transferência de dados: o S3 permite configurar a transferência de dados em massa para importar ou exportar grandes quantidades de dados de e para o S3.
7. Integrações com outros serviços: o S3 pode ser integrado com outros serviços da AWS, como o AWS Lambda, para processar objetos armazenados no S3.
8. Gerenciamento de versão do bucket: permite habilitar o versionamento do bucket para rastrear as alterações feitas em todos os objetos armazenados no bucket.
9. Política de ciclo de vida: permite criar regras de ciclo de vida que definem quando objetos podem ser movidos para outras classes de armazenamento, excluídos ou arquivados.
10. Controle de acesso baseado em objeto: permite criar políticas de controle de acesso baseadas em objeto para controlar o acesso a objetos específicos em um bucket.
11. Cross-Region Replication (CRR): permite replicar automaticamente objetos entre buckets em diferentes regiões do S3 para proteger contra interrupções de serviços.
12. Transfer Acceleration: permite acelerar a transferência de dados de e para o S3 usando uma rede de entrega de conteúdo (CDN) global.
13. Configurações de segurança: incluem a capacidade de configurar políticas de segurança avançadas para proteger os dados armazenados no S3, como políticas de segurança de rede, autenticação de usuário e criptografia de chave de cliente.

### Wide Range Storage Classes

O Amazon S3 oferece uma ampla gama de classes de armazenamento para atender às necessidades de diferentes casos de uso e requisitos de custo e desempenho. Algumas das classes de armazenamento disponíveis no Amazon S3 incluem:

1. S3 Standard: projetado para armazenamento de dados frequente e acesso imediato.
2. S3 Intelligent-Tiering: projetado para otimizar os custos de armazenamento movendo automaticamente os dados entre duas camadas de acesso com base em padrões de uso.
3. S3 Standard-Infrequent Access (S3 Standard-IA): projetado para armazenamento de dados que não são acessados com frequência, mas exigem acesso rápido quando necessário.
4. S3 One Zone-Infrequent Access (S3 One Zone-IA): projetado para armazenamento de dados que podem ser reproduzidos em uma única zona de disponibilidade.
5. S3 Glacier: projetado para arquivamento de dados de longo prazo com acesso em horas.
6. S3 Glacier Deep Archive: projetado para arquivamento de dados de longo prazo com acesso em horas.
7. S3 Outposts: projetado para armazenamento de dados local em racks de servidores em instalações de clientes.

### Bucket

Um bucket é um contêiner virtual que pode ser usado para armazenar dados no serviço de armazenamento em nuvem da AWS, o Amazon S3. O bucket é uma espécie de diretório que pode conter vários objetos, como arquivos de texto, imagens, vídeos, arquivos de áudio e outros tipos de dados.

Os buckets são usados para organizar e gerenciar os objetos no S3. Cada bucket tem um nome único globalmente, que é usado para identificar o bucket na URL de acesso do objeto. Os buckets também podem ser criados em qualquer região da AWS e podem ser configurados para permitir ou negar o acesso público.

Os objetos em um bucket são armazenados e replicados em diferentes servidores em vários data centers da AWS, garantindo alta disponibilidade e durabilidade dos dados. Além disso, o S3 oferece recursos de segurança avançados, como a criptografia de dados em repouso e em trânsito, controle de acesso e monitoramento de acesso a objetos.

Os buckets do S3 são amplamente utilizados para armazenamento e distribuição de conteúdo estático em sites e aplicativos, backup e arquivamento de dados, análise de big data e machine learning, entre outros usos.

Em resumo, um bucket na AWS é um contêiner virtual que é usado para armazenar e organizar objetos no serviço de armazenamento em nuvem da AWS, o Amazon S3. Cada bucket tem um nome único globalmente e pode ser configurado com opções de segurança avançadas.

### Key

No contexto da AWS, "key" em um bucket se refere a um identificador único para um objeto armazenado em um bucket S3. A chave é composta por um nome e um caminho que especifica a localização do objeto dentro do bucket. A chave é usada para identificar e acessar objetos em um bucket S3, e ela é usada como parte da URL que os usuários usam para acessar o objeto na web. A chave é importante para a organização e gerenciamento de objetos em um bucket S3, e deve ser escolhida cuidadosamente para evitar conflitos ou problemas de desempenho.

### Policy

A política de bucket (bucket policy) é um recurso do Amazon S3 que permite aos usuários especificar permissões de acesso a um bucket e aos objetos armazenados nele. Essa política é escrita em formato JSON e pode ser usada para conceder ou negar permissões de acesso a usuários, grupos de usuários ou a serviços da AWS.

A política de bucket é útil para gerenciar o acesso a objetos em um bucket S3, permitindo que os usuários controlem quem pode acessar o bucket e como o acesso pode ser feito. Por exemplo, a política de bucket pode ser usada para conceder permissões de leitura ou gravação a um usuário específico ou a um grupo de usuários, ou para restringir o acesso a um intervalo de endereços IP específicos.

Ao criar uma política de bucket, é importante entender os princípios básicos de segurança da AWS, como o controle de acesso baseado em função (RBAC) e o modelo de segurança de responsabilidade compartilhada. Além disso, é recomendável testar e revisar regularmente a política de bucket para garantir que ela esteja funcionando corretamente e cumprindo as necessidades de segurança e conformidade da organização.

### Objetos

Objetos são as entidades fundamentais armazenadas no Amazon S3. É necessário conceder explicitamente permissões a outras pessoas para acessar seus objetos. Cada objeto possui dados, uma chave e metadados. A chave do objeto (ou nome da chave) identifica exclusivamente o objeto em um bucket.

O Amazon S3 mantém um conjunto de metadados do sistema e do usuário para cada objeto e processa os metadados do sistema conforme necessário para o gerenciamento de armazenamento.

O Amazon S3 tem uma estrutura plana em vez de uma hierarquia como você pode ver em um sistema de arquivos. No entanto, o console suporta o conceito de pasta como um meio de agrupar objetos, usando um prefixo de nome compartilhado para objetos na mesma pasta.

Use esta página para ver todos os objetos em um bucket ou pasta, criar uma pasta ou fazer o upload de um objeto. Você pode abrir, baixar, excluir e copiar a URL de objetos selecionados. Você também pode realizar ações de objeto como calcular tamanho, copiar, restaurar, editar e consultar com S3 Select.

### Propriedades

Na guia Propriedades do bucket, você pode editar as configurações do bucket para atender ao seu caso de uso.

Proteja seu armazenamento

Para salvar várias cópias distintas de seus dados e recuperar facilmente tanto de ações de usuário não intencionais quanto de falhas de aplicativo, habilite a Versioning do Amazon S3. A Versioning do S3 é necessária para habilitar outras opções de proteção de dados para o Amazon S3, incluindo o Object Lock do S3 e a Replicação do S3.

Proteja seu armazenamento

Para criptografar automaticamente e proteger ainda mais os novos objetos que são adicionados ao seu bucket, habilite a criptografia padrão com chaves gerenciadas pelo Amazon S3 ou chaves do AWS Key Management Service.

Arquive objetos raramente acessados

Para objetos que são raramente acessados por longos períodos de tempo, crie uma configuração de Arquivo do S3 Intelligent-Tiering que ativa um ou ambos os níveis de acesso de arquivo do S3 Intelligent-Tiering. Depois de ativar um ou ambos os níveis de acesso de arquivo, o S3 Intelligent-Tiering move automaticamente os objetos com base em quão frequentemente eles são acessados. Objetos que não foram acessados por 90 dias consecutivos são movidos para o nível de Acesso do Arquivo. Objetos que não foram acessados por 180 dias consecutivos são movidos para o nível de Acesso do Arquivo Profundo.

### Monitore o Acesso ao Bucket e Eventos

Configure ferramentas de registro para monitorar e controlar como seus recursos S3 estão sendo usados. Para obter registros detalhados das solicitações feitas ao seu bucket, habilite o registro de acesso do servidor. Para registrar as ações tomadas por um usuário, uma função ou em seu bucket do S3, configure eventos de dados do AWS CloudTrail no console do CloudTrail. Para iniciar fluxos de trabalho que usam o Amazon Simple Notification Service (Amazon SNS), o Amazon Simple Queue Service (Amazon SQS) e o AWS Lambda quando ocorre uma alteração em seus recursos do S3, crie uma notificação de evento.

Para obter informações adicionais sobre o uso do seu bucket, recomendamos que você vá para a página S3 Storage Lens e configure um painel e habilite métricas gratuitas. Depois de fazer isso, você pode visualizar seu painel padrão a partir da página da lista de Buckets.

Atenda aos requisitos de conformidade

Com o Object Lock do S3, você pode armazenar objetos no Amazon S3 usando um modelo de gravação uma vez e leitura muitas vezes (WORM). Para atender aos requisitos de retenção de conformidade de dados, você pode usar o Object Lock para impedir que um objeto seja excluído ou sobrescrito por um tempo fixo ou indefinidamente. Você pode configurar o Object Lock para se aplicar a todos os objetos no bucket ou apenas a certos objetos.

Explore outras opções

Use o seu bucket do S3 para hospedar um site estático. Habilite a Transferência Acelerada para transferências de arquivos rápidas e seguras em longas distâncias. Habilite o Pagador de Solicitação para compartilhar dados sem incorrer em cobranças associadas a outros acessando os dados.

## EBS

Amazon Elastic Block Store (EBS) é um serviço de armazenamento de blocos de alta performance para uso com instâncias do Amazon Elastic Compute Cloud (EC2). Ele fornece volumes de armazenamento persistente que podem ser anexados a uma instância do EC2 e usados como um disco rígido padrão.

O Amazon EBS oferece vários tipos de volumes de armazenamento, incluindo:

SSDs provisionados (gp2): projetado para cargas de trabalho que exigem um desempenho consistente de IOPS (operações de entrada/saída por segundo) com baixa latência.

Throughput otimizado HDDs (st1): projetado para cargas de trabalho que exigem alto throughput de leitura/gravação e acesso frequente a grandes conjuntos de dados.

HDDs de capacidade (sc1): projetado para cargas de trabalho que exigem alto throughput de leitura/gravação e acesso a grandes volumes de dados, com requisitos de custo mais baixos.

Cold HDDs (sc1): projetado para cargas de trabalho que exigem acesso a dados menos frequentes, com requisitos de custo mais baixos.

O Amazon EBS permite criar e modificar volumes de armazenamento, anexá-los a instâncias do EC2 e fazer backups e snapshots para proteger os dados armazenados. Ele também oferece recursos de criptografia de dados em repouso e replicação de volumes para garantir a disponibilidade contínua dos dados armazenados.

Em resumo, o Amazon Elastic Block Store é um serviço de armazenamento de blocos altamente escalável e confiável que ajuda a fornecer armazenamento persistente para as instâncias do EC2 da AWS.

Os EBS Elastic Volumes são uma funcionalidade adicional do serviço EBS que permite alterar o tamanho e o tipo de volume sem interromper a instância EC2. Com os EBS Elastic Volumes, é possível aumentar ou diminuir o tamanho do volume e alterar o tipo de armazenamento (por exemplo, de SSD para HDD) sem precisar parar a instância EC2 ou fazer backup e restauração dos dados. Isso proporciona maior flexibilidade e facilidade na gestão de armazenamento, permitindo que os usuários ajustem rapidamente a capacidade e o desempenho do armazenamento para atender às necessidades de suas aplicações.

### Benefícios

O Amazon Elastic Block Store (EBS) oferece uma variedade de benefícios para usuários que precisam de armazenamento em bloco confiável e escalável em nuvem. Aqui estão alguns dos benefícios mais importantes do Amazon EBS:

1. Disponibilidade: O EBS oferece alta disponibilidade e durabilidade para seus volumes de armazenamento em bloco. Os dados são replicados automaticamente em várias zonas de disponibilidade para ajudar a evitar a perda de dados e interrupções de serviços.
2. Escalabilidade: O EBS é altamente escalável e pode ser facilmente dimensionado verticalmente ou horizontalmente para atender às necessidades em constante evolução de seus aplicativos. Você pode adicionar, expandir e excluir volumes sem interromper suas instâncias EC2.
3. Desempenho: O EBS fornece volumes de armazenamento de alto desempenho com diferentes tipos de volume, incluindo SSD, HDD e provisioned IOPS, permitindo que você selecione o tipo de volume mais adequado para suas cargas de trabalho.
4. Segurança: O EBS permite criptografar dados em repouso em volumes usando chaves gerenciadas pela AWS. Isso ajuda a garantir a privacidade e a proteção dos dados do usuário.
5. Flexibilidade: O EBS é altamente flexível e fornece vários recursos, como snapshots, elastic volumes, replicação cruzada de regiões e provisioned IOPS, para atender às necessidades de diferentes tipos de aplicativos.
6. Integração com outros serviços AWS: O EBS é integrado com outros serviços AWS, como Amazon EC2, Amazon RDS, Amazon Redshift e Amazon EMR, permitindo que você crie soluções de armazenamento altamente escaláveis e confiáveis para seus aplicativos.

### Features

Alguns dos recursos e funcionalidades do EBS incluem:

1. Snapshots: permitem criar uma cópia de backup de um volume EBS para armazenamento no Amazon Simple Storage Service (S3).
2. Volume Types: fornece diferentes tipos de volumes de armazenamento com características específicas de desempenho, durabilidade e custo, incluindo SSD, HDD, Cold HDD e Magnetic.
3. Elastic Volumes: permite alterar o tamanho e o tipo de volume sem interromper a instância EC2, fornecendo maior flexibilidade e facilidade na gestão de armazenamento.
4. Encryption: permite criptografar os dados armazenados nos volumes EBS usando chaves gerenciadas pela AWS.
5. Cross-Region Replication: permite replicar automaticamente os snapshots de volumes EBS para outra região da AWS para fins de backup e recuperação de desastres.
6. Fast Snapshot Restore: permite restaurar rapidamente os snapshots EBS, melhorando a disponibilidade de aplicativos e reduzindo o tempo de inatividade.
7. Provisioned IOPS: permite provisionar IOPS (operações de entrada/saída por segundo) para volumes de armazenamento que exigem alta performance de I/O.
8. Multi-Attach: permite anexar um volume EBS a várias instâncias EC2 simultaneamente, o que é útil para cargas de trabalho compartilhadas ou de alta disponibilidade.

### Snapshot

Um snapshot é uma cópia do estado de um volume do EBS em um determinado ponto no tempo. Ele captura o estado do volume do EBS, incluindo todos os dados e metadados, como permissões e atributos. Os snapshots do EBS são armazenados no Amazon S3, o que garante durabilidade e disponibilidade dos dados.

Os snapshots do EBS são uma maneira eficiente de fazer backup e restaurar volumes do EBS, além de serem uma ferramenta útil para criar novos volumes do EBS a partir de um ponto de partida conhecido. Por exemplo, se você precisa criar uma nova instância do Amazon EC2 que seja semelhante a uma instância existente, você pode usar um snapshot do EBS dessa instância para criar um novo volume do EBS e, em seguida, usar esse volume para criar uma nova instância do EC2.

Os snapshots do EBS também são usados para criar backups incrementais. Quando um snapshot é criado, apenas os blocos modificados desde o último snapshot são copiados, o que economiza tempo e espaço em disco. Além disso, os snapshots do EBS podem ser copiados para outras regiões do AWS para fins de recuperação de desastres ou para serem usados como base para volumes do EBS em outras regiões.

Em resumo, o snapshot do EBS é uma ferramenta importante para fazer backup e restaurar volumes do EBS, criar novos volumes do EBS a partir de um ponto de partida conhecido e para criar backups incrementais de seus dados do EBS.

### DLM

O Amazon Data Lifecycle Manager (DLM) é um serviço que ajuda a gerenciar automaticamente a criação, retenção e exclusão de snapshots de volumes do EBS. Com o DLM, você pode definir políticas de ciclo de vida para os seus snapshots, o que pode ajudar a garantir que os dados estejam disponíveis quando você precisar deles e também reduzir os custos de armazenamento.

O Amazon DLM oferece vários recursos, incluindo:

1. Programação flexível: você pode definir políticas de ciclo de vida para seus snapshots, com a opção de programar a execução dessas políticas de acordo com as suas necessidades.
2. Políticas personalizadas: você pode criar políticas de ciclo de vida personalizadas que atendam às suas necessidades específicas, como a definição de uma programação para a criação e retenção de snapshots, bem como a exclusão automática de snapshots antigos.
3. Controle granular: você pode definir políticas de ciclo de vida para diferentes volumes, dependendo de suas necessidades específicas de armazenamento.
4. Integração com AWS Backup: o Amazon DLM é totalmente integrado com o AWS Backup, permitindo que você crie e gerencie políticas de ciclo de vida para seus snapshots de EBS através de uma única interface.
5. Redução de custos: com a programação de políticas de ciclo de vida, você pode automatizar a exclusão de snapshots antigos, ajudando a reduzir os custos de armazenamento.

Em resumo, o Amazon DLM ajuda a automatizar o gerenciamento de snapshots de EBS, proporcionando maior flexibilidade, personalização e controle granular sobre as políticas de ciclo de vida. Isso pode ajudar a garantir a disponibilidade de dados quando você precisar deles, bem como reduzir os custos de armazenamento.

### FSR

Fast Snapshot Restore (FSR) é um recurso da AWS que permite a restauração rápida de snapshots do Amazon Elastic Block Store (EBS).

Com o FSR, os snapshots EBS são armazenados em caches em uma instância EC2 dedicada e podem ser restaurados em questão de segundos, em vez de minutos, o que é o tempo necessário para restaurar os snapshots tradicionalmente. Isso ajuda a melhorar a disponibilidade de aplicativos e reduzir o tempo de inatividade, pois os volumes EBS podem ser restaurados rapidamente a partir de snapshots sem a necessidade de esperar por um longo processo de restauração.

O FSR pode ser ativado para cada snapshot EBS individualmente ou em lote usando as APIs da AWS ou o console de gerenciamento. É importante notar que o FSR está disponível apenas em algumas regiões da AWS e pode ser cobrado pelo uso do recurso.

## EFS

O Amazon Elastic File System (EFS) é um serviço de armazenamento de arquivos gerenciado pela AWS que fornece armazenamento de arquivos altamente escalável e acessível para cargas de trabalho baseadas em nuvem. Com o EFS, as empresas podem armazenar e acessar arquivos diretamente de suas instâncias EC2, compartilhando dados entre várias instâncias, sem a necessidade de gerenciar a infraestrutura de armazenamento subjacente.

O EFS é projetado para ser altamente escalável, com capacidade de se adaptar dinamicamente ao crescimento de dados e de armazenar petabytes de arquivos. Ele também oferece alta disponibilidade, com redundância de dados multi-az (disponível em várias zonas de disponibilidade), tornando-o uma solução adequada para aplicativos com requisitos críticos de tempo de atividade. Além disso, o EFS é altamente seguro, permitindo o controle de acesso baseado em políticas e criptografia de dados em repouso e em trânsito.

O EFS pode ser usado em uma ampla gama de casos de uso, incluindo sites, aplicativos móveis, análise de big data, processamento de mídia e desenvolvimento de software. Com o EFS, as empresas podem aproveitar os benefícios do armazenamento de arquivos na nuvem, incluindo a flexibilidade, escalabilidade e economia de custos, sem a necessidade de gerenciar a infraestrutura subjacente.

### EFS IA

AWS EFS IA (Amazon Elastic File System Infrequent Access) é um serviço da AWS que fornece armazenamento de arquivos acessível pela Internet, que é escalável, seguro e altamente disponível. Ele oferece aos usuários um armazenamento de dados eficiente e econômico, com acesso a arquivos frequentes e não frequentes, em um único sistema de arquivos.

O Amazon EFS IA é uma opção de armazenamento mais barata para arquivos que não são acessados com frequência, como backups, arquivos de log, arquivos de vídeo e outros tipos de dados menos usados. Ele usa a mesma infraestrutura de armazenamento de dados do Amazon EFS padrão, porém com a capacidade de reduzir os custos de armazenamento em até 85% em comparação com o Amazon EFS padrão.

Em resumo, o AWS EFS IA é um serviço de armazenamento de arquivos altamente escalável, seguro e econômico, que permite aos usuários acessar arquivos frequentes e não frequentes de um sistema de arquivos compartilhado e reduzir significativamente os custos de armazenamento de dados.

### Perfomance modes

O AWS EFS Performance Modes são modos de desempenho que podem ser selecionados ao criar um sistema de arquivos do EFS. Existem dois modos de desempenho disponíveis: "General Purpose" (Uso geral) e "Max I/O" (Máximo de E/S).

O modo "General Purpose" é adequado para a maioria das cargas de trabalho e oferece um equilíbrio entre o desempenho de leitura e gravação. Já o modo "Max I/O" é projetado para cargas de trabalho intensivas em leitura e gravação, como grandes bancos de dados ou aplicativos de processamento de vídeo. Ele oferece um desempenho de leitura e gravação mais alto, mas com um custo maior de operação.

Ao selecionar o modo de desempenho correto para o seu sistema de arquivos do EFS, você pode garantir que seus aplicativos e cargas de trabalho tenham o desempenho ideal e eficiente.

### Troughput modes

O EFS oferece opções de throughput modes (modos de taxa de transferência) que determinam a velocidade e o desempenho com que os dados são transferidos para e a partir do sistema de arquivos. Existem dois tipos de throughput modes no AWS EFS: o modo "Provisioned" e o modo "Bursting".

No modo "Provisioned", o usuário escolhe uma taxa de transferência predefinida e paga um preço fixo para manter essa taxa constante. Esse modo é ideal para aplicativos com requisitos de desempenho consistentes e previsíveis.

No modo "Bursting", a taxa de transferência é determinada pela quantidade de dados armazenados no EFS. Quando o sistema de arquivos está ocioso, ele acumula créditos de burst que podem ser usados para aumentar a taxa de transferência em momentos de pico de uso. Esse modo é mais adequado para aplicativos com requisitos de desempenho variáveis e que podem lidar com atrasos ocasionais.

Em resumo, os throughput modes no AWS EFS são uma forma flexível e escalável de gerenciar a taxa de transferência de dados em um sistema de arquivos na nuvem, permitindo que os usuários escolham a opção mais adequada para suas necessidades específicas.

### EFS Containers

O AWS EFS (Elastic File System) Containers é um serviço da AWS que oferece uma solução de armazenamento de arquivos escalável e flexível para containers em ambientes de computação em nuvem. Com o EFS Containers, é possível armazenar dados de aplicativos de containers em um sistema de arquivos compartilhado, permitindo que vários containers acessem e compartilhem os mesmos arquivos simultaneamente. Isso facilita a criação de aplicativos altamente disponíveis e tolerantes a falhas, além de permitir que os desenvolvedores criem, implantem e gerenciem aplicativos de containers de forma mais eficiente. O EFS Containers é integrado com o Amazon Elastic Container Service (ECS) e o Kubernetes, permitindo que os usuários gerenciem facilmente o armazenamento de arquivos para seus aplicativos de containers em ambientes de nuvem AWS.

### EFS, fFSx, FSx for Lustre

AWS EFS (Amazon Elastic File System) é um serviço de armazenamento em nuvem totalmente gerenciado que fornece um sistema de arquivos compartilhado para uso com instâncias do Amazon EC2 (Elastic Compute Cloud). Ele é escalável, elástico e fornece acesso de leitura e gravação para múltiplas instâncias de EC2, permitindo que vários usuários acessem os mesmos arquivos simultaneamente.

AWS FSx (Amazon FSx) é um serviço gerenciado de armazenamento de arquivos nativo na nuvem que oferece um sistema de arquivos Windows e Linux totalmente compatível com o servidor, projetado para execução em instâncias do Amazon EC2. Ele é dimensionável, seguro e fornece acesso a arquivos de alta performance.

O FSx para Lustre é uma opção adicional do serviço FSx que permite a execução de aplicativos de alto desempenho que requerem acesso a sistemas de arquivos de alta performance. O FSx para Lustre é um sistema de arquivos distribuído e paralelo que é altamente escalável e projetado para aplicações que exigem altas taxas de transferência de dados, como computação de alto desempenho (HPC), modelagem e simulação, processamento de imagens e vídeo, entre outros. Ele é executado no cluster Lustre, que é um sistema de arquivos de código aberto usado por organizações de todo o mundo para executar aplicações de HPC.

| Recurso | Amazon EFS | Amazon FSx para Windows File Server | Amazon FSx para Lustre |
| --- | --- | --- | --- |
| Tipo de serviço | Serviço de armazenamento de arquivos | Serviço de armazenamento de arquivos | Serviço de armazenamento de arquivos |
| Protocolos suportados | NFS | SMB | Lustre |
| Escalabilidade | Escalabilidade automática, sem limites de capacidade | Escalabilidade vertical (adicionar mais armazenamento) e horizontal (adicionar mais instâncias) | Escalabilidade vertical (adicionar mais armazenamento) e horizontal (adicionar mais instâncias) |
| Recursos compartilhados | Compartilhamento de arquivos em vários sistemas de arquivos | Compartilhamento de arquivos em vários sistemas de arquivos | Compartilhamento de arquivos em vários sistemas de arquivos |
| Acesso | Acesso de arquivos simultâneo de várias instâncias | Acesso de arquivos simultâneo de várias instâncias | Acesso de arquivos simultâneo de várias instâncias |
| Integração com o Active Directory | Não | Sim | Sim |
| Casos de uso recomendados | Compartilhamento de arquivos entre várias instâncias EC2 | Migração de aplicativos do Windows para a nuvem | Processamento de dados em paralelo, HPC, simulações e análises de big data |
| Custo | Faturamento por GB de armazenamento e transferência de dados | Faturamento por hora da instância EC2 e armazenamento | Faturamento por hora da instância EC2 e armazenamento |

### Instance Store

O Instance Store é um serviço de armazenamento temporário oferecido pela AWS que fornece armazenamento local para as instâncias EC2 (Elastic Compute Cloud) na nuvem da AWS. Ao contrário do Amazon EBS (Elastic Block Store) e do Amazon EFS (Elastic File System), o Instance Store oferece armazenamento temporário diretamente associado a uma instância EC2 e, portanto, não é persistente.

O Instance Store é um tipo de armazenamento que é fornecido localmente em uma instância EC2 física e não está disponível para outras instâncias. Ele é projetado para oferecer alta velocidade e baixa latência de leitura e gravação, tornando-o ideal para aplicativos com requisitos de I/O intensivos, como processamento de banco de dados em memória, cache de aplicativos e processamento de big data.

As limitações do Instance Store incluem sua natureza não persistente e não escalável. Uma vez que os dados armazenados no Instance Store são perdidos quando a instância é interrompida ou terminada, ele deve ser usado apenas para dados temporários e descartáveis. O Instance Store também não pode ser ampliado para atender a necessidades de armazenamento adicionais, o que pode ser uma limitação para aplicativos que exigem grande capacidade de armazenamento.

Em resumo, o Instance Store é uma opção de armazenamento local de alta velocidade para dados temporários e não críticos que exigem baixa latência. É importante considerar as limitações da Instance Store ao escolher a opção de armazenamento mais adequada para uma carga de trabalho específica.

| Características | EBS | EFS | Instance Store |
| --- | --- | --- | --- |
| Tipo de armazenamento | Bloco | Arquivo | Temporário |
| Persistência | Persistente | Persistente | Não persistente |
| Capacidade de armazenamento | Até 16 TB | Até petabytes | Limitado pela instância |
| Acesso simultâneo | Apenas um ponto de montagem por vez | Vários pontos de montagem simultâneos | N/A |
| Desempenho | Boa performance | Bom desempenho para acesso aleatório e baixo desempenho para acesso sequencial | Alto desempenho para acesso sequencial |
| Recuperação de desastres | Snapshots e replicação de região | Replicação de região | Não é possível fazer backup e restauração |
| Uso recomendado | Banco de dados, aplicativos críticos | Compartilhamento de arquivos, ambientes de desenvolvimento | Processamento temporário de dados, cache, logs |

# Redes

## VPC

VPC (Virtual Private Cloud) é um serviço de rede da AWS que permite que você crie uma nuvem privada virtual na qual você pode lançar recursos da AWS, como instâncias EC2 (Elastic Compute Cloud) e bancos de dados RDS (Relational Database Service). É possível criar e configurar uma VPC para atender às necessidades específicas da sua aplicação ou organização.

Com a VPC, você pode criar um ambiente de rede isolado e seguro na nuvem AWS. É possível definir endereços IP privados, criar sub-redes, configurar tabelas de rotas e definir regras de segurança em um nível granular para controlar o tráfego de entrada e saída da VPC. Além disso, você pode conectar a VPC ao data center local ou a outras redes usando uma conexão de rede privada, como VPN (Virtual Private Network) ou AWS Direct Connect.

A VPC também oferece recursos avançados, como a capacidade de criar instâncias EC2 em várias sub-redes para melhorar a escalabilidade e a resiliência, bem como criar e gerenciar grupos de segurança para controlar o tráfego de entrada e saída .

A AWS oferece opções flexíveis de configuração da VPC, como criar uma VPC a partir do zero ou usar um modelo pré-configurado. Além disso, é possível usar ferramentas como o Amazon VPC Wizard para configurar rapidamente a VPC com base em configurações comuns.

Em resumo, a VPC da AWS é um serviço de rede que fornece um ambiente de computação em nuvem isolado, seguro e altamente personalizável para permitir que você execute seus aplicativos e serviços na nuvem AWS de maneira eficiente e escalável.

### Route Tables

Route Tables na AWS é um serviço que permite controlar o tráfego de rede dentro de uma rede virtual (VPC) criada na AWS. A tabela de roteamento é um conjunto de regras que determina o tráfego de entrada e saída da VPC, especificando o destino de cada pacote de rede que entra ou sai da VPC.

A tabela de roteamento é uma lista de rotas que define como o tráfego de rede é encaminhado entre a VPC e a internet, ou entre a VPC e outras redes que possam estar conectadas a ela. Cada tabela de roteamento pode ter várias regras de roteamento, e cada regra pode especificar um destino de rede, como um endereço IP ou um intervalo de endereços IP, e o caminho que o tráfego deve seguir para alcançar esse destino, como uma interface de rede ou um gateway da Internet.

Por padrão, cada VPC é criada com uma tabela de roteamento padrão que é aplicada a todas as sub-redes da VPC. No entanto, você pode criar tabelas de roteamento personalizadas para atender às suas necessidades específicas. Por exemplo, você pode criar uma tabela de roteamento separada para lidar com o tráfego de rede de uma sub-rede específica, ou pode criar uma tabela de roteamento separada para lidar com o tráfego de rede de um grupo específico de instâncias.

Ao configurar uma tabela de roteamento na AWS, você pode definir rotas para direcionar o tráfego de entrada e saída da VPC. Isso permite que você controle o tráfego de rede de maneira granular e eficiente, ajudando a garantir que o tráfego seja encaminhado corretamente e reduzindo a possibilidade de falhas de rede ou problemas de segurança.

### Internet Gateway

Internet Gateway (ou Gateway de Internet) na AWS é um serviço que permite que uma rede privada, criada por meio do Amazon Virtual Private Cloud (VPC), tenha acesso à Internet pública.

Ao criar uma VPC na AWS, ela é criada como uma rede privada isolada da Internet. Isso significa que as instâncias EC2 (Elastic Compute Cloud) e outros recursos dentro da VPC não têm acesso à Internet pública. Para permitir que esses recursos se comuniquem com a Internet, é necessário criar um Internet Gateway e anexá-lo à VPC.

O Internet Gateway é um componente virtual que funciona como um roteador entre a VPC e a Internet pública. Ele permite que as instâncias EC2 e outros recursos dentro da VPC se conectem à Internet e, ao mesmo tempo, protege a VPC de tráfego não autorizado.

Para utilizar o Internet Gateway, é necessário configurar as rotas na tabela de roteamento da VPC para direcionar o tráfego de saída para o Internet Gateway. Isso permitirá que o tráfego gerado pelos recursos da VPC sejam roteados para a Internet pública.

É importante destacar que o uso do Internet Gateway pode implicar em custos adicionais devido ao tráfego de dados que é gerado entre a VPC e a Internet pública. Além disso, é importante configurar a segurança da VPC adequadamente para garantir que apenas o tráfego autorizado tenha acesso à Internet pública.

### Peering Connection

O AWS Peering Connection é uma conexão de rede privada direta entre duas VPCs (Virtual Private Clouds) diferentes dentro do ambiente da Amazon Web Services (AWS). Esse recurso permite que as VPCs comuniquem-se entre si de forma segura, confiável e de alta velocidade, sem precisar passar pela internet pública.

Com o AWS Peering Connection, é possível conectar VPCs dentro da mesma conta AWS ou em diferentes contas. Essa conexão é estabelecida através de um túnel criptografado, garantindo a privacidade e segurança dos dados trocados entre as VPCs.

O AWS Peering Connection permite que as VPCs compartilhem recursos e serviços, como instâncias EC2, bancos de dados RDS, balanceadores de carga ELB, entre outros. Além disso, a conexão entre as VPCs pode ser facilmente gerenciada através do console de gerenciamento da AWS ou utilizando ferramentas de linha de comando, permitindo que os usuários configurem, monitorem e gerenciem as conexões de forma eficiente.

Em resumo, o AWS Peering Connection é uma solução ideal para empresas que precisam integrar e compartilhar recursos entre VPCs em sua infraestrutura da AWS, de forma privada e segura.

## Security Group

Security groups são um recurso da AWS que fornecem uma camada adicional de segurança para as instâncias do Amazon Elastic Compute Cloud (Amazon EC2), permitindo que você controle o acesso de entrada e saída para as instâncias. Eles funcionam como um firewall virtual para sua instância EC2, permitindo que você controle o tráfego de rede de entrada e saída que é permitido na sua instância.

Cada security group atua como uma política de segurança para uma ou mais instâncias EC2, especificando as portas de entrada permitidas, os protocolos de rede aceitos e os endereços IP de origem autorizados. Isso significa que você pode permitir ou negar o tráfego de entrada ou saída para sua instância com base em uma série de regras de segurança que você definiu.

Os security groups da AWS são criados com base em regras que você define, incluindo o tipo de tráfego permitido (por exemplo, HTTP, SSH, RDP), os intervalos de endereços IP permitidos (por exemplo, de um único endereço IP ou de um intervalo de endereços IP), e as portas permitidas para o tráfego (por exemplo, a porta 80 para o tráfego HTTP).

Cada instância EC2 pode ser associada a um ou mais security groups, e os security groups podem ser aplicados a várias instâncias. É importante notar que os security groups são específicos da região em que foram criados e só se aplicam às instâncias dentro dessa região.

Em resumo, os security groups são uma maneira eficiente de garantir a segurança das suas instâncias EC2, permitindo que você defina políticas de segurança baseadas em regras para controlar o tráfego de entrada e saída.

## NACL

O NACL é um recurso da AWS que permite controlar o tráfego de rede em uma VPC (Virtual Private Cloud) da AWS. Ele age como uma camada adicional de segurança, além das regras de segurança de grupos de segurança. O NACL permite configurar regras de entrada e saída de tráfego de rede para uma ou mais sub-redes dentro da VPC.

Cada NACL é composto por uma lista de regras numeradas em ordem de prioridade. Cada regra contém informações como o tipo de tráfego permitido (por exemplo, HTTP, SSH, RDP), o endereço IP de origem e destino, e a ação a ser tomada em caso de correspondência da regra (por exemplo, permitir ou negar o tráfego).

O NACL é útil para permitir ou bloquear o tráfego de rede em um nível mais granular, dependendo das necessidades de segurança da sua aplicação. No entanto, é importante lembrar que configurar o NACL incorretamente pode bloquear o tráfego legítimo da sua aplicação, portanto, é necessário ter cuidado ao configurá-lo.

## PoP

Em termos de AWS, PoP significa Point of Presence, que se refere a um local físico onde a AWS possui equipamentos de rede e infraestrutura para fornecer serviços de nuvem aos seus clientes.

A AWS possui PoPs em diversas localidades ao redor do mundo, incluindo América do Norte, Europa, Ásia, Austrália, América Latina, Oriente Médio e África. Esses PoPs são essenciais para permitir que os clientes da AWS acessem os serviços em suas regiões geográficas com baixa latência e alta disponibilidade.

Os PoPs da AWS geralmente incluem servidores, roteadores e outros equipamentos de rede que gerenciam o tráfego de dados e garantem que os serviços da AWS estejam disponíveis e funcionando adequadamente para os usuários finais. Além disso, os PoPs podem incluir recursos de cache, como o Amazon CloudFront, que armazena em cache conteúdo web e distribui esse conteúdo a partir do local mais próximo ao usuário final, reduzindo a latência e melhorando o desempenho.

Em resumo, os PoPs são pontos de presença física da AWS que fornecem recursos de infraestrutura de rede e computação, permitindo que os clientes da AWS acessem os serviços em suas regiões com baixa latência e alta disponibilidade.

## Elastic IP

O Elastic IP é um serviço da AWS (Amazon Web Services) que permite aos usuários ter um endereço IP estático e fixo para uma instância EC2 (Elastic Compute Cloud) ou uma interface de rede. Normalmente, quando você inicia uma instância EC2 na AWS, ela recebe um endereço IP público que pode mudar sempre que a instância é parada ou iniciada novamente. Com o Elastic IP, você pode atribuir um endereço IP estático e fixo para sua instância, que permanecerá o mesmo, mesmo que a instância seja interrompida ou iniciada novamente.

O uso do Elastic IP é especialmente importante quando se trata de hospedagem de sites ou aplicativos, pois permite que você mantenha um endereço IP fixo para sua instância, o que facilita a conexão de domínios personalizados, configuração de DNS e outros recursos de rede.

O Elastic IP é fácil de configurar na AWS. Você pode alocar um novo endereço IP ou usar um endereço IP existente e associá-lo a uma instância EC2 ou interface de rede. É importante lembrar que a AWS cobra uma pequena taxa horária pelo uso de um endereço IP elástico alocado, a menos que ele esteja associado a uma instância em execução. Portanto, é importante monitorar o uso do Elastic IP e desassociá-lo de instâncias em execução quando não estiver em uso para evitar cobranças desnecessárias.

## ELB

AWS ELB (Elastic Load Balancer) é um serviço da AWS que distribui o tráfego de rede entre instâncias EC2 (Elastic Compute Cloud) ou containers. O ELB ajuda a melhorar a disponibilidade e escalabilidade de aplicações, permitindo que elas sejam executadas em várias instâncias simultaneamente, sem sobrecarregar nenhuma delas. O serviço monitora o tráfego e redireciona as requisições para as instâncias disponíveis, tornando o processo transparente para o usuário final. O AWS ELB também oferece recursos de segurança, como a capacidade de criptografar o tráfego de rede e proteger as instâncias de ataques DDoS (Distributed Denial of Service). Em resumo, o AWS ELB é uma ferramenta essencial para garantir a disponibilidade, escalabilidade e segurança de aplicações na nuvem.

### Listener

AWS ELB Listener é um componente do Elastic Load Balancing (ELB) da AWS que atua como um ponto de entrada para o tráfego de rede que chega ao Load Balancer. O Listener é responsável por receber as solicitações de tráfego e direcioná-las para os recursos de back-end, como instâncias do Amazon EC2, contêineres ou outros serviços web.

O Listener opera em um ou mais protocolos de camada de transporte (como HTTP, HTTPS, TCP, SSL) e portas definidas pelo usuário. Ele também define o comportamento do Load Balancer em relação ao tráfego recebido, como o roteamento de solicitações para diferentes grupos de destino ou distribuição do tráfego por porcentagem, sessão ou endereço IP do cliente.

Em resumo, o AWS ELB Listener é um elemento fundamental para configurar e gerenciar o fluxo de tráfego em um ambiente de infraestrutura na nuvem da AWS, permitindo a distribuição de carga de trabalho e a alta disponibilidade dos aplicativos hospedados em diferentes instâncias ou serviços.

### Tipos

1. Classic Load Balancer: como mencionado anteriormente, é o tipo mais antigo de ELB e suporta balanceamento de carga para aplicações web HTTP/HTTPS e TCP/SSL.
2. Application Load Balancer: como mencionado anteriormente, é um ELB avançado que suporta balanceamento de carga de aplicações web HTTP/HTTPS. Ele roteia tráfego para instâncias EC2 com base em regras definidas em um nível de aplicação, como URL, cabeçalhos de solicitação e cookies.
3. Network Load Balancer: como mencionado anteriormente, é um ELB que suporta balanceamento de carga de camada de rede TCP/UDP. Ele é capaz de lidar com altas taxas de transferência e conexões de baixa latência.
4. Gateway Load Balancer: é um novo tipo de ELB que fornece escalabilidade, disponibilidade e segurança para cargas de trabalho que executam em um ambiente de gateway, como VPN, NAT e firewalls. O Gateway Load Balancer é compatível com AWS Transit Gateway, permitindo a integração fácil de gateways com recursos em diferentes regiões ou contas da AWS.

| Recurso | Classic Load Balancer (CLB) | Application Load Balancer (ALB) | Network Load Balancer (NLB) | Gateway Load Balancer (GLB) |
| --- | --- | --- | --- | --- |
| Tipo de balanceamento de carga | Nível de conexão | Camada de aplicação | Camada de transporte | Camada de rede |
| Suporte de protocolos | HTTP, HTTPS, TCP, SSL | HTTP, HTTPS, WebSocket, HTTP/2 | TCP, UDP | TCP, UDP, HTTP(S) |
| Redirecionamento de URL | Não | Sim | Não | Sim |
| Roteamento de tráfego | Baseado em regras e recursos | Baseado em regras | Baseado em regras e recursos | Baseado em regras e recursos |
| Balanceamento de carga de IP | Não | Sim | Sim | Sim |
| Suporte de porta | Portas fixas | Portas variáveis | Portas fixas | Portas fixas e variáveis |
| Escalabilidade | Escalabilidade vertical e horizontal (limitada) | Escalabilidade vertical e horizontal | Escalabilidade horizontal | Escalabilidade horizontal |
| Preços | Cobrado por hora | Cobrado por hora | Cobrado por hora | Cobrado por hora |

# Computação

## EC2

EC2 (Elastic Compute Cloud) é um serviço de computação em nuvem fornecido pela AWS que permite que os usuários executem instâncias de servidores virtualizados na nuvem. Com o EC2, os usuários podem criar, configurar e gerenciar facilmente instâncias de servidores sob demanda, com escalabilidade rápida e flexível.

O EC2 é altamente escalável e pode ser usado para hospedar aplicativos e serviços de todos os tamanhos, desde pequenos sites e aplicativos até grandes empresas com tráfego e demanda intensos. Com o EC2, os usuários podem selecionar a capacidade de processamento, memória, armazenamento e rede que melhor atende às suas necessidades.

O EC2 oferece várias opções de sistema operacional, incluindo Amazon Linux, Ubuntu, Windows Server, entre outros, e os usuários podem configurar suas instâncias para atender às suas necessidades específicas. Além disso, o EC2 é altamente seguro e oferece recursos avançados de segurança, como criptografia de dados em trânsito e em repouso, controle de acesso e segurança de rede.

O EC2 é usado por empresas de todos os tamanhos e em todos os setores para hospedar aplicativos, sites, serviços e aplicativos móveis na nuvem. Ele oferece uma alternativa econômica e escalável ao provisionamento de servidores em data centers locais e ajuda as empresas a reduzir custos e aumentar a agilidade e a eficiência dos negócios.

### Diferença entre EC2 e S3

EC2 e S3 são serviços diferentes da Amazon Web Services (AWS) que atendem a diferentes necessidades de computação e armazenamento na nuvem.

EC2 (Elastic Compute Cloud) é um serviço de computação em nuvem que fornece capacidade computacional sob demanda. Com o EC2, os usuários podem criar e gerenciar instâncias de máquinas virtuais (VMs) em uma infraestrutura de nuvem altamente escalável e segura.

S3 (Simple Storage Service) é um serviço de armazenamento em nuvem que permite armazenar e recuperar grandes quantidades de dados de forma segura e escalável. O S3 é frequentemente usado para armazenar arquivos estáticos, como imagens, vídeos, arquivos de áudio e backups de banco de dados, entre outros.

Em resumo, enquanto o EC2 fornece recursos de computação sob demanda, o S3 é voltado para armazenamento em nuvem de grande escala. No entanto, é possível usar esses serviços juntos para criar aplicativos escaláveis que combinam recursos de computação e armazenamento em nuvem.

### Tipo de Instância

AWS oferece diversos tipos de instâncias EC2 (Elastic Compute Cloud), cada um com diferentes combinações de CPU, memória, armazenamento e capacidade de rede, projetados para atender a diferentes cargas de trabalho. Aqui estão alguns dos tipos de instâncias EC2 disponíveis:

1. General Purpose Instances: projetadas para aplicativos que exigem uma proporção balanceada de CPU, memória e armazenamento. Exemplos: t2.micro, m5.large.
2. Computer-Optimized Instances: projetadas para cargas de trabalho que exigem alto desempenho de CPU, como aplicativos de computação científica e análise de dados. Exemplos: c5.large, c5n.18xlarge.
3. Memory-Optimized Instances: projetadas para cargas de trabalho que exigem grande quantidade de memória, como bancos de dados e análise de big data. Exemplos: r5.large, x1e.32xlarge.
4. Storage-Optimized Instances: projetadas para cargas de trabalho que exigem alto desempenho de armazenamento, como bancos de dados NoSQL e Hadoop Distributed File System (HDFS). Exemplos: d2.xlarge, i3.large.
5. GPU Instances: projetadas para cargas de trabalho que exigem desempenho de GPU, como aprendizado de máquina e processamento de vídeo. Exemplos: p3.2xlarge, g4dn.xlarge.
6. FPGA Instances: projetadas para cargas de trabalho que exigem aceleração personalizada para cargas de trabalho específicas, como processamento de imagens e análise de dados. Exemplo: f1.2xlarge.

| Recurso | Amazon EC2 | Amazon S3 |
| --- | --- | --- |
| Tipo de serviço | Serviço de computação (IaaS) | Serviço de armazenamento (S3) |
| Capacidade de armazenamento | Armazenamento efêmero em instâncias EC2 | Armazenamento ilimitado de objetos |
| Acesso | Acesso via SSH ou RDP para gerenciamento de instâncias | Acesso através de APIs ou consoles web |
| Uso de dados | Armazenamento de dados em unidades de instância de EBS ou instância temporária de armazenamento local | Armazenamento de objetos como arquivos, imagens, vídeos, etc. |
| Escalabilidade | Escalabilidade vertical (adicionar recursos à instância) e horizontal (adicionar instâncias) | Escalabilidade horizontal (adicionar mais objetos) |
| Custo | Faturamento por hora da instância EC2 e armazenamento EBS | Faturamento por GB de armazenamento e transferência de dados |

### Tipos de Volume

Existem vários tipos de volumes que podem ser usados com o Amazon EC2, incluindo:

1. Amazon Elastic Block Store (EBS): É um serviço de armazenamento de blocos de dados que pode ser anexado a uma instância do EC2 para fornecer armazenamento persistente. Os volumes do Amazon EBS são altamente disponíveis, escaláveis e fornecem opções de desempenho para atender às necessidades de diferentes cargas de trabalho.
2. Armazenamento de instâncias: As instâncias do Amazon EC2 também podem ser configuradas para usar o armazenamento local de instâncias, que é armazenamento em disco efêmero anexado fisicamente à instância. O armazenamento de instâncias é ideal para aplicativos que exigem alta taxa de transferência de dados e acesso de baixa latência.
3. Armazenamento S3: Embora o Amazon S3 seja um serviço de armazenamento de objetos, os usuários podem acessar os arquivos armazenados no S3 diretamente de suas instâncias do EC2, como se estivessem armazenados localmente. O armazenamento S3 é ideal para armazenar arquivos que não mudam com frequência e que são acessados com pouca frequência.
4. Armazenamento Glacier: O Amazon Glacier é um serviço de armazenamento em nuvem de baixo custo e altamente durável. Os usuários podem usar o Glacier como um destino de backup para seus dados do EC2 ou para arquivar dados que não são acessados com frequência.

### AMI

AMI (Amazon Machine Image) é uma imagem de máquina pré-configurada, que pode ser usada para criar instâncias do Amazon Elastic Compute Cloud (EC2). É basicamente uma imagem de backup de uma instância EC2, que pode ser usada para lançar novas instâncias EC2 idênticas à instância original.

Uma AMI inclui informações sobre o sistema operacional, as configurações de rede, os aplicativos instalados e outros dados necessários para lançar uma nova instância. Isso permite que os usuários criem e implementem facilmente novas instâncias EC2 que sejam semelhantes às instâncias existentes.

As AMIs podem ser criadas a partir de instâncias EC2 existentes ou criadas do zero, permitindo aos usuários personalizar as imagens para atender às suas necessidades específicas. As AMIs também podem ser compartilhadas entre contas da AWS e, em alguns casos, estão disponíveis publicamente para que qualquer pessoa possa usá-las.

Em resumo, AMIs são imagens de máquinas virtuais que fornecem uma maneira fácil de lançar e replicar instâncias EC2 com configurações específicas. Isso ajuda a simplificar o processo de implantação e escalabilidade de aplicativos na nuvem.

### Spot

O Amazon EC2 Spot é um serviço da AWS que permite aos usuários aproveitar instâncias EC2 (Elastic Compute Cloud) não utilizadas a preços significativamente reduzidos. O Spot permite que os usuários aproveitem a capacidade ociosa de instâncias EC2 em execução na nuvem da AWS, permitindo que sejam usados a preços mais baixos do que as instâncias On-Demand.

As instâncias Spot são uma forma econômica de executar cargas de trabalho que são tolerantes a falhas e que podem ser interrompidas ou iniciadas em momentos diferentes. Os usuários podem solicitar instâncias Spot para suas cargas de trabalho a um preço que especificam, e a AWS aloca a capacidade de acordo com a oferta de capacidade ociosa disponível.

Os preços Spot flutuam continuamente com base na oferta e demanda de capacidade de instâncias. Quando o preço de uma instância Spot cai abaixo do preço que o usuário especificou, a instância é iniciada e executada até que a capacidade seja necessária por outro cliente com um preço maior. Quando isso acontece, a instância Spot é interrompida, permitindo que a capacidade seja usada por outro cliente.

O Spot pode ser usado para uma variedade de cargas de trabalho, incluindo tarefas de processamento em lote, cargas de trabalho de teste e desenvolvimento, análise de big data, entre outras. Ele pode ser integrado a outros serviços da AWS, como o Amazon EMR (Elastic MapReduce) e o AWS Batch, para criar ambientes de processamento em escala em um custo mais baixo.

O Spot é altamente escalável, tolerante a falhas. Com este serviço, os usuários podem economizar significativamente nos custos de infraestrutura de suas cargas de trabalho, aproveitando a capacidade ociosa da nuvem da AWS.

### EC2 Auto Scaling

O Amazon EC2 Auto Scaling é um AWS que permite que os usuários dimensionem automaticamente grupos de instâncias EC2 (Elastic Compute Cloud) para atender a demanda da aplicação. O serviço ajuda a garantir que o número de instâncias em execução seja proporcional à carga de trabalho, evitando a sobrecarga dos servidores ou a ociosidade de recursos.

Com o EC2 Auto Scaling, os usuários podem criar grupos de instâncias EC2 que são dimensionados automaticamente com base em métricas de utilização, como a CPU, memória, tráfego de rede e outras. O serviço permite que os usuários definam políticas de dimensionamento para aumentar ou diminuir o número de instâncias em execução com base em limites mínimos e máximos de capacidade.

O EC2 Auto Scaling também pode ser integrado a outros serviços da AWS, como o Elastic Load Balancing, para garantir que as instâncias sejam adicionadas ou removidas automaticamente com base na carga de trabalho do balanceador de carga. Além disso, o serviço oferece recursos de monitoramento e notificação para alertar os usuários sobre eventos de escalabilidade ou problemas de desempenho.

O EC2 Auto Scaling é altamente escalável, tolerante a falhas e pode ser facilmente configurado por meio do console da AWS, API ou linha de comando. Com este serviço, os usuários podem garantir que sua aplicação seja executada com a capacidade ideal, otimizando o desempenho e reduzindo os custos operacionais.

## Lambda Shared

O AWS Lambda Shared é um recurso da AWS Lambda que permite compartilhar recursos comuns entre diferentes funções do Lambda. Com o AWS Lambda Shared, você pode criar um código compartilhado ou biblioteca de funções que pode ser usado em várias funções sem a necessidade de copiá-las ou mantê-las separadamente. Isso pode ajudar a reduzir o tempo de desenvolvimento e a complexidade do código, além de melhorar a reutilização de código e a colaboração em equipe.

Para usar o AWS Lambda Shared, você pode criar uma camada (layer) que contém o código compartilhado ou uma biblioteca de funções e, em seguida, adicionar essa camada a uma ou mais funções do Lambda. Dessa forma, as funções podem acessar o código compartilhado ou a biblioteca de funções e usar suas funcionalidades em tempo de execução. Além disso, as camadas podem ser versionadas e gerenciadas separadamente, o que torna mais fácil manter e atualizar o código compartilhado em um ambiente distribuído.

Em resumo, o AWS Lambda Shared é uma solução para simplificar o desenvolvimento de funções do Lambda e melhorar a reutilização de código em diferentes projetos. Com ele, é possível compartilhar recursos comuns de forma simples, segura e escalável.

## Severless

AWS Serverless é um modelo de computação em nuvem que permite que os desenvolvedores criem e executem aplicativos sem se preocupar com a infraestrutura de hardware subjacente. Em um ambiente Serverless, a AWS gerencia automaticamente a alocação e a escalabilidade dos recursos de computação, armazenamento e rede, tornando o processo de desenvolvimento e implantação de aplicativos mais rápido e fácil.

O modelo de arquitetura Serverless da AWS é baseado em serviços que permitem que os desenvolvedores se concentrem apenas no código da aplicação, sem precisar lidar com a infraestrutura do servidor. Esses serviços incluem AWS Lambda, que permite executar código sem um servidor; Amazon API Gateway, que gerencia o acesso aos serviços e recursos do AWS; e AWS DynamoDB, que é um banco de dados NoSQL escalável e totalmente gerenciado.

Ao usar o modelo Serverless, os desenvolvedores podem implantar aplicativos rapidamente, escalar automaticamente conforme a demanda e pagar apenas pelos recursos que usam, reduzindo significativamente os custos de infraestrutura. Além disso, a AWS Serverless oferece alta disponibilidade e segurança, com recursos integrados de monitoramento e registro de dados para facilitar a depuração e a análise.

# Banco de Dados

## Amazon RDS

Amazon RDS (Relational Database Service) é um serviço gerenciador de banco de dados relacionais na nuvem da AWS. Ele permite que você crie, execute e dimensione facilmente bancos de dados relacionais na nuvem.

Os benefícios do Amazon RDS incluem:

- Gerenciamento automatizado: O Amazon RDS gerencia automaticamente tarefas de rotina, como aplicação de patches de segurança, backups e monitoramento de desempenho. Isso permite que você se concentre em desenvolver seus aplicativos, em vez de gerenciar a infraestrutura do banco de dados.
- Backup e recuperação: O Amazon RDS oferece backups automáticos e armazenamento em vários locais para proteger seus dados contra perda. Ele também permite que você restaure facilmente um banco de dados a partir de um ponto no tempo.
- Suporte para vários mecanismos de banco de dados: O Amazon RDS suporta vários mecanismos de banco de dados, incluindo MySQL, PostgreSQL, Oracle, SQL Server e MariaDB. Isso oferece flexibilidade para escolher o mecanismo de banco de dados que melhor atende às suas necessidades.
- Escalabilidade: O Amazon RDS permite que você dimensione facilmente seu banco de dados verticalmente ou horizontalmente para lidar com aumento de tráfego e demanda.
- Fácil de usar: O Amazon RDS é fácil de configurar e usar, e oferece uma variedade de opções de configuração para atender às necessidades específicas de seu aplicativo.

### Read Only

AWS RDS (Relational Database Service) é um serviço gerenciado de banco de dados na nuvem da Amazon Web Services (AWS). O modo read-only, ou modo somente leitura, significa que os usuários podem acessar o banco de dados para leitura de informações, mas não podem fazer alterações ou inserções.

O AWS RDS oferece suporte para múltiplas réplicas de leitura, permitindo que vários usuários acessem o banco de dados simultaneamente para leitura de informações, sem afetar a capacidade de gravação no banco de dados principal. Esse modo é útil para casos em que a maioria dos usuários precisam apenas acessar as informações armazenadas no banco de dados, sem precisar alterar ou inserir novos dados.

O modo read-only pode ser ativado ou desativado facilmente no console do AWS RDS. Quando ativo o RDS principal replica de forma assíncrona as alterações para as instâncias read-only

### Automet Backups

O AWS RDS (Relational Database Service) oferece um recurso de backups automáticos para garantir a segurança e a disponibilidade dos dados armazenados em seus bancos de dados na nuvem.

Os backups automáticos são realizados regularmente pelo RDS de forma a assegurar que os dados estejam disponíveis em caso de falhas no sistema, erros humanos ou incidentes de segurança. O recurso é totalmente gerenciado pela AWS e não requer a intervenção do usuário.

Os backups automáticos são realizados de acordo com uma política definida pelo usuário e podem ser agendados para ocorrer diariamente, semanalmente ou mensalmente. Durante o processo de backup, o RDS cria uma imagem do banco de dados, que pode ser usada posteriormente para restaurar o banco de dados em caso de necessidade.

Os backups automáticos são armazenados no Amazon S3 e podem ser retidos por até 35 dias. Isso significa que é possível restaurar o banco de dados em qualquer ponto nos últimos 35 dias.

O recurso de backups automáticos é altamente recomendado para todas as instâncias do RDS, pois garante a disponibilidade dos dados e ajuda a proteger o usuário contra perda de dados e interrupções no serviço.

### IOPS Storage

O AWS IOPS (Input/Output Operations per Second) é um serviço oferecido pela Amazon Web Services (AWS) que permite aos usuários otimizarem o desempenho de suas instâncias de banco de dados que rodam no Amazon RDS (Relational Database Service) ou no Amazon EC2 (Elastic Compute Cloud).

O IOPS Storage é um recurso do Amazon RDS que permite escolher o tipo de armazenamento para seus bancos de dados, com a opção de provisionar o número necessário de operações de entrada e saída por segundo (IOPS) para o seu banco de dados. O IOPS é uma medida de desempenho para armazenamento de dados, e quanto mais IOPS, mais rápido será o desempenho do armazenamento.

Com o IOPS Storage, os usuários podem escolher entre armazenamento padrão ou provisionado. O armazenamento padrão é adequado para cargas de trabalho de banco de dados leves e de baixa intensidade. Já o armazenamento provisionado é adequado para cargas de trabalho de banco de dados que exigem alto desempenho, como bancos de dados com muitas transações de leitura e gravação.

O IOPS Storage permite aos usuários configurar o número de IOPS que seus bancos de dados precisam para obter o melhor desempenho possível. Com isso, é possível provisionar o armazenamento de acordo com as necessidades da aplicação, garantindo um desempenho consistente e previsível, independentemente das flutuações no tráfego de aplicativos.

### General Purpose Storage

O tipo de armazenamento General Purpose (ou propósito geral) pode ser utilizado em ambos os serviços. No Amazon S3, o armazenamento General Purpose é conhecido como Amazon S3 Standard e fornece uma camada de armazenamento altamente disponível, durável e com baixa latência. No Amazon EBS, o armazenamento General Purpose é conhecido como gp2 e fornece armazenamento de bloco de alta performance para as instâncias EC2.

### Magnetic Storage

O Amazon RDS Magnetic Storage é um tipo de armazenamento disponível no serviço de banco de dados relacional da Amazon Web Services (AWS), o RDS. Esse tipo de armazenamento é a opção mais econômica do RDS e é recomendado para aplicações que não exigem alta performance de I/O, ou seja, que não precisam de um alto volume de leitura e gravação de dados no disco.

O Amazon RDS Magnetic Storage utiliza discos magnéticos (hdd) como meio de armazenamento, em vez de unidades de estado sólido (ssd), que são mais rápidas, mas também mais caras. Isso torna o RDS Magnetic Storage uma opção de armazenamento mais acessível para as aplicações que têm menor demanda por performance e/ou possuem restrições orçamentárias.

No entanto, vale lembrar que o uso do RDS Magnetic Storage pode ter um impacto na performance das aplicações que utilizam o banco de dados, especialmente em operações que envolvem leitura e gravação de grandes volumes de dados. Por isso, é importante avaliar as necessidades de performance do seu aplicativo e considerar outras opções de armazenamento oferecidas pelo RDS, como o Provisioned IOPS SSD, caso seja necessário uma maior performance de I/O.

Em resumo, o Amazon RDS Magnetic Storage é uma opção de armazenamento econômica para aplicações com menor demanda por performance e/ou com restrições orçamentárias, mas que ainda precisam de uma infraestrutura de banco de dados confiável e escalável.

### Multi-Master Clusters

Um cluster de banco de dados com múltiplos mestres na Amazon Web Services (AWS) é uma arquitetura que permite a configuração de vários nós de banco de dados mestre para operarem em paralelo e aceitar escritas simultâneas. Isso pode melhorar significativamente o desempenho e a disponibilidade do banco de dados em relação a um cluster de banco de dados convencional com um único nó mestre.

Os clusters de banco de dados com múltiplos mestres estão disponíveis no AWS RDS (Relational Database Service) para MySQL e PostgreSQL. Com a configuração de um cluster de banco de dados com múltiplos mestres, cada nó mestre tem sua própria cópia do banco de dados.

Quando uma gravação é feita em um nó mestre, a transação é replicada automaticamente em todos os outros nós mestre no cluster. Isso significa que várias escritas podem ocorrer simultaneamente, resultando em um melhor desempenho e capacidade de resposta do banco de dados.

Além disso, os clusters de banco de dados com múltiplos mestres podem ajudar a melhorar a disponibilidade do banco de dados. Se um nó mestre falhar, outro nó mestre pode assumir automaticamente e as transações podem continuar sem interrupção. Isso significa que o cluster de banco de dados pode continuar operando mesmo em caso de falha em um ou mais nós.

No entanto, é importante notar que a configuração de um cluster de banco de dados com múltiplos mestres pode ser mais complexa do que a configuração de um cluster de banco de dados convencional com um único nó mestre. A configuração requer conhecimento técnico avançado e experiência em bancos de dados, além de ajustes de configuração para garantir que as transações sejam replicadas de forma confiável em todo o cluster.

### TDE

AWS TDE (Transparent Data Encryption) é um recurso de segurança oferecido pela Amazon Web Services (AWS) que criptografa automaticamente dados em repouso armazenados em bancos de dados RDS (Relational Database Service).

O TDE usa criptografia AES-256 para proteger dados em repouso, incluindo backups, snapshots e réplicas de bancos de dados RDS. Isso ajuda a proteger os dados sensíveis armazenados em bancos de dados, garantindo que apenas usuários autorizados possam acessá-los.

O TDE é transparente para aplicativos e usuários finais, o que significa que não há necessidade de alterar o aplicativo ou a forma de acesso ao banco de dados. O TDE criptografa os dados automaticamente antes de armazená-los e descriptografa-os automaticamente quando são lidos.

Para ativar o TDE, basta selecionar a opção "Enable Encryption" ao criar um novo banco de dados RDS ou habilitá-lo em um banco de dados existente. Uma vez ativado, a chave de criptografia é gerenciada pela AWS e armazenada em um ambiente seguro e altamente disponível.

O uso do AWS TDE é uma das formas de garantir a segurança dos dados armazenados em bancos de dados RDS, juntamente com outras práticas recomendadas de segurança, como controle de acesso baseado em função (RBAC), monitoramento de logs e atualizações regulares do software.

### Standby Replica

A Standby Replica é uma instância de banco de dados que está configurada para replicar todos os dados e alterações feitas no banco de dados principal. É uma réplica de leitura que está pronta para assumir o papel de banco de dados principal em caso de falha do banco de dados principal ou em caso de manutenção planejada.

A Standby Replica é criada com o objetivo de garantir a disponibilidade contínua do banco de dados principal e minimizar a interrupção dos serviços em caso de falhas ou interrupções. Quando uma falha é detectada na instância principal, a Standby Replica pode ser promovida para o papel de principal, permitindo que os usuários continuem a acessar e atualizar o banco de dados sem interrupções significativas.

A Standby Replica pode ser configurada como uma instância adicional em uma zona de disponibilidade diferente da instância principal, proporcionando maior resiliência em caso de falhas de zona. Além disso, a Standby Replica pode ser utilizada para fins de backup, permitindo que os dados sejam restaurados a partir de uma versão anterior, se necessário.

É importante destacar que a Standby Replica é uma instância de réplica de leitura, ou seja, ela não pode ser usada para fazer atualizações ou inserções no banco de dados. Ela serve apenas como uma cópia de segurança e como uma opção de failover em caso de problemas com a instância principal.

## AWS DynamoDB

SQL (Structured Query Language) e NoSQL (Not Only SQL) são dois tipos diferentes de bancos de dados. Embora ambos sejam usados para armazenar e recuperar dados, existem algumas diferenças fundamentais entre eles:

- Modelo de dados: O SQL é baseado em um modelo de dados relacional, onde os dados são organizados em tabelas com linhas e colunas. Já o NoSQL é baseado em um modelo de dados não relacional, onde os dados são armazenados em documentos, pares de chave-valor, grafos ou outras estruturas.
- Estrutura: O SQL é altamente estruturado, o que significa que a estrutura dos dados é definida antecipadamente e segue um esquema rígido. O NoSQL é mais flexível, permitindo que os dados sejam adicionados, modificados ou removidos sem precisar alterar o esquema.
- Escalabilidade: O SQL é geralmente dimensionado verticalmente, o que significa que o hardware é atualizado para lidar com mais dados ou tráfego. O NoSQL é dimensionado horizontalmente, o que significa que os dados são distribuídos em vários servidores para lidar com mais tráfego ou armazenar mais dados.
- Desempenho: O SQL é adequado para operações de leitura complexas, como junções e agregações. O NoSQL é mais adequado para operações de gravação em larga escala e leituras simples.
- Segurança: O SQL tem recursos de segurança integrados, como controle de acesso baseado em funções e autenticação. O NoSQL pode ter recursos de segurança limitados, embora muitos provedores de banco de dados NoSQL ofereçam opções de segurança avançadas.
- Custo: O SQL geralmente tem custos iniciais mais altos devido à necessidade de comprar hardware e software de banco de dados, além de exigir especialistas em banco de dados para gerenciar o ambiente. O NoSQL é geralmente mais barato, pois é baseado em serviços em nuvem gerenciados.

Em resumo, SQL e NoSQL são tipos diferentes de bancos de dados, cada um com suas próprias vantagens e desvantagens. A escolha entre SQL e NoSQL dependerá dos requisitos do projeto, como o modelo de dados, a escalabilidade, o desempenho e o orçamento.

### NoSQL

Bancos de dados NoSQL (Not Only SQL) são sistemas de gerenciamento de banco de dados que diferem dos bancos de dados relacionais tradicionais, que utilizam linguagem SQL (Structured Query Language) para realizar consultas e manipulação de dados.

Os bancos de dados NoSQL são projetados para lidar com grandes volumes de dados, com alta escalabilidade e desempenho, além de oferecerem flexibilidade na modelagem de dados e esquemas. Eles geralmente usam uma abordagem de armazenamento de dados não tabular, baseada em documentos, grafos ou colunas, para permitir a fácil expansão e manipulação de dados não estruturados ou semiestruturados.

| Característica | Banco de dados SQL | Banco de dados NoSQL |
| --- | --- | --- |
| Estrutura de dados | Possui estrutura de dados rigidamente definida | Possui estrutura de dados flexível |
| Escalabilidade | Escalabilidade vertical limitada | Escalabilidade horizontal fácil e sem limites |
| Consultas | Suporta consultas SQL complexas | Não suporta consultas SQL complexas |
| Armazenamento | Normalmente usa tabelas com linhas e colunas | Normalmente usa documentos, pares de chave-valor ou famílias de colunas |
| Transações | Suporta transações ACID (Atomicidade, Consistência, Isolamento, Durabilidade) | Normalmente suporta apenas transações básicas (por exemplo, inserção e exclusão de documentos) |
| Adequação para aplicativos | Bons para aplicativos que precisam garantir a integridade dos dados e/ou executar consultas complexas | Bons para aplicativos que exigem alta escalabilidade e/ou precisam armazenar grandes quantidades de dados não estruturados |
| Exemplos de serviços AWS | Amazon RDS, Amazon Aurora | Amazon DynamoDB, Amazon DocumentDB, Amazon Keyspaces |

### NoSQL Tipos

1. Bancos de Dados de Documentos: Os bancos de dados de documentos armazenam dados em documentos semiestruturados, como JSON ou XML, onde cada documento representa uma instância de um objeto. Eles permitem que os desenvolvedores armazenem dados com estrutura variável, em que cada documento pode ter um esquema diferente. Isso os torna adequados para aplicativos que precisam de flexibilidade no esquema de dados e escalabilidade. Alguns exemplos incluem MongoDB, Couchbase e Amazon DocumentDB.
2. Bancos de Dados de Colunas: Os bancos de dados de colunas armazenam dados em colunas em vez de linhas, permitindo melhor desempenho em operações de leitura e agregação. Eles são ideais para cenários em que o tempo de resposta é crítico, e quando há grande volume de dados e consulta de dados em larga escala. Exemplos incluem Apache Cassandra e Amazon Keyspaces.
3. Bancos de Dados de Grafos: Os bancos de dados de grafos armazenam dados em nós e arestas, permitindo a modelagem de dados complexos com relacionamentos. Eles são adequados para aplicativos que precisam de análise de dados, detecção de padrões, recomendadores e análise de redes sociais. Exemplos incluem Neo4j e Amazon Neptune.
4. Bancos de Dados Chave-Valor: Os bancos de dados chave-valor armazenam dados como pares chave-valor, permitindo acesso rápido aos dados. Eles são ideais para aplicativos que exigem escalabilidade, desempenho e baixa latência, como armazenamento em cache de sessões de usuários, gerenciamento de sessões e dados de perfil de usuário. Exemplos incluem Amazon DynamoDB e Redis.
5. Bancos de Dados de Objetos: Os bancos de dados de objetos armazenam objetos diretamente, sem que haja a necessidade de mapear para um modelo relacional. Eles são ideais para aplicativos que exigem escalabilidade, desempenho e baixa latência, como armazenamento em cache, gerenciamento de sessões, dados de perfil de usuário e outras aplicações. Exemplos incluem Oracle NoSQL Database e Amazon S3.
6. Bancos de Dados de Tempo de Série: Os bancos de dados de tempo de série armazenam dados em que cada registro possui um carimbo de data/hora. Eles são ideais para aplicativos que geram dados em tempo real, como sensores, servidores de IoT, dados de log e aplicações financeiras. Exemplos incluem Amazon Timestream e InfluxDB.

### Parallel Scan

A AWS Parallel Scan é um recurso disponível no Amazon DynamoDB que permite a leitura simultânea de várias partições de uma tabela em paralelo, aumentando a eficiência das operações de leitura e permitindo o processamento mais rápido de grandes volumes de dados.

Existem dois tipos de AWS

1. Parallel Scan: Standard Parallel Scan: nesse tipo de operação, cada processo de varredura paralela é executado em uma thread separada e pode ser configurado para ler de uma ou mais partições em uma tabela do DynamoDB. Isso permite a leitura simultânea de várias partições e pode melhorar significativamente o tempo de leitura de grandes quantidades de dados.
2. Segment Parallel Scan: nesse tipo de operação, o DynamoDB divide a tabela em segmentos e atribui a cada processo de varredura paralela um segmento específico para ler. Cada processo de varredura paralela é executado em uma instância separada, o que permite escalar verticalmente a operação de leitura de grandes volumes de dados. Essa técnica é especialmente útil quando se trata de tabelas com muitas partições ou quando é necessário processar grandes volumes de dados em um curto espaço de tempo.

# Monitoramento e Gerenciamento

## CloudTrail

Existem dois tipos de AWS CloudTrail:

1. AWS CloudTrail para serviços da AWS: este tipo de CloudTrail registra eventos de chamada de API para serviços da AWS, como Amazon S3, Amazon EC2, Amazon RDS, AWS Lambda, Amazon CloudFront, entre outros. O CloudTrail para serviços da AWS captura informações sobre a atividade do usuário, como quem iniciou a ação, o que foi feito, quando foi feito e qual endereço IP foi usado.
2. AWS CloudTrail para eventos do AWS Organization: este tipo de CloudTrail registra eventos de chamada de API para as contas da AWS em uma organização. Ele captura informações sobre a atividade do usuário, incluindo quem fez a ação, o que foi feito, quando foi feito e qual endereço IP foi usado. Isso pode ajudar a monitorar e rastrear atividades em várias contas AWS e em uma organização AWS.

Ambos os tipos de AWS CloudTrail permitem que os usuários monitorem a atividade da conta da AWS, solucionem problemas de conformidade e auditoria e identifiquem possíveis ameaças à segurança.

## CloudWatch

AWS CloudWatch é um serviço de monitoramento e observabilidade da AWS que coleta e rastreia métricas, logs e eventos em tempo real dos recursos em nuvem da AWS, como instâncias EC2, bancos de dados RDS, Lambda functions, entre outros. Ele fornece insights em tempo real sobre o desempenho dos recursos e permite que os usuários visualizem e analisem dados de monitoramento usando gráficos e alarmes.

Com o CloudWatch, os usuários podem monitorar a utilização de recursos, detectar anomalias e tomar medidas proativas para manter o desempenho e a disponibilidade dos recursos em alta. Além disso, o CloudWatch permite criar alarmes baseados em métricas para notificar quando determinadas condições são atendidas, como um aumento na utilização da CPU ou queda de conexões em um banco de dados.

O CloudWatch também integra com outros serviços da AWS, como o AWS Lambda, permitindo a coleta de logs de aplicativos e a monitoração de funções. Em resumo, o AWS CloudWatch é um serviço essencial para garantir a saúde e o desempenho dos recursos em nuvem da AWS.

## Pricing Calculator

O AWS Pricing Calculator é uma ferramenta da Amazon Web Services (AWS) que permite estimar o custo dos serviços da AWS antes de usá-los. Com o AWS Pricing Calculator, você pode criar estimativas de custos para serviços individuais ou combinações de serviços da AWS.

A ferramenta é útil para ajudar as empresas a entenderem quanto custará a utilização dos serviços da AWS e para planejarem seus orçamentos. Além disso, ela permite comparar os preços dos diferentes serviços da AWS e escolher a opção mais adequada.

Para usar o AWS Pricing Calculator, é necessário selecionar os serviços que você pretende usar e configurá-los de acordo com suas necessidades, como a região onde serão executados, a quantidade de recursos necessários e o tempo de uso. A ferramenta então calcula automaticamente o custo com base nas informações fornecidas.

Vale ressaltar que o AWS Pricing Calculator é apenas uma estimativa e que os preços reais podem variar dependendo de diversos fatores, como a demanda, a região geográfica, o tipo de instância escolhido e outros. Portanto, é sempre importante verificar a fatura real após a utilização dos serviços da AWS para confirmar os custos reais.

### PAYG

AWS Pay-As-You-Go (PAYG) é um modelo de pagamento da Amazon Web Services, em que o usuário paga somente pelos recursos de computação e serviços de nuvem que são utilizados. Essa modalidade de pagamento permite que o usuário tenha acesso aos recursos de computação da AWS sem precisar adquirir servidores e infraestrutura própria, o que reduz custos e aumenta a flexibilidade na gestão de recursos.

O AWS PAYG permite que o usuário pague somente pelo uso dos recursos de computação, como a capacidade de armazenamento, processamento, transferência de dados e outros serviços que são oferecidos pela plataforma de nuvem da Amazon. Dessa forma, o usuário pode reduzir custos ao utilizar os recursos apenas quando for necessário, sem precisar adquirir servidores e infraestrutura própria.

Além disso, o AWS PAYG também oferece a possibilidade de escalabilidade e flexibilidade, permitindo que o usuário aumente ou diminua os recursos de acordo com a demanda de trabalho e evite gastos desnecessários. Com isso, é possível ter mais controle e visibilidade sobre os custos e a gestão de recursos de computação na nuvem.

## AWS Datasync

AWS DataSync é um serviço de transferência de dados da AWS que facilita a transferência de grandes quantidades de dados entre sistemas de armazenamento on-premises e serviços de armazenamento na nuvem, como o Amazon S3, o Amazon EFS, entre outros. Ele permite transferir dados de forma rápida, segura e automatizada, reduzindo os tempos de transferência e minimizando os custos de largura de banda.

O AWS DataSync é projetado para suportar uma ampla gama de casos de uso, como backup, recuperação de desastres, migração de dados, compartilhamento de dados entre locais e muito mais. Ele oferece recursos avançados, como criptografia de dados em trânsito e em repouso, transferência de dados delta para reduzir a quantidade de dados transferidos, integração com IAM (Identity and Access Management), suporte para protocolos de transferência de dados padrão do setor, como NFS e SMB, e muito mais.

Em resumo, o AWS DataSync é uma ferramenta poderosa para simplificar a transferência de grandes quantidades de dados entre sistemas de armazenamento on-premises e serviços de armazenamento na nuvem, proporcionando maior eficiência, segurança e redução de custos.

## Life Cycle Hooks

AWS Lifecycle Hooks é um recurso disponível no AWS Elastic Compute Cloud (EC2) que permite aos usuários configurar scripts para serem executados automaticamente quando ocorre uma transição de estado em uma instância do EC2. As transições de estado incluem inicialização, terminação e paralisação.

Por meio do AWS Lifecycle Hooks, é possível adicionar scripts personalizados em pontos específicos do ciclo de vida de uma instância, permitindo que os usuários gerenciem os processos de inicialização, finalização e paralisação da instância de maneira mais eficiente. O recurso ajuda a garantir que os processos sejam concluídos com êxito antes da transição de estado da instância, minimizando os riscos de interrupção ou perda de dados.

Os usuários podem criar ganchos personalizados para executar ações personalizadas, como executar um script específico ou enviar uma mensagem para um serviço de notificação, quando uma instância é iniciada ou encerrada. Isso pode ajudar a gerenciar a carga de trabalho do servidor e a melhorar a eficiência da instância.

Em resumo, AWS Lifecycle Hooks é uma ferramenta útil que ajuda a gerenciar as transições de estado das instâncias do EC2 e automatizar tarefas personalizadas para garantir a eficiência e segurança de suas aplicações em nuvem.

## Well-Architected

O AWS Well-Architected é um conjunto de melhores práticas e diretrizes desenvolvidas pela Amazon Web Services para ajudar os clientes a criar arquiteturas seguras, eficientes e confiáveis na nuvem. O serviço oferece um framework que ajuda as organizações a avaliar e aperfeiçoar as arquiteturas de suas aplicações e sistemas, garantindo que eles estejam alinhados aos principais princípios de segurança, confiabilidade, eficiência, desempenho e custo-efetividade.

O AWS Well-Architected fornece uma metodologia para avaliar, planejar e otimizar arquiteturas de nuvem de acordo com cinco pilares: excelência operacional, segurança, eficiência de custos, desempenho e resiliência. O serviço também oferece ferramentas e recursos para ajudar os clientes a implementar essas melhores práticas, incluindo relatórios de avaliação, orientação de especialistas em AWS, e acesso a ferramentas de automatização e monitoramento.

Em resumo, o AWS Well-Architected é uma ferramenta poderosa para ajudar as organizações a criar e manter infraestruturas de nuvem seguras, escaláveis, eficientes e confiáveis, maximizando o valor dos investimentos em nuvem.

### Os 6 pilares

O AWS Well-Architected é um framework da Amazon Web Services (AWS) que ajuda os usuários a criar, projetar e manter arquiteturas de nuvem seguras, escaláveis, eficientes e resilientes. O framework é baseado em 6 pilares que fornecem diretrizes para projetar, construir e operar soluções na nuvem:

1. Segurança: garante a proteção dos dados e sistemas, seguindo as melhores práticas de segurança e compliance.
2. Confiabilidade: garante que os sistemas estejam sempre disponíveis e resistentes a falhas.
3. Eficiência de desempenho: garante que os recursos sejam usados de maneira eficiente para reduzir custos e maximizar a performance.
4. Excelência operacional: garante a automação e a gestão eficiente de operações de TI para aumentar a eficácia e reduzir custos.
5. Otimização de custos: garante que os recursos sejam usados de maneira econômica e que os custos sejam gerenciados com eficácia.
6. Arquitetura: garante que a arquitetura da solução seja escalável, flexível, e atenda às necessidades de negócios e de usuários.

Cada pilar contém um conjunto de práticas recomendadas e orientações para ajudar os usuários a criar e manter soluções na nuvem bem arquitetadas. O AWS Well-Architected pode ser usado como um guia para avaliar arquiteturas existentes ou para projetar novas soluções na nuvem.

| Pilar | Descrição |
| --- | --- |
| Excelência operacional | Foco em executar e monitorar sistemas para entregar valor ao negócio e aos clientes com eficiência e rapidez. Inclui a utilização de automação, melhoria contínua e práticas de gerenciamento de incidentes |
| Segurança | Foco em proteger informações e sistemas. Inclui o uso de controles de segurança, práticas de gerenciamento de identidade e acesso, criptografia e auditorias regulares |
| Confiabilidade | Foco em garantir que sistemas e aplicativos funcionem de maneira confiável e com capacidade de recuperação em caso de falhas. Inclui a utilização de tolerância a falhas, backup e recuperação de desastres |
| Eficiência de desempenho | Foco em utilizar recursos de forma eficiente para atender aos requisitos de desempenho e capacidade do sistema. Inclui a utilização de monitoramento e otimização de recursos, escalabilidade e uso de tecnologias adequadas |
| Otimização de custos | Foco em otimizar o uso de recursos e minimizar custos. Inclui o uso de monitoramento de custos, planejamento de capacidade e seleção de serviços e recursos adequados para o negócio |
| Arquitetura | Foco em criar sistemas flexíveis, escaláveis, seguros e eficientes. Inclui a utilização de padrões arquiteturais adequados, design modular, integração e desacoplamento de componentes e gerenciamento de mudanças |

### Highly Avaliby

AWS Highly Available (ou alta disponibilidade, em português) é um conjunto de práticas e soluções oferecidas pela Amazon Web Services (AWS) para garantir a continuidade dos serviços hospedados na plataforma, mesmo em situações de falhas ou interrupções.

A alta disponibilidade é alcançada por meio da redundância de recursos, replicação de dados e failover automático em caso de problemas. Isso significa que, se um servidor ou componente falhar, outro assume imediatamente, evitando qualquer interrupção ou perda de dados.

A AWS oferece uma ampla variedade de serviços que podem ser utilizados para construir uma infraestrutura altamente disponível, incluindo balanceadores de carga, grupos de autoescalonamento, banco de dados em várias zonas de disponibilidade, replicação de armazenamento, além de ferramentas de monitoramento e recuperação automatizada.

Ao garantir a alta disponibilidade em uma arquitetura de nuvem, as empresas podem oferecer aos seus usuários um serviço mais confiável, reduzir a possibilidade de perda de receita e manter a reputação da marca.

### Design for Failure

AWS Design for Failure é uma prática de design arquitetural na AWS que consiste em projetar e implementar sistemas que possam lidar com falhas de componentes individuais, permitindo que o sistema como um todo continue funcionando sem interrupções. Essa abordagem é baseada no conceito de que as falhas são inevitáveis e que é melhor se preparar para elas do que tentar evitá-las completamente.

Para implementar o AWS Design for Failure, os desenvolvedores da AWS usam técnicas como redundância, balanceamento de carga, monitoramento de desempenho e implementação de serviços em várias regiões geográficas. Com essas práticas, o sistema pode continuar operando mesmo que um ou mais componentes falhem.

A implementação do AWS Design for Failure é importante para garantir alta disponibilidade, escalabilidade e resiliência para aplicações na nuvem da AWS. Com essa abordagem, é possível garantir que o sistema continue operando mesmo em situações adversas, o que reduz o tempo de inatividade, melhora a experiência do usuário e ajuda a evitar perda de negócios.

### Embre Elasticy and Automation

AWS Elasticity and Automation é uma solução que permite gerenciar de forma eficiente e dinâmica a escalabilidade e a automação de recursos na nuvem da AWS. O objetivo do AWS Elasticity é ajustar automaticamente a capacidade dos recursos, como instâncias do EC2, de acordo com a demanda, garantindo que a infraestrutura esteja sempre disponível e com o desempenho esperado. Já o AWS Automation fornece recursos para automatizar tarefas de gerenciamento e manutenção de recursos na nuvem, como backups, atualizações e monitoramento de logs, por exemplo.

Essas soluções da AWS são ideais para empresas que precisam lidar com grandes volumes de tráfego ou processamento de dados, garantindo que a infraestrutura esteja sempre preparada para atender às demandas do negócio. Além disso, a automação de tarefas repetitivas ajuda a reduzir erros e aumentar a eficiência da equipe de TI. Em resumo, a AWS Elasticity and Automation é uma solução poderosa para aumentar a disponibilidade, escalabilidade e eficiência dos recursos na nuvem da AWS.

### Loosely Couple Components

AWS Loosely Coupled Components é um conceito utilizado na arquitetura de soluções em nuvem da AWS, que se refere à construção de sistemas compostos por componentes independentes e que possam operar de forma autônoma, sem depender uns dos outros.

Na prática, isso significa que os componentes de uma solução em nuvem são desenvolvidos e implantados separadamente, sem que haja um forte acoplamento entre eles. Cada componente é responsável por uma função específica e pode ser executado de forma independente, sem afetar o funcionamento dos outros componentes.

Esse modelo de arquitetura traz diversas vantagens, como maior flexibilidade, escalabilidade e resiliência, uma vez que é possível adicionar ou remover componentes conforme a necessidade, sem afetar o restante da solução. Além disso, o uso de componentes independentes facilita a manutenção e a atualização dos sistemas, tornando-os mais eficientes e econômicos.

Em resumo, a utilização de AWS Loosely Coupled Components é uma estratégia importante para criar soluções mais flexíveis, escaláveis e resistentes na nuvem.

# Integração e Segurança

## AWS Direct Connect

O AWS Direct Connect é um serviço de rede fornecido pela Amazon Web Services (AWS) que permite que as empresas estabeleçam uma conexão dedicada e privada entre sua infraestrutura de rede local e a nuvem da AWS. Com o AWS Direct Connect, as empresas podem transferir grandes volumes de dados de forma rápida, confiável e segura, reduzindo a latência e o custo de rede.

O AWS Direct Connect permite que as empresas estabeleçam conexões de rede dedicadas com a AWS, contornando a Internet pública e evitando possíveis gargalos de tráfego e problemas de segurança associados. As conexões do AWS Direct Connect são privadas e seguras, utilizando criptografia para proteger os dados em trânsito. Além disso, o AWS Direct Connect oferece baixa latência, o que é importante para aplicativos que exigem alta velocidade de transmissão de dados.

O AWS Direct Connect pode ser usado para uma ampla gama de casos de uso, incluindo migração de dados, backup e recuperação de desastres, processamento de big data, hospedagem de aplicativos, entre outros. Ele também é adequado para empresas que precisam transferir grandes quantidades de dados regularmente ou precisam de conectividade dedicada e privada para a AWS.

Em resumo, o AWS Direct Connect é uma solução de conectividade de rede dedicada e privada entre a infraestrutura de rede local e a nuvem da AWS. Ele permite transferir grandes volumes de dados de forma rápida e segura, reduzindo a latência e os custos de rede.

## IAM

O AWS Identity and Access Management (IAM) é um serviço da Amazon Web Services (AWS) que permite gerenciar com segurança o acesso a recursos da AWS. O IAM ajuda a controlar quem tem acesso aos recursos da AWS e como eles acessam esses recursos.

O serviço permite criar usuários, grupos e funções de acesso para permitir ou negar o acesso aos serviços e recursos da AWS. Os usuários do IAM podem ser autenticados por meio de várias fontes, como login e senha, credenciais temporárias, SAML 2.0, OpenID Connect e outras.

O IAM permite definir permissões granulares em nível de recurso, para que você possa controlar o que cada usuário pode fazer em um determinado serviço ou recurso. O IAM também oferece recursos de auditoria e monitoramento para ajudar a rastrear quem está fazendo o quê na sua conta da AWS.

Os benefícios do uso do AWS IAM incluem:

- Segurança: o IAM ajuda a garantir que apenas os usuários autorizados tenham acesso aos recursos da AWS.
- Gerenciamento de acesso: o IAM permite gerenciar facilmente quem tem acesso aos recursos da AWS e como eles acessam esses recursos.
- Flexibilidade: o IAM oferece várias opções de autenticação, autorização e gerenciamento de usuários para atender às suas necessidades específicas.
- Auditoria e monitoramento: o IAM fornece recursos para monitorar e auditar o acesso aos seus recursos da AWS para ajudar a garantir a conformidade com os requisitos regulatórios e de segurança.

Em resumo, o AWS IAM é uma solução para gerenciar o acesso aos serviços e recursos da AWS de maneira segura e eficiente, permitindo que as organizações controlem com precisão o acesso aos seus dados e recursos na nuvem.

## SRM

AWS SRM (AWS Systems Manager Resource Groups) é um serviço da AWS que permite criar, gerenciar e agrupar recursos em uma organização de acordo com critérios específicos, como tags, tipo, região, etc. Com o AWS SRM, é possível organizar e monitorar recursos da AWS em grande escala, além de facilitar a automação de tarefas e a gestão de políticas de segurança em ambientes complexos. O serviço também permite visualizar informações sobre a utilização e o desempenho dos recursos, além de simplificar a administração de políticas de compliance e auditoria. Em resumo, o AWS SRM é uma ferramenta poderosa para simplificar a gestão de recursos em nuvem, melhorar a produtividade e reduzir os custos de infraestrutura.

## Entities

AWS Entities é um serviço da AWS que ajuda a organizar recursos e entidades da AWS em uma única visualização, tornando mais fácil monitorar e gerenciar recursos de forma eficiente. O AWS Entities utiliza a aprendizagem automática para identificar e agrupar recursos com base em suas características, como tags, tipo de recurso, região, entre outras. Ele cria uma hierarquia de recursos e entidades, fornecendo uma visão geral de todos os recursos relacionados a uma entidade específica, como um aplicativo ou serviço. Dessa forma, o AWS Entities ajuda a simplificar a gestão de recursos em grande escala e permite uma melhor compreensão da infraestrutura de nuvem, aumentando a eficiência e a produtividade.

## MFA

AWS MFA (Multi-Factor Authentication) é um recurso de segurança da AWS que adiciona uma camada extra de autenticação ao processo de login do usuário. Com o MFA, o usuário precisará fornecer duas formas de autenticação para acessar a conta, geralmente uma senha e um código de autenticação temporário gerado por um dispositivo de segurança físico ou aplicativo móvel. Isso torna mais difícil para hackers ou pessoas mal-intencionadas acessarem uma conta comprometida, pois além de obter a senha, eles também precisariam ter acesso físico ao dispositivo de segurança ou ao aplicativo móvel. O uso do AWS MFA é altamente recomendado para aumentar a segurança das contas da AWS, especialmente para usuários com permissões de alto nível.

## Cross Account Access

AWS Cross-Account Access (Acesso Intercontas da AWS) é um recurso que permite que os usuários acessem recursos e serviços em contas AWS diferentes. Isso é útil para empresas que possuem várias contas na AWS e desejam compartilhar recursos entre elas, como arquivos, bancos de dados, servidores, entre outros.

Por meio do Cross-Account Access, é possível conceder permissões específicas para usuários em uma conta para acessar recursos em outras contas. Isso pode ser feito por meio do uso de políticas de IAM (Identity and Access Management), que controlam o acesso aos recursos na AWS.

Por exemplo, imagine uma empresa que possui uma conta na AWS para o departamento de TI e outra conta para o departamento financeiro. Com o Cross-Account Access, um usuário do departamento financeiro pode acessar um servidor na conta do departamento de TI para executar um aplicativo financeiro, sem precisar criar uma nova instância na sua própria conta.

O Cross-Account Access é um recurso seguro e escalável que ajuda as empresas a gerenciar de forma eficiente seus recursos na AWS, sem comprometer a segurança ou a conformidade.

## Granting Permission to AWS Services

AWS Granting Permission to AWS Services (Permitir a concessão de permissão aos serviços da AWS) é uma prática de segurança e gestão de acesso que permite que serviços específicos da AWS acessem recursos em sua conta da AWS. Por exemplo, você pode permitir que o serviço AWS Lambda acesse objetos no Amazon S3, ou que o serviço Amazon EC2 acesse um banco de dados Amazon RDS. Isso é feito através da criação de políticas de segurança específicas, que concedem permissões aos serviços da AWS para realizar ações específicas em seus recursos. Essas permissões podem ser gerenciadas centralmente através do AWS Identity and Access Management (IAM) e podem ser limitadas a ações específicas e recursos específicos, para garantir a segurança e evitar acesso não autorizado a recursos da AWS. Ao permitir a concessão de permissão aos serviços da AWS, você pode garantir que seus serviços possam funcionar de forma eficiente e segura, sem comprometer a segurança ou a integridade de seus recursos na AWS.

## Amazon Lex

O Amazon Lex é um serviço de reconhecimento de voz e processamento de linguagem natural da Amazon Web Services (AWS), que permite criar chatbots e interfaces de conversação para aplicativos, sites e dispositivos IoT.

O Amazon Lex utiliza tecnologias avançadas de inteligência artificial para entender e interpretar a linguagem natural e fornecer respostas precisas e personalizadas para os usuários. Ele suporta múltiplos canais de comunicação, como chat, voz e SMS, e pode ser integrado a outros serviços da AWS, como o Amazon S3, Amazon Lambda, Amazon DynamoDB, Amazon CloudWatch, entre outros.

Com o Amazon Lex, é possível criar chatbots para atendimento ao cliente, suporte técnico, vendas, entre outras finalidades, e personalizá-los de acordo com as necessidades da sua empresa. O serviço também oferece recursos avançados de gerenciamento e monitoramento, permitindo acompanhar as conversas em tempo real, analisar dados e otimizar o desempenho do chatbot.

## Access Analysis

AWS Access Analyzer é um serviço de análise de acesso que ajuda a identificar possíveis brechas de segurança em recursos da AWS. Ele utiliza técnicas de machine learning para analisar políticas de acesso e recomendar ações de segurança para garantir a conformidade com as políticas de segurança da organização. Com o AWS Access Analyzer, os usuários podem analisar políticas de acesso de S3, IAM e KMS e identificar possíveis erros ou configurações incorretas. O serviço também oferece relatórios de auditoria para rastrear e documentar atividades de acesso aos recursos da AWS. O AWS Access Analyzer é uma ferramenta essencial para garantir a segurança e conformidade dos recursos da AWS e proteger a organização contra potenciais ameaças cibernéticas.

## CDN e CloudFront

CDN (Content Delivery Network) é uma rede distribuída de servidores que são usados para fornecer conteúdo da internet, como imagens, vídeos, páginas da web e outros tipos de arquivos estáticos e dinâmicos, aos usuários finais. O objetivo principal de uma CDN é melhorar a velocidade e a confiabilidade da entrega de conteúdo, minimizando a latência e reduzindo a carga em um único servidor.

O Amazon CloudFront é o serviço de CDN da AWS que permite que os usuários entreguem conteúdo com baixa latência, alta transferência de dados e altamente disponível por meio de uma rede global de servidores distribuídos. Ele é altamente escalável e oferece recursos de segurança, como criptografia SSL/TLS e proteção contra ataques DDoS (Distributed Denial of Service).

O Amazon CloudFront é projetado para trabalhar em conjunto com outros serviços da AWS, como o S3 e o EC2, e pode ser usado para fornecer conteúdo dinâmico ou estático, incluindo vídeo sob demanda, transmissão ao vivo, páginas da web, APIs e muito mais.

Os usuários podem configurar o Amazon CloudFront para armazenar em cache o conteúdo em seus servidores globais e fornecê-lo aos usuários finais em todo o mundo de forma rápida e eficiente. Além disso, o Amazon CloudFront oferece recursos para monitorar a utilização e desempenho, permitindo que os usuários otimizem suas implantações de CDN e melhorem a experiência do usuário final.