# Computação e Rede

## Tipos de computação 
 - Máquina virtual
      - Precisa estár em execução para funcionar
      - Controle total sobre o SO (sistema operacional).
      - Capacidade para executar um software personalizado.
      - Usar configurações personalizadas de hospedagem.
      - Conjunto de escala de máquina virtual
      - Conjunto de disponibilidade de máquina virtual
      - Migrar para nuvem com VMs
        - Lift-and-shift : migração de um servidor físico para nuvem.
 - Instância de contêiner
      - Precisa estár em execução para funcionar
      - Contêineres geralmente são usados para criar soluções que utilizam uma arquitetura de microsserviço. 
      - Compatível com o Docker
      - Oferta de PaaS
      - Balanceamento de carga
      - Serviços Kuvernete (AKS)
      - Orquestração de contêiner
 - Funções
      - Não precisa estár em execução para funcionar
      - O Azure Functions é uma opção de computação sem servidor controlada por eventos que não requer a manutenção
      - O Azure Functions executa seu código quando ele é acionado e desaloca automaticamente os recursos quando a função é concluída. Nesse modelo, o Azure cobra apenas pelo tempo de CPU usado durante a execução da função.
 - Are de trabalho vitual
      - Aprimorar a segurança
        - Dados e aplicações na nuvem não tendo contanto com o computador local
        - Controle de acesso e permições.

## Hospedagem de aplicativos
 - Crie e hospede aplicativos Web
 - Sem gerenciar a infraestrutura
 - Balanceamento de carga interno e o gerenciador de tráfego fornecem alta disponibilidade
 - Compatível com o Windows e o Linux
 - Serviço com base em HTTP para hospedagem
 - Tipos de serviçõs de aplicativos 
     - Aplicativos Web
     - Aplicativos de API
     - WebJobs
       - Executar um script (.cmd, .bat, PowerShell ou Bash)
       - Programa (.exe, Java, PHP, Python ou Node.js) 
     - Aplicativos móveis
## Rede vituais
 - As redes virtuais e as sub-redes virtuais do Azure permitem que recursos do Azure, como VMs, aplicativos Web e bancos de dados, comuniquem-se uns com os outros, com usuários na Internet e com computadores cliente locais. Você pode pensar em uma rede do Azure como uma extensão de sua rede local com recursos que vinculam outros recursos do Azure.
     - Isolamento e segmentação
        - IP interno e externo 
        - DNS interno e externo
     - Comunicação pela Internet
     - Comunicação entre recursos do Azure
     - Comunicação com os recursos locais
     - Rotear tráfego de rede
      - O BGP (Border Gateway Protocol) funciona com Gateways de VPN do Azure, Servidor de Rota do Azure ou Azure ExpressRoute para propagar as rotas BGP locais para redes virtuais do Azure.
     - Filtrar tráfego de rede
     - Conectar redes virtuais
 - A rede virtual do Azure dá suporte a pontos de extremidade públicos e privados
     - Pontos de extremidade públicos têm um endereço IP público e podem ser acessados de qualquer lugar do mundo.
     - Pontos de extremidade privados existem em uma rede virtual e têm um endereço IP privado dentro do espaço de endereço dessa rede virtual.
 - Gateray de VPN
     - Tráfego criptografado entre redes vituais
 - ExpressRoute
     - Estenda suas redes locais para a nuvem da Microsoft (cabo fisico)
 - DNS do Azure
     - Serviço de hospedagem para domínios DNS
       - Confiabilidade e desempenho
       - Segurança
       - Facilidade de uso
       - Personalizar redes virtuais
       - Registros de alias
