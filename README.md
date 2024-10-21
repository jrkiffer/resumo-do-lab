# resumo-do-lab
Este repositorio é um resumo dos meus estudos sobre Azure na DIO






Descrever os conceitos da nuvem (25 a 30%)






Definir a computação em Nuvem

Computação em Nuvem é a entrega de serviços de computação por meio da internet, possibilitando uma inovação mais rápida, recursos flexíveis e economia de escala.
A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede. Os serviços de nuvem também expandem as ofertas tradicionais de TI para incluir itens como IoT (Internet das Coisas), ML (machine learning) e IA (inteligência artificial).
Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua infraestrutura de TI, não precisará esperar para construir um novo datacenter; você pode usar a nuvem para expandir rapidamente seu volume de TI.


Definir Modelos de Nuvem

Nuvem Privada
Uma nuvem privada é, de certa forma, a evolução natural de um datacenter corporativo. Ela é uma nuvem (que fornece serviços de TI pela Internet) usada por uma única entidade. A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. No entanto, ela também tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. Por fim, uma nuvem privada pode ser hospedada em seu datacenter local. Ela também pode ser hospedada em um datacenter dedicado externo, até mesmo por terceiros que tenham dedicado esse datacenter à sua empresa.
As organizações criam um ambiente em nuvem em seu Datacenter
A organização é responsável por operar os serviços que fornece.
Não fornece acesso aos usuários fora da organização.
O hardware deve ser adquirido para inicialização e manutenção.
As organizações tem controle total sobre recursos e segurança.
As organizações são responsáveis pelas atualizações e pela manutenção do hardware.

Nuvem Pública
Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas.
Pertencente a serviços de nuvem ou provedor de hosting (Azure, AWS, Google Cloud)
Fornece recursos a serviços a várias organizações e usuários.
Acessado via conexão de rede segura (geralmente pela internet).
Nenhuma despesa de capital para escalar verticalmente.
Os aplicativos podem ser rapidamente provisionados e desprovisionados.
As organizações pagam apenas pelo que usam.

Nuvem Híbrida
Uma nuvem híbrida é um ambiente de computação que usa nuvens públicas e privadas em um ambiente interconectado. Um ambiente de nuvem híbrida pode ser usado para permitir que uma nuvem privada escale para atender a uma demanda maior temporária implantando recursos de nuvem pública. A nuvem híbrida pode ser usada para fornecer uma camada adicional de segurança. Por exemplo, os usuários podem escolher com flexibilidade quais serviços manter na nuvem pública e quais implantar na infraestrutura de nuvem privada.
Combina as nuvens Publica e Privada para permitir que os aplicativos sejam executados no local mais apropriado.
Oferece a maior flexibilidade.
As organizações determinam onde executar seus aplicativos.
As organizações controlam os requisitos de segurança, conformidade ou jurídicos. 
 
Descrever o modelo de responsabilidade compartilhada:

Com o modelo de responsabilidade compartilhada, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem. O consumidor não fica na mesma localização do datacenter, portanto, não faria sentido que o consumidor tivesse algumas dessas responsabilidades.
Ao mesmo tempo, o consumidor é responsável pelos dados e pelas informações armazenados na nuvem. (Você não gostaria que o provedor de nuvem pudesse ler suas informações). O consumidor também é responsável pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.

Você sempre será responsável por:
•	Informações e dados armazenados na nuvem
•	Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
•	Contas e identidades das pessoas, serviços e dispositivos em sua organização
O provedor de nuvem é sempre responsável por:
•	Datacenter físico
•	Rede física
•	Hosts físicos

Seu modelo de serviço determinará a responsabilidade por coisas como:
•	Sistemas operacionais
•	Controles de rede
•	Aplicativos
•	Identidade e infraestrutura

Tipos de Cloud:

IAAS (Infrastructure as as servisse): Infraestrutura como serviço.
“Você como cliente pode alugar uma estrutura de TI de um provedor Cloud.
Servidores, VM, Storage”

PAAS (Platform as a Service): Plataforma como serviço.
S.O, Banco de Dados, Hospedagem de site

SAAS (Software as a Service): Software como serviço.
Acesso a aplicação, Gmail, Dropbox.

Descrever o modelo baseado em consumo  - CapEX/OpEX

Ao comparar modelos de infraestrutura de TI, há dois tipos de despesas a serem consideradas. CapEx (despesas de capital) e OpEx (despesas operacionais).
A CapEx normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
Ao contrário, a OpEx é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.
A computação em nuvem se enquadra na OpEx porque opera em um modelo baseado em consumo. Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. Se você não usar nenhum recurso de TI durante o mês, não pagará nada.
Um modelo baseado em consumo oferece vários benefícios, como:
•	Sem custos prévios.
•	Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
•	A capacidade de pagar para obter mais recursos quando necessário.
•	A capacidade de parar de pagar por recursos que não são mais necessários.
Com um datacenter tradicional, você tenta estimar as necessidades futuras de recursos. Se você superestimar, gastará mais do que o necessário no datacenter, podendo desperdiçar capital. Se você subestimar, o datacenter atingirá a capacidade rapidamente e os aplicativos e serviços poderão sofrer redução de desempenho. A correção de um datacenter subprovisionado pode ser muito demorada. Pode ser necessário solicitar, receber e instalar mais hardware. Você também precisará adicionar energia, resfriamento e rede para o hardware extra.
Em um modelo baseado em nuvem, você não precisa se preocupar em acertar perfeitamente as necessidades de recursos. Se você achar que precisa de mais máquinas virtuais, bastará adicioná-las. Se a demanda cair e você não precisar de tantas máquinas virtuais, bastará remover algumas, conforme o necessário. De qualquer forma, você só paga pelas máquinas virtuais que usa, não pela "capacidade extra" que o provedor de nuvem tem em mãos.

Beneficios da Nuvem

Alta disponibilidade:
A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
Escalabilidade:
A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
A escala geralmente vem em duas variedades: vertical e horizontal. A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. A escala horizontal é adição ou subtração do número de recursos.
Dimensionamento vertical
Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações de CPU ou RAM.
Dimensionamento horizontal
Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

Confiabilidade:
Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. Ela também é um dos pilares do Microsoft Azure Well-Architected Framework.
Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. Você pode criar aplicativos para aproveitar automaticamente essa confiabilidade maior. Em alguns casos, o próprio ambiente de nuvem mudará automaticamente para uma região diferente, sem que você precise realizar nenhuma ação
Previsibilidade:
A previsibilidade na nuvem permite que você avance com confiança. A previsibilidade pode se concentrar na previsibilidade de desempenho ou na previsibilidade de custo. Tanto a previsibilidade de desempenho quanto a de custo são bastante influenciadas pelo Microsoft Azure Well-Architected Framework. Implante uma solução criada em torno dessa estrutura e você terá uma solução cujo custo e desempenho são previsíveis.
Desempenho
A previsibilidade de desempenho se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho. Se de repente você precisar de mais recursos, o dimensionamento automático poderá implantar recursos adicionais para atender à demanda e depois reduzir a implantação quando a demanda cair. Ou se o tráfego estiver bem concentrado em uma área, o balanceamento de carga ajudará a redirecionar parte da sobrecarga para áreas menos sobrecarregadas.
Custo
A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem. Com a nuvem, você pode acompanhar o uso de recursos em tempo real, monitorar os recursos para garantir a maior eficiência de uso possível e aplicar a análise de dados para encontrar padrões e tendências que ajudam a planejar melhor as implantações de recursos. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.
Governança e Segurança:

Se você estiver implantando infraestrutura como serviço ou software como serviço, os recursos de nuvem vão dar suporte à governança e à conformidade. Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. Além disso, você pode atualizar todos os seus recursos implantados com novos padrões à medida que os padrões são alterados. A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
Em relação à segurança, você pode encontrar uma solução de nuvem que atenda às suas necessidades de segurança. Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
Benefícios da capacidade de gerenciamento na nuvem:

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
Gerenciamento da nuvem
O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
•	Escalar automaticamente a implantação de recursos com base na necessidade.
•	Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
•	Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
•	Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.
Gerenciamento na nuvem
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:
•	Por meio de um portal da Web.
•	Usando uma interface de linha de comando.
•	Usando APIs.
•	Usando o PowerShell.






Descrever a arquitetura e os serviços do Azure (35 a 40%)







Arquitetura e Serviços do Azure

1. Regiões do Azure, Pares de Regiões e Regiões Soberanas
•	Regiões do Azure: São locais geográficos onde os datacenters do Azure estão localizados. Cada região contém um ou mais datacenters.
O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem com mais de 60 regiões representando mais de 140 países.
As regiões são compostas de um ou mais datacenters muito próximos.
Fornecer flexibilidade e escala para reduzir a latência do cliente.
Preservar a residência de dados com uma oferta de conformidade abrangente.
•	Pares de Regiões: São pares de regiões dentro da mesma área geográfica que fornecem recuperação de desastres e alta disponibilidade. Exemplo: Leste dos EUA e Oeste dos EUA. 
•	No mínimo 300 milhas(480km) de separação entre pares de região.
•	Replicação automática para alguns serviços.
•	Recuperação de região priorizada em caso de interrupção.

•	Regiões Soberanas: São regiões que atendem a requisitos específicos de conformidade e regulamentação de um país. Exemplo: Azure Government nos EUA.
2. Zonas de Disponibilidade
•	Zonas de Disponibilidade: São locais fisicamente separados dentro de uma região do Azure. Cada zona tem sua própria fonte de energia, resfriamento e rede, garantindo alta disponibilidade e resiliência.
3. Datacenters do Azure
•	Datacenters do Azure: São instalações físicas que abrigam servidores e outros componentes de infraestrutura. Eles são projetados para fornecer serviços de nuvem com alta disponibilidade e segurança.
4. Recursos e Grupos de Recursos do Azure
•	Recursos: São instâncias de serviços que você cria, como máquinas virtuais, bancos de dados e redes.
•	Grupos de Recursos: São contêineres que mantêm recursos relacionados para facilitar a gestão e a organização.
5. Assinaturas
•	Assinaturas: São unidades de gerenciamento que agrupam recursos do Azure. Cada assinatura tem limites de cota e políticas de acesso.
6. Grupos de Gerenciamento
•	Grupos de Gerenciamento: São contêineres que ajudam a gerenciar várias assinaturas. Eles permitem aplicar políticas e controles de acesso de forma centralizada.




7. Hierarquia de Grupos de Recursos, Assinaturas e Grupos de Gerenciamento
•	Hierarquia: A estrutura hierárquica começa com grupos de gerenciamento no topo, seguidos por assinaturas e, finalmente, grupos de recursos. Isso ajuda a organizar e gerenciar recursos de forma eficiente.









Descrever os serviços de computação e rede do Azure











Descrever máquinas virtuais do Azure

Com as VMs (Máquinas Virtuais) do Azure, você pode criar e usar VMs na nuvem. As VMs fornecem IaaS (infraestrutura como serviço) na forma de um servidor virtualizado e podem ser usadas de várias maneiras. Como em um computador físico, você pode personalizar todos os programas de software em execução na VM. As VMs são uma opção ideal quando você precisa de:
•	Controle total sobre o SO (sistema operacional).
•	Capacidade para executar um software personalizado.
•	Usar configurações personalizadas de hospedagem.
• Máquinas Virtuais (VMs): Permitem criar e gerenciar VMs no Azure, oferecendo flexibilidade para executar uma variedade de sistemas operacionais e aplicativos.
• Escalabilidade Automática: Com os conjuntos de dimensionamento de VMs, você pode aumentar ou diminuir automaticamente o número de VMs com base na demanda.
• Serviços de Aplicativos: Incluem Azure App Services, que permitem criar, implantar e dimensionar aplicativos web e APIs rapidamente.

Uma VM do Azure oferece a flexibilidade da virtualização sem a necessidade de comprar e manter o hardware físico que a executa. No entanto, como uma oferta de IaaS, você ainda precisa configurar, atualizar e manter o software executado na VM.
Você pode até mesmo criar ou usar uma imagem já criada para provisionar rapidamente VMs. Você pode criar e provisionar uma VM em minutos quando seleciona uma imagem de VM pré-configurada. Uma imagem é um modelo usado para criar uma VM e pode já incluir um sistema operacional e outros softwares, como ferramentas de desenvolvimento ou ambientes de hospedagem na Web.

Dimensionar VMs no Azure

Você pode executar VMs únicas para teste, desenvolvimento ou para tarefas secundárias. Ou pode agrupar VMs para fornecer alta disponibilidade, escalabilidade e redundância. O Azure também pode gerenciar o agrupamento de VMs para você com recursos como conjuntos de dimensionamento e conjuntos de disponibilidade.
Conjuntos de escala de máquina virtual

Os Conjuntos de Dimensionamento de Máquinas Virtuais permitem criar e gerenciar um grupo de VMs idênticas e com balanceamento de carga. Se você simplesmente criou várias VMs com a mesma finalidade, precisará garantir que todas elas foram configuradas de modo idêntico e configurar parâmetros de roteamento de rede para garantir a eficiência. Você também precisa monitorar a utilização para determinar se precisa aumentar ou diminuir o número de VMs.
Em vez disso, com conjuntos de dimensionamento de máquinas virtuais, o Azure automatiza a maior parte desse trabalho. Os conjuntos de dimensionamento permitem que você gerencie, configure e atualize centralmente um grande número de VMs em minutos. O número de instâncias de VM pode aumentar ou diminuir automaticamente em resposta à demanda ou você pode defini-lo para uma escala com base em uma agenda definida. Os conjuntos de dimensionamento de máquinas virtuais também implantam automaticamente um balanceador de carga para garantir que seus recursos estejam sendo usados com eficiência. Com conjuntos de dimensionamento de máquinas virtuais, você pode criar serviços em grande escala para áreas como computação, big data e cargas de trabalho de contêiner.

Conjuntos de disponibilidade da máquina virtual

Os conjuntos de disponibilidade de máquinas virtuais são outra ferramenta para ajudá-lo a criar um ambiente mais resiliente e altamente disponível. Os conjuntos de disponibilidade foram projetados para garantir que as VMs escalonem atualizações e tenham conectividade de rede e energia variadas, impedindo que você perca todas as suas VMs com uma só falha de rede ou energia.
A disponibilidade atinge esses objetivos agrupando VMs de duas maneiras: domínio de atualização e domínio de falha.
•	Domínio de atualização: as VMs de grupos de domínio de atualização que podem ser reinicializadas ao mesmo tempo. Essa configuração permite aplicar atualizações sabendo que apenas um agrupamento de domínio de atualização está offline por vez. Todos os computadores em uma atualização de domínio de atualização. Um grupo de atualizações que passa pelo processo de atualização recebe um tempo de 30 minutos para se recuperar antes que a manutenção no próximo domínio de atualização seja iniciada.
•	Domínio de falha: o domínio de falha agrupa suas VMs por origem de energia comum e comutador de rede. Por padrão, um conjunto de disponibilidade divide suas VMs em até três domínios de falha. Isso ajuda a proteger contra uma falha de energia física ou de rede, tendo VMs em diferentes domínios de falha (portanto, sendo conectadas a diferentes recursos de energia e rede).
O melhor de tudo é que não há nenhum custo adicional para configurar um conjunto de disponibilidade. Você paga apenas pelas instâncias de VM criadas.
Exemplos de quando usar VMs
Alguns exemplos comuns ou casos de uso para máquinas virtuais incluem:
•	Durante o teste e o desenvolvimento. As VMs fornecem uma maneira rápida e fácil de criar diferentes configurações de sistema operacional e de aplicativo. A equipe de teste e desenvolvimento pode excluir facilmente as VMs quando não precisarem mais delas.
•	Ao executar aplicativos na nuvem. A capacidade de executar determinados aplicativos na nuvem pública, em vez de criar uma infraestrutura tradicional para executá-los, pode trazer benefícios econômicos substanciais. Por exemplo, um aplicativo pode precisar lidar com flutuações na demanda. Desligar VMs quando elas não são necessárias ou iniciá-las rapidamente para atender a um aumento repentino na demanda significa que você paga apenas pelos recursos que usa.
•	Ao estender seu datacenter para a nuvem: uma organização pode estender os recursos de sua própria rede local criando uma rede virtual no Azure e adicionando VMs a ela. Aplicativos como o SharePoint podem, então, ser executados em uma VM do Azure em vez de localmente. É mais fácil ou menos caro implantar dessa forma do que em um ambiente local.
•	Durante a recuperação de desastre: assim como acontece com a execução de determinados tipos de aplicativos na nuvem e com a extensão de uma rede local para a nuvem, você pode conseguir economias significativas usando uma abordagem baseada em IaaS para a recuperação de desastre. Se um datacenter primário falhar, você poderá criar VMs em execução no Azure para executar seus aplicativos críticos e desligá-los quando o datacenter primário ficar operacional novamente.
Migrar para a nuvem com VMs
As VMs também são uma excelente opção quando você migra de um servidor físico para a nuvem (também conhecido como lift-and-shift). Você pode criar uma imagem do servidor físico e hospedá-la em uma VM com poucas ou nenhuma alteração. Assim como um servidor local físico, você deve manter a VM: você é responsável por manter o sistema operacional e o software instalados.
Recursos da VM
Ao provisionar uma VM, você também terá a oportunidade de escolher os recursos associados a essa VM, incluindo:
•	Tamanho (finalidade, número de núcleos de processador e quantidade de RAM)
•	Discos de armazenamento (unidades de disco rígido, unidades de estado sólido etc.)
•	Rede (rede virtual, endereço IP público e configuração de porta)

Área de Trabalho Virtual do Azure

A Área de Trabalho Virtual do Azure é um serviço de virtualização de desktops e aplicativos que permite fornecer uma experiência completa do Windows em qualquer dispositivo. Ele oferece:

Escalabilidade e flexibilidade: Criar ambientes de desktop virtual escaláveis e flexíveis.
Segurança: Utilizar a segurança integrada do Azure para proteger seus dados e aplicativos.
Custo-benefício: Reduzir custos com recursos em pool de várias sessões e pague apenas pelo que usar.

Contêineres do Azure

Os Contêineres do Azure permitem que execute aplicativos em contêineres de forma eficiente e escalável. Principais serviços incluem:

Azure Kubernetes Service (AKS): Gerenciamento de clusters Kubernetes.
Azure Container Instances (ACI): Execução de contêineres sem a necessidade de gerenciar sevidores.
Azure Container Registry: Armazenamento e gerenciamento de imagens de contêineres

Azure Functions

O Azure Functions é um serviço de computação sem servidor que permite executar código sob demanda sem a necessidade de gerenciar a infraestrutura. Ele é ideal para:

Automatização de tarefas: Executar scripts e funções em resposta a eventos.
Escalabilidade automática: Escalar automaticamente com base na demanda.
Custo-efetividade: Pague apenas pelo tempo de execução do código.

Serviços de Aplicativos do Azure

Os Serviços de Aplicativos do Azure permitem criar, implantar e escalar aplicativos web e APIs rapidamente. Eles oferecem:

Suporte a várias linguagens: .NET, Java, Node.js, Python, entre outras.
Integração contínua: Ferramentas de DevOps para integração e entrega contínuas.
Escalabilidade e segurança: Escale seus aplicativos facilmente e proteja-os com recursos de segurança integrados.







Descrever os serviços do armazenamento do Azure







Opções de Redundância e Serviços de Armazenamento
•	Redundância: O Azure oferece várias opções de redundância para garantir a alta disponibilidade e durabilidade dos dados. As opções incluem:
o	Locally Redundant Storage (LRS): Mantém três cópias dos dados dentro de uma única região.
o	Zone-Redundant Storage (ZRS): Armazena dados em diferentes zonas de disponibilidade dentro da mesma região.

Opções de Gerenciamento de Arquivo

•	Azure Files: Serviço de compartilhamento de arquivos totalmente gerenciado, acessível via SMB (Server Message Block) e NFS (Network File System).
O armazenamento dos Arquivos do Azure oferece compartilhamento de arquivo totalmente gerenciado na nuvem e acessível por meio do protocolo SMB ou NFS (Network File System) padrão do setor. Os compartilhamentos de Arquivos do Azure podem ser montados de maneira simultânea por implantações locais ou na nuvem. É possível acessar os compartilhamentos de Arquivos do Azure do protocolo SMB em clientes Windows, Linux e macOS. É possível acessar os compartilhamentos de Arquivos do Azure do protocolo NFS em clientes Linux e macOS. Além disso, os compartilhamentos de Arquivos do Azure do protocolo SMB podem ser armazenados em cache nos Windows Servers com a Sincronização de Arquivos do Azure para acesso rápido perto de onde os dados estão sendo usados.
•	Azure Blob Storage: Armazenamento de objetos otimizado para grandes quantidades de dados não estruturados, como documentos, imagens e vídeos.
O armazenamento de Blobs do Azure é uma solução de armazenamento de objetos para a nuvem. Ele pode armazenar grandes quantidades de dados, como texto ou dados binários. O armazenamento de Blobs do Azure não é estruturado, o que significa que não há nenhuma restrição quanto aos tipos de dados que ele pode armazenar. O armazenamento de Blobs pode gerenciar milhares de carregamentos simultâneos, grandes quantidades de dados de vídeo, arquivos de log em constante crescimento e pode ser acessado de qualquer lugar com uma conexão com a Internet.
Os blobs não estão limitados a formatos de arquivo comuns. Um blob pode conter gigabytes de dados binários transmitidos de um instrumento científico, uma mensagem criptografada para outro aplicativo ou dados em um formato personalizado para um aplicativo que você está desenvolvendo. Uma vantagem do Armazenamento de Blobs em relação ao Armazenamento em Disco é que ele não exige que os desenvolvedores pensem em discos e nem os gerenciem. Os dados são carregados como blobs e o Azure cuida das necessidades de armazenamento físico.
O armazenamento de Blobs é ideal para:
•	Fornecimento de imagens ou de documentos diretamente a um navegador.
•	Armazenamento de arquivos para acesso distribuído.
•	Transmissão por streaming de áudio e vídeo.
•	Armazenamento de dados de backup e restauração, recuperação de desastres e arquivamento.
•	Armazenamento de dados para análise por um serviço local ou hospedado no Azure.

•	Azure Data Box: Solução para transferir grandes quantidades de dados para o Azure usando dispositivos físicos.

Filas do Azure
O Armazenamento de Filas do Azure é um serviço usado para armazenar grandes quantidades de mensagens. Após o armazenamento, você pode acessar as mensagens em qualquer lugar do mundo por meio de chamadas autenticadas usando HTTP ou HTTPS. Uma fila pode conter a quantidade de mensagens que couber na sua conta de armazenamento (possivelmente milhões). Cada mensagem individual pode ter até 64 KB de tamanho. As filas são normalmente usadas para criar uma lista de pendências de trabalho para processamento assíncrono.
O Armazenamento de Filas pode ser combinado com funções de computação, como o Azure Functions, para executar uma ação quando uma mensagem é recebida. Por exemplo, você quer que uma ação seja executada depois que um cliente carregar um formulário no site. Você pode fazer com que o botão Enviar no site dispare uma mensagem para o Armazenamento de Filas. Depois, você pode usar o Azure Functions para disparar uma ação quando a mensagem for recebida.

Tabelas do Azure
O Armazenamento de Tabelas do Microsoft Azure armazena grandes quantidades de dados estruturados. As tabelas do Azure são um repositório de dados NoSQL que aceita chamadas autenticadas de dentro e de fora da nuvem do Azure. Isso permite que você use tabelas do Azure para criar sua solução híbrida ou de várias nuvens e ter seus dados sempre disponíveis. As tabelas do Azure são ideais para armazenar dados estruturados não relacionais.

Pontos de Extremidades Públicos e Privados

•	Pontos de Extremidade Públicos: Permitem que os serviços de armazenamento do Azure sejam acessados pela internet. São usados para cenários onde os dados precisam ser acessíveis externamente.
•	Pontos de Extremidade Privados: Permitem que os serviços de armazenamento sejam acessados de forma segura dentro da rede virtual do Azure, sem expor os dados à internet pública.

Camadas de armazenamento

Os dados armazenados na nuvem aumentam em ritmo exponencial. Para gerenciar os custos de suas necessidades de armazenamento em expansão, pode ser útil organizar seus dados com base na frequência com que eles serão acessados e por quanto tempo eles serão retidos. O Armazenamento do Azure oferece diferentes camadas de acesso para que você possa armazenar seus dados de blob da maneira mais econômica com base em como eles estão sendo usados. As camadas de acesso do Armazenamento do Azure incluem:
•	Camada quente – uma camada online otimizada para armazenar dados acessados ou modificados com frequência. A camada quente tem os custos de armazenamento mais altos, mas os custos de acesso mais baixos.
•	Camada fria – uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência. Os dados na camada de acesso esporádico devem ser armazenados por um mínimo de 30 dias. A camada fria tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada quente.
•	Camada de acesso frio: uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência, mas que ainda exigem uma recuperação rápida. Os dados na camada acesso frio devem ser armazenados por um mínimo de 90 dias. A camada de acesso frio tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada de acesso esporádico.
•	Camada de arquivos: uma camada offline otimizada para armazenar dados acessados raramente e com requisitos de latência flexíveis, na ordem de horas. Os dados na camada de arquivos devem ser armazenados por um mínimo de 180 dias.


Migração para o Azure

•	Azure Site Recovery: Usado para replicar, proteger e recuperar máquinas virtuais e servidores físicos para o Azure.

Migrações para Azure
•	Azure Migrate: É uma ferramenta centralizada que ajuda a avaliar e migrar cargas de trabalho para o Azure. Oferece suporte para migração de servidores, bancos de dados, aplicativos e dados.
•	Suas principais funcionalidades incluem:
o	Descoberta e Avaliação: Permite descobrir e avaliar servidores, bancos de dados, aplicativos e dados no ambiente local.
o	Migração de Servidores: Suporta a migração de servidores físicos, VMware, Hyper-V e outros provedores de nuvem para o Azure.
o	Migração de Bancos de Dados: Facilita a migração de bancos de dados SQL Server, MySQL, PostgreSQL e outros para o Azure SQL Database ou Azure Database for MySQL/PostgreSQL.
o	Migração de Aplicativos Web: Ajuda a migrar aplicativos web para o Azure App Service.
o	Migração de Áreas de Trabalho Virtuais: Suporta a migração de desktops virtuais para o Azure Virtual Desktop.
Azure Data Box
•	Azure Data Box: É uma solução para transferir grandes quantidades de dados para o Azure usando dispositivos físicos. Existem diferentes variantes do Data Box:
o	Data Box: Um dispositivo robusto que pode transferir até 80 TB de dados.
o	Data Box Disk: Discos SSD que podem transferir até 8 TB de dados por disco, ideal para transferências menores.
o	Data Box Heavy: Um dispositivo maior que pode transferir até 1 PB de dados, adequado para grandes volumes de dados.

O AzCopy é uma ferramenta de linha de comando usada para transferir dados de e para o Armazenamento do Microsoft Azure. Com o AzCopy, você pode copiar ou mover blobs, arquivos e até mesmo tabelas entre contas de armazenamento no Azure. Aqui estão algumas funcionalidades principais:
Transferência de Dados: Permite copiar dados de, para ou entre contas de armazenamento do Azure.
Autorização: Suporta várias formas de autenticação, incluindo chaves de conta, SAS (Shared Access Signatures) e identidades gerenciadas.
Desempenho: Otimizado para transferências rápidas e eficientes, suportando operações em massa e paralelas.
Flexibilidade: Pode ser usado em diferentes sistemas operacionais, incluindo Windows, Linux e macOS.
Sincronização em uma direção.

Gerenciador de Armazenamento do Azure
Interface gráfica do usuário (de modo semelhante ao Windows Explorer).
Compatível com Windows, MacOS e Linux.
Sincronização de Arquivos do Azure
Sincroniza os arquivos do Azure e locais de forma bidirecional
A camada de nuvem mantém os arquivos acessados com frequência no local, enquanto libera espaço.





Identidade, Acesso e Segurança







Microsoft Entra ID: Anteriormente conhecido como Azure Active Directory, é um serviço de gerenciamento de identidades e acessos baseado em nuvem. Ele oferece autenticação e autorização para serviços como Microsoft 365, Dynamics 365 e Azure. Funcionalidades incluem logon único (SSO), autenticação multifator (MFA) e acesso condicional.

Microsoft Entra Domain Services: Fornece serviços de domínio gerenciados, como ingresso no domínio do Windows, políticas de grupo e LDAP, sem a necessidade de implantar, gerenciar ou aplicar patches a controladores de domínio.

Métodos de Autenticação no Azure

SSO (Logon Único): Permite que os usuários acessem vários aplicativos com uma única credencial de login, simplificando a experiência do usuário e aumentando a segurança.

MFA (Autenticação Multifator): Adiciona uma camada extra de segurança, exigindo que os usuários forneçam dois ou mais métodos de verificação, como senha e um código enviado para o celular.

Autenticação Sem Senha: Utiliza métodos como biometria (impressão digital, reconhecimento facial) ou chaves de segurança FIDO2 para autenticar usuários sem a necessidade de uma senha.

Identidades Externas e Acesso de Convidado no Azure

Identidades Externas: Permitem que usuários de fora da organização acessem recursos de forma segura. Isso inclui parceiros, clientes e consumidores que podem usar suas próprias identidades, como contas de redes sociais ou corporativas.

Acesso de Convidado: Permite que convidados externos colaborem com a organização, oferecendo acesso controlado a recursos específicos. Isso é gerenciado através do Microsoft Entra ID.

Acesso Condicional do Entra

Acesso Condicional: É uma ferramenta que aplica políticas de acesso baseadas em condições específicas, como localização, dispositivo ou risco de login. Ele ajuda a garantir que apenas usuários autorizados e em conformidade possam acessar recursos sensíveis.

Controle de Acesso Baseado em Função (RBAC)

RBAC: Permite gerenciar permissões de acesso refinadas para recursos do Azure, atribuindo funções específicas a usuários, grupos ou aplicativos. Isso simplifica o gerenciamento de permissões e aumenta a segurança.

Conceito de Confiança Zero

Confiança Zero: Modelo de segurança que assume que nenhuma entidade, seja dentro ou fora da rede, é confiável por padrão. Ele exige verificação contínua de identidade e contexto antes de conceder acesso a recursos.

Finalidade do Modelo de Defesa em Profundidade

Defesa em Profundidade: Estratégia de segurança que utiliza várias camadas de defesa para proteger dados e recursos. Cada camada serve como uma barreira adicional contra ataques, aumentando a resiliência geral do sistema.

Finalidade do Microsoft Defender para Nuvem

Microsoft Defender para Nuvem: Oferece visibilidade e controle sobre a segurança dos recursos no Azure. Ele ajuda a identificar e mitigar ameaças, além de fornecer recomendações de segurança para melhorar a postura de segurança da organização.







Gerenciamento de Custos









Fatores que Podem Afetar os Custos no Azure

Os custos no Azure podem ser influenciados por diversos fatores, incluindo:

•	Tipo de Serviço: Diferentes serviços têm diferentes estruturas de preços. Por exemplo, o custo de uma máquina virtual pode variar dependendo do tipo de instância e da região.
•	Uso de Recursos: A quantidade de recursos consumidos, como CPU, memória e armazenamento, impacta diretamente os custos.
•	Localização Geográfica: Os preços podem variar entre diferentes regiões do Azure.
•	Nível de Serviço: Serviços com maior disponibilidade e suporte podem ter custos mais elevados.
•	Descontos e Ofertas: Programas como Instâncias Reservadas e o Benefício Híbrido do Azure podem reduzir os custos.

Azure Marketplace

O Azure Marketplace permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos e serviços de centenas de provedores de serviços líderes, que são todos certificados para execução no Azure.
O Azure Marketplace é uma plataforma online onde você pode encontrar, experimentar, comprar e implantar milhares de aplicativos e serviços que são otimizados para rodar no Microsoft Azure. Ele oferece uma ampla variedade de soluções, desde software de código aberto até aplicativos comerciais, que podem ajudar a acelerar o desenvolvimento, economizar tempo e dinheiro, e inovar mais rapidamente com soluções pré-construídas.

Principais Funcionalidades do Azure Marketplace:

•	Variedade de Aplicativos: Inclui uma vasta gama de aplicativos e serviços, como imagens de máquinas virtuais, soluções de segurança, redes, armazenamento, bancos de dados e muito mais.
•	Consultoria e Serviços: Além de software, o Marketplace também oferece serviços de consultoria para ajudar na adoção e implementação de soluções no Azure.
•	Certificação e Otimização: Todos os aplicativos e serviços disponíveis são certificados e otimizados para execução no Azure, garantindo desempenho e segurança.
•	Facilidade de Implantação: Permite a implantação rápida e confiável de soluções de ponta a ponta diretamente no ambiente do Azure.

Benefícios do Azure Marketplace:

•	Aceleração do Desenvolvimento: Com acesso a soluções pré-construídas, você pode acelerar o desenvolvimento de seus projetos.
•	Economia de Tempo e Dinheiro: Ao utilizar soluções prontas, você reduz o tempo e os custos associados ao desenvolvimento e manutenção de software.
•	Inovação: A plataforma facilita a inovação, permitindo que você experimente novas tecnologias e soluções de forma rápida e segura.


Comparação entre a Calculadora de Preços e a Calculadora de Custo Total de Propriedade (TCO)

•	Calculadora de Preços: Ferramenta que permite estimar os custos mensais ou por hora dos serviços do Azure com base no uso previsto. É útil para planejar e orçar novos projetos no Azure.

•	Calculadora de Custo Total de Propriedade (TCO): Ferramenta que ajuda a calcular as economias potenciais ao migrar cargas de trabalho para o Azure. Considera custos de infraestrutura, energia, manutenção e outros fatores para fornecer uma visão abrangente do custo total de propriedade.

Ferramenta de Gerenciamento de Custos do Azure

A Ferramenta de Gerenciamento de Custos do Azure permite que as organizações monitorem, analisem e otimizem seus gastos na nuvem. Com ela, é possível:

•	Analisar Custos: Visualizar e analisar os custos detalhados por assinatura, grupo de recursos ou tipo de recurso.
•	Definir Orçamentos: Estabelecer orçamentos e receber alertas quando os gastos se aproximarem ou excederem os limites definidos.
•	Alocar Custos: Atribuir custos a diferentes departamentos ou projetos para melhor controle financeiro.

Finalidade das Marcas (TAGS)

As marcas (tags) no Azure são usadas para organizar e gerenciar recursos de forma eficiente. Elas permitem:

•	Classificação: Categorizar recursos para facilitar a busca e a organização.
•	Gerenciamento de Custos: Atribuir custos a projetos específicos, departamentos ou equipes.
•	Automação: Utilizar tags em scripts e automações para gerenciar recursos de forma dinâmica.



Descrever os recursos e ferramentas de governança e conformidade no Azure


Azure Blueprints

Azure Blueprints permite que você defina um conjunto de recursos, políticas e outros artefatos que podem ser reutilizados para criar e gerenciar ambientes consistentes e conformes. Ele ajuda a garantir que as implantações estejam alinhadas com os padrões organizacionais e requisitos de conformidade. Além disso, os Blueprints podem incluir bloqueios de recursos para evitar alterações indesejadas.

Azure Policy

Azure Policy é uma ferramenta que permite criar, atribuir e gerenciar políticas que aplicam regras e efeitos sobre os recursos do Azure. O objetivo é garantir que os recursos estejam em conformidade com os padrões corporativos e regulatórios. Por exemplo, você pode usar o Azure Policy para garantir que apenas tipos específicos de máquinas virtuais sejam criados ou que todos os recursos tenham tags apropriadas.

Bloqueios de Recursos

Os bloqueios de recursos no Azure são usados para impedir que recursos críticos sejam excluídos ou modificados acidentalmente. Existem dois tipos principais de bloqueios: “Não Excluir” e “Somente Leitura”. O bloqueio “Não Excluir” impede a exclusão de um recurso, enquanto o bloqueio “Somente Leitura” impede qualquer modificação.

Portal de Confiança do Serviço

O Portal de Confiança do Serviço (Service Trust Portal) fornece informações detalhadas sobre a conformidade do Azure com vários padrões regulatórios e de segurança. Ele oferece acesso a relatórios de auditoria, guias de conformidade e outros documentos que ajudam as organizações a entender como o Azure atende aos requisitos de conformidade e segurança.



Descrever os recursos e ferramentas para gerenciar e implantar recursos do Azure



Portal do Azure

O Portal do Azure é uma interface web unificada que permite gerenciar e visualizar todos os seus recursos do Azure. Ele oferece uma experiência gráfica intuitiva para criar, configurar e monitorar serviços e recursos. Com o Portal do Azure, você pode realizar tarefas como a criação de máquinas virtuais, configuração de redes virtuais e monitoramento de desempenho de aplicativos, tudo em um único lugar.

Azure Cloud Shell

O Azure Cloud Shell é um terminal baseado em navegador que fornece um ambiente de linha de comando autenticado para gerenciar recursos do Azure. Ele suporta dois tipos de shell: Bash e PowerShell. O Cloud Shell inclui ferramentas como a CLI do Azure e o Azure PowerShell, permitindo que você execute comandos para criar, configurar e gerenciar recursos do Azure diretamente do navegador.

CLI do Azure: Uma interface de linha de comando multiplataforma que permite gerenciar recursos do Azure usando comandos simples e diretos.
Azure PowerShell: Um módulo do PowerShell que fornece cmdlets para gerenciar recursos do Azure, ideal para automação de tarefas administrativas.

Azure Arc

O Azure Arc estende os serviços e a gestão do Azure para qualquer infraestrutura, seja on-premises, na borda ou em outras nuvens. Ele permite que você gerencie servidores, clusters de Kubernetes e serviços de dados como se estivessem no Azure. O Azure Arc facilita a governança e a segurança centralizadas, além de permitir a implementação de práticas DevOps em ambientes híbridos e multinuvem.

Azure Resource Manager (ARM) e Modelos do ARM

O Azure Resource Manager (ARM) é o serviço de gerenciamento de implantação do Azure. Ele fornece uma camada de gerenciamento que permite criar, atualizar e excluir recursos em sua conta do Azure. Com o ARM, você pode gerenciar seus recursos como um grupo, chamado de grupo de recursos, e aplicar políticas, tags e controle de acesso a esses grupos.

Os Modelos do ARM são arquivos JSON que definem a infraestrutura e a configuração do seu projeto. Eles permitem a implantação declarativa de recursos, garantindo que a infraestrutura seja configurada de maneira consistente e repetível. Os modelos ARM são idempotentes, o que significa que você pode implantá-los várias vezes com os mesmos resultados.


Descrever as ferramentas de monitoramento no Azure


Assistente do Azure
O Assistente do Azure é uma ferramenta que fornece recomendações personalizadas para ajudar a otimizar seus recursos do Azure em termos de confiabilidade, segurança, excelência operacional, desempenho e custo. Ele analisa suas configurações e uso do Azure e sugere ações que você pode tomar para melhorar a eficiência e reduzir custosa.

Integridade do Serviço do Azure
A Integridade do Serviço do Azure (Azure Service Health) mantém você informado sobre incidentes de serviço e manutenção planejada que podem afetar seus recursos do Azure. Ele fornece alertas personalizados e diretrizes para ajudar a mitigar o impacto de problemas de serviço. Você pode configurar alertas para receber notificações por email, SMS, notificações push, webhook e outras ferramentas de gerenciamento de serviços de TI.

Azure Monitor
O Azure Monitor é uma solução abrangente para coletar, analisar e agir sobre dados de monitoramento de seus ambientes de nuvem e locais. Ele ajuda a maximizar a disponibilidade e o desempenho de seus aplicativos e serviços. O Azure Monitor inclui várias ferramentas:

Log Analytics: Permite coletar e analisar dados de logs de todos os seus recursos do Azure. Você pode criar consultas personalizadas para obter insights detalhados sobre a integridade e o desempenho dos seus recursos.
Alertas do Azure Monitor: Permitem configurar notificações para eventos específicos, como quando uma métrica atinge um limite definido. Isso ajuda a responder rapidamente a problemas antes que eles afetem seus usuários.
Application Insights: Uma ferramenta de monitoramento de desempenho de aplicativos (APM) que fornece insights detalhados sobre a integridade e o desempenho de seus aplicativos web. Ele permite rastrear solicitações, exceções, dependências e muito mais, ajudando a identificar e resolver problemas rapidamente.

