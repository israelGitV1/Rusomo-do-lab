# Principais Componentes e Arquiterura

## Regiões
- Pares
    - Para cada região
        - Priorização
        - Replicação de recursos
        - Recuperação 
- Soberanas
    - Distribuição Limitada e reservada
        - Militar  (EUA)
        - Gorverno (EUA)
        - China
            - 21 Vianet (Responsavel)     
## Zonas de Disponibilidade
 - são formadas por regiões que tem um grupo de Datacenters interligados e com redundancia de dados.
## Hierarquia
 - Assinaturas
 - Gerenciamento
 - Recursos 
## Recursos
 - Grupo de recursos 
    - organização
        - Maquinas 
        - Projetos
        - funções
        - Banco de dados
        - Regiões
        - Regras
    - limitações
        - não podem ser renomeadas
    - Vantagens
        - Pote movimentar recursos entre elas
        - O mesmo recurso não pode estar em dois grupos ao mesmo tempo
    
## Assinaturas
 - Conta Azure (main)
  - Um conta pode ter inímeras assinaturas ligadas à ela.
     - Assinaturas
         - Produção
             - Limites de Acesso
             - Direcionamento
             - Regras
         - Dezenvolvimento
             - Limites de Acesso
             - Direcionamento
             - Regras

## Gerenciamento
 - Herdam as condições aplicadas ou grupo gerenciado.
     - Regincia de grupos de chaves de assinaturas  
        - Grupos de recursos
        - Recursos 
        - Assinaturas
## Segurança
 - LGBD
    - Recursos que não podem sair do pais