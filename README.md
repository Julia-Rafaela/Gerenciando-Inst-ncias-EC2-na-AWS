EC2 – ELASTIC COMPUTE CLOUD são máquinas virtuais na AWS
Modelos IAAS
Existem vários tipos de instâncias EC2, entender a necessidade pra saber qual instância usar 
Escalando Vertical - acrescentar ou reduzir capacidade de um recurso em um mesmo nó e geralmente está relacionado a alterar o número de vCPUs, memória, storage, rede de uma instância 
Escalando Horizontamente - é quando você aumenta o número de recursos. Ex: adicionando mais um disco rígido, adicionando mais uma instancia para suportar a aplicação
Amazon EBS Elastic block store – é um armazenamento em nuvem, como se estivesse anexando um HD externo em qualquer instância EC2
Amazon S3 simple storege servece – recuso também de armazenamento de objetos(recursos) em nuvem, você apenas tem acesso ao recurso armazenando quando solicitado
Criação da imagem da máquina da Amazon (AMI)
Uma AMI (Amazon Machine Image) é uma imagem de máquina virtual pré-configurada, que inclui as informações necessárias para iniciar uma instância
Snapshots com EBS – é um serviço para fornecer armazenamento em bloco fiável (volumes ou discos rígidos). É um serviço de backup nativo do AWS que faz backup dos volumes do EBS em um determinado momento. São copias em pontos no tempo de um volume do Amazon EBS, armazenadas no Amazon S3
Meu exemplo:
Este diagrama representa a infraestrutura em nuvem de uma loja virtual que utiliza serviços da AWS (Amazon Web Services) para hospedar, armazenar e proteger seus dados.

