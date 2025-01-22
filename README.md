# Testes de API - ServeRest

Este repositório contém os testes manuais e automatizados realizados na API [ServeRest](https://serverest.dev/). Abaixo, você encontrará as instruções para importar os testes no Postman e um resumo do trabalho realizado.

## Passo a passo para importar os testes no Postman

1. **Baixe o arquivo JSON de coleção do Postman** que está neste repositório.
2. Abra o Postman no seu computador.
3. Clique no botão **"Import"** no canto superior esquerdo.
4. Selecione o arquivo JSON baixado ou arraste-o para a janela de importação.
5. Após a importação, a coleção estará disponível na barra lateral esquerda.
6. Verifique se todas as variáveis de ambiente necessárias estão configuradas corretamente:
   - Acesse a aba **Environments** no Postman.
   - Crie um novo ambiente ou edite um existente para incluir as variáveis necessárias (exemplo: `{{baseUrl}}` com valor `https://serverest.dev`).
7. Agora você está pronto para executar os testes!

## Sobre os testes realizados

Os testes foram realizados em todas as categorias disponíveis na API ServeRest:

### 1. **Usuários**
- Testes para criação, consulta, atualização e exclusão de usuários.
- Validação de cenários positivos e negativos, como usuários duplicados ou campos obrigatórios ausentes.

### 2. **Produtos**
- Testes para adicionar, consultar, atualizar e excluir produtos.
- Verificação de limites de campos e respostas para dados inválidos.

### 3. **Carrinho**
- Testes para operações como adicionar itens ao carrinho, consultar o carrinho e finalizar compras.
- Testes para validar o comportamento com carrinhos vazios ou produtos inexistentes.

### Abordagem utilizada
- **Testes manuais:** Cenários exploratórios e casos críticos foram executados manualmente para garantir a estabilidade inicial da API.
- **Testes automatizados:** Criação de scripts no Postman utilizando a aba "Tests" para validar automaticamente as respostas e assegurar a conformidade com os requisitos.

## Próximos passos
Ainda existem alguns cenários a serem testados e validados. Este README será atualizado conforme o progresso.

## Referência
- Documentação oficial da API: [ServeRest](https://serverest.dev/)

