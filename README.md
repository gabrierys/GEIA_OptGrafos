# Grupo de Estudos em Inteligência Artificial (GEIA) / Universidade de Fortaleza
Grupo de Estudos em Otimização em Grafos - Prof. Me. Ricardo Carubbi

## Fonte dos Dados: Rede de Transporte Aéreo

Os dados utilizados são provenientes de um repositório chamado OpenFlights especializado em armazenar e disponibilizar informações de voos, aeroportos e rotas aéreas.

Cada linha do arquivo `routes.dat` representa uma rota entre dois aeroportos e, geralmente, possui o seguinte formato:

| Companhia Aérea | ID Companhia | Aeroporto de Origem | ID Origem | Aeroporto de Destino | ID Destino | Codeshare | Paradas | Equipamento |
|----------------|---------------|---------------------|-----------|---------------------|------------|-----------|-------|-----------|

A partir do arquivo `routes.dat`, foi criado um grafo da **Rede de Transporte Aéreo** chamado `rede_aerea.gt`. Através desse arquivo, serão trabalhados os conceitos de otimização em grafos.

## Estrutura 

A cada encontro, será criada uma pasta de nome com formato `DDMMYY`simbolizando a data, o mês e o ano do encontro do GEIA onde o notebook foi apresentado. Essa pasta estará dentro de `notebooks`, os alunos deverão colocar seus trabalhos dentro das respectivas pastas, obedecendo a data do encontro. A nível de organização, é preferível que os *commits* sigam a seguinte estrutura:

```
<tipo>: <mensagem curta e descritiva>
```

### Tipos de Commit

- `feat`: adições de novas funcionalidades ou componentes.
- `fix`: correções de bugs, erros ou comportamentos inesperados.
- `docs`: adições ou modificações de documentação (ex: README, comentários).
- `style`: ajustes que não afetam a lógica do código (ex: formatação, indentação).
- `refactor`: reestruturação de código sem alteração de funcionalidade.
- `test`: adição ou atualização de testes de unidade, integração ou automação.
- `chore`: tarefas de manutenção, como atualizações de dependências.
- `perf`: otimizações de performance.
- `ci`: alterações nos scripts de integração contínua e automação.
- `build`: alterações relacionadas à build do projeto, como ajustes em configurações.

### Mensagem Curta e Descritiva

- Escreva a mensagem em **tempo presente** e de forma **imperativa**.
- Limite a mensagem principal a **50 caracteres ou menos**.
- Seja claro e específico, evitando terminologias ambíguas.

## Referências

BARABÁSI, Albert-Lázsló. **Network science**. Cambridge: Cambridge University Press, 2016. <br>
NEWMAN, M. **Networks**. [s.l.] Oxford University Press, 2018.