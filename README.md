# virtual_machine_Azure

1. Como a Computação em Nuvem Funciona
📄 Resumo
A computação em nuvem permite o acesso sob demanda a recursos computacionais via internet.

Ao invés de investir em infraestrutura física, as empresas alugam capacidade computacional conforme a necessidade.

Serviços são oferecidos por provedores de nuvem como Microsoft Azure, AWS e Google Cloud.

Os principais modelos de entrega:

IaaS (Infraestrutura como Serviço): aluguel de servidores, VMs, redes.

PaaS (Plataforma como Serviço): ambiente para desenvolvimento de aplicações.

SaaS (Software como Serviço): softwares prontos (como Office 365).

🖊️ Anotações
O usuário não precisa se preocupar com a manutenção física dos servidores.

A cobrança geralmente é feita no modelo pay-as-you-go (pagamento pelo uso).

💡 Dicas
Comece testando máquinas virtuais para entender como o modelo de infraestrutura funciona na prática.

Use a Azure Free Account para experimentar sem custo inicial.

2. Introdução à Computação em Nuvem
📄 Resumo
Computação em nuvem é a entrega de serviços de TI como armazenamento, bancos de dados, servidores e redes pela internet ("a nuvem").

Elimina a necessidade de comprar, possuir e manter datacenters físicos.

🖊️ Anotações
Três características principais da nuvem:

Elasticidade: capacidade de aumentar ou reduzir recursos conforme a demanda.

Acesso global: serviços disponíveis em qualquer lugar com internet.

Modelo baseado em consumo: você paga apenas pelo que usar.

💡 Dicas
Escolha a região do Azure mais próxima dos seus usuários para reduzir latência.

Explore serviços de gravação automática e replicação para maior segurança dos dados.

3. Benefícios da Computação em Nuvem
📄 Resumo
Economia de custos: sem investimentos em hardware ou infraestrutura física.

Escalabilidade: ajuste fácil de recursos de acordo com o crescimento ou queda da demanda.

Desempenho: acesso a hardware de última geração gerenciado por especialistas.

Segurança: nuvem oferece mecanismos de segurança avançados, como criptografia e controle de acesso.

Agilidade: implantação de aplicações e serviços em minutos.

🖊️ Anotações
A nuvem acelera o tempo de colocação no mercado de novos produtos e serviços.

Azure investe bilhões de dólares em segurança anualmente.

💡 Dicas
Utilize as ferramentas de monitoramento do Azure para acompanhar a performance dos recursos.

Considere o Azure Advisor para sugestões de melhoria de custo, desempenho e segurança.

!!!!Exemplo Prático: Criando uma Máquina Virtual no Azure
Acesse o Portal Azure.

Vá para Máquinas Virtuais > Adicionar > Máquina Virtual.

Preencha:

Nome da VM (ex: vm-exemplo),

Região (ex: Brazil South),

Imagem (ex: Windows Server 2022),

Tamanho da VM.

Configure o usuário administrador e a senha.

Revise as configurações e clique em Criar.

Após criada, você pode acessar a VM via RDP usando o IP público gerado.
