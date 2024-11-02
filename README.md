# Grupo de Estudos em Inteligência Artificial (GEIA) / Universidade de Fortaleza
Grupo de Estudos em Otimização em Grafos - Prof. Me. Ricardo Carubbi

## Fonte dos Dados: Rede de Transporte Aérea

Os dados utilizados são provenientes de um repositório chamado OpenFlights especializado em armazenar e disponibilizar informações de voos, aeroportos e rotas aéreas.

Cada linha do arquivo `routes.dat` representa uma rota entre dois aeroportos e geralmente possui o seguinte formato:

| Companhia Aérea | ID Companhia | Aeroporto de Origem | ID Origem | Aeroporto de Destino | ID Destino | Codeshare | Paradas | Equipamento |
|----------------|---------------|---------------------|-----------|---------------------|------------|-----------|-------|-----------|

Através do arquivo `routes.dat`, foi criado um grafo da **Rede de Transporte Aérea** chamado `rede_aerea.gt`. A partir desse arquivo, serão trabalhados os conceitos de otimização em grafos.

## Referências

BARABÁSI, Albert-Lázsló. **Network science**. Cambridge: Cambridge University Press, 2016. <br>
NEWMAN, M. **Networks**. [s.l.] Oxford University Press, 2018.