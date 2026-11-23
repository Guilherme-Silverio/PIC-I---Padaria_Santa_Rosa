# Sistema de Gestão — Padaria e Confeitaria Santa Rosa

> Projeto Integrador Curricular I (PIC I) — terceira entrega, 2026.

## 1. Nome e objetivo

**Sistema de Gestão — Padaria e Confeitaria Santa Rosa**.

Aplicação web acadêmica criada para centralizar e simplificar o acompanhamento de produtos, clientes, estoque, pedidos e indicadores de vendas de uma padaria e confeitaria. O objetivo é demonstrar um fluxo integrado de gestão em uma interface intuitiva.

## 2. Integrantes

- Guilherme Henrique Silvério Francisco
- Davi Henrique Cardoso Bellato

## 3. Tecnologias utilizadas

- **HTML5:** estrutura semântica das páginas.
- **CSS3:** identidade visual, componentes e responsividade.
- **JavaScript (ES6+):** regras de negócio, formulários e atualização da interface.
- **Web Storage API (`localStorage`):** persistência local de dados.
- **CSV:** exportação de dados para planilhas.

Não são utilizados frameworks, bibliotecas externas ou banco de dados remoto.

## 4. Requisitos e dependências

- Computador ou dispositivo com navegador moderno, como Chrome, Edge ou Firefox.
- JavaScript e armazenamento local habilitados no navegador.
- Não é necessário instalar Node.js, servidor web, banco de dados ou pacotes adicionais.
- Acesso à internet não é necessário para a execução local.

## 5. Instalação, configuração e execução

1. Baixe o ZIP da entrega ou clone o repositório GitHub.
2. Extraia o ZIP, caso necessário.
3. Mantenha os arquivos `index.html`, `style.css` e `script.js` na mesma pasta.
4. Abra `index.html` no navegador.
5. Utilize o menu lateral para acessar os módulos.


## 6. Principais funcionalidades

| Módulo | Funcionalidades |
| --- | --- |
| Dashboard | Indicadores de vendas e pedidos do dia, quantidade de clientes e produtos, gráfico dos últimos sete dias, alertas e pedidos recentes. |
| Produtos | Cadastro, busca, filtro por categoria, edição e exclusão com restrições para itens com histórico de pedidos. |
| Estoque | Consulta de saldo e estoque mínimo, registro de entradas, saídas e ajustes, histórico de movimentações. |
| Pedidos | Cadastro com múltiplos produtos, cliente e pagamento, cálculo do total, baixa do estoque, alteração de status e cancelamento com devolução do estoque. |
| Clientes | Cadastro, busca, edição, exclusão e consulta do histórico agregado de compras. |
| Relatórios | Faturamento mensal, ticket médio, pedidos do mês, produto mais vendido, faturamento por categoria e exportações CSV. |

## 7. Dados de demonstração

O sistema abre **com dados fictícios**: produtos, oito clientes e pedidos simulados distribuídos pelos últimos 14 dias, com faturamento demonstrativo calculado automaticamente. Os valores são **exemplos para avaliação**, não vendas reais da Padaria Santa Rosa. Os dados se ajustam à data em que a base de demonstração é criada.

Os pedidos de exemplo incluem situações como **Pendente**, **Em preparo**, **Pronto** e **Entregue**. É possível testar as alterações de status e criar novas vendas.

Para recomeçar os testes, use o botão **Restaurar dados de exemplo** no rodapé do sistema. **Atenção:** essa ação substitui todos os dados salvos naquele navegador após confirmação.

O sistema usa os dados previamente salvos no navegador quando já existem; por isso, a restauração é útil se a versão anterior foi aberta no mesmo navegador.

## 8. Exemplos de funcionamento / roteiro de avaliação

1. **Dashboard:** confira os indicadores de vendas e pedidos recentes já preenchidos.
2. **Produtos:** cadastre um produto, pesquise pelo nome e altere seu preço.
3. **Estoque:** registre uma entrada e verifique a alteração no saldo e no histórico.
4. **Clientes:** cadastre um novo cliente e pesquise seu nome.
5. **Pedidos:** crie um pedido com dois itens, observe o valor total e a baixa no estoque; altere seu status.
6. **Relatórios:** confira o faturamento e exporte os dados de vendas em CSV.
7. **Restauração:** use o botão de demonstração para retornar à base inicial.

As próprias telas do sistema servem como exemplos interativos. Capturas de tela podem ser acrescentadas ao repositório na pasta `imagens/`, se desejado.

