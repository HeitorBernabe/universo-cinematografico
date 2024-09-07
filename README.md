# Universo Cinematográfico - Aplicação de Pesquisa de Filmes e Séries

## Descrição
Esta aplicação web simples permite aos usuários pesquisar por filmes e séries em um banco de dados pré-definido. Ao digitar um termo na barra de pesquisa, a aplicação retorna uma lista de resultados relevantes, exibindo o título, descrição e um link para mais informações sobre cada item.

## Tecnologias Utilizadas
* **HTML:** Estrutura básica da página web, definindo elementos como cabeçalho, corpo, seções e formulário de pesquisa.
* **CSS:** Estiliza a aparência da página, definindo cores, fontes, layout e responsividade.
* **JavaScript:** Adiciona interatividade à aplicação, permitindo a pesquisa em tempo real e a atualização dinâmica da interface.

## Funcionamento
1. **Interface do Usuário:** 
   * A página principal possui uma barra de pesquisa onde o usuário digita o termo a ser buscado.
   * Ao clicar no botão "Pesquisar" ou ao pressionar Enter, a função `pesquisar()` é acionada.

2. **Lógica de Pesquisa:**
   * A função `pesquisar()` coleta o termo de pesquisa e converte-o para minúsculas para facilitar a comparação.
   * Em seguida, a função itera sobre cada item do banco de dados (armazenado no arquivo `dados.js`), verificando se o termo de pesquisa está presente no título, descrição ou tags do item.
   * Se houver correspondência, um novo elemento HTML é criado e adicionado à seção de resultados, exibindo as informações relevantes sobre o item encontrado.

3. **Exibição dos Resultados:**
   * Os resultados da pesquisa são exibidos em uma seção dedicada na página, com cada item apresentando:
     * Título (com link para mais informações)
     * Descrição
     * Link para a página externa com mais detalhes sobre o item

## Estrutura dos Arquivos
* **index.html:** Arquivo principal da aplicação, contendo a estrutura HTML da página.
* **style.css:** Arquivo CSS responsável pelo estilo visual da página.
* **app.js:** Arquivo JavaScript que contém a lógica da aplicação, incluindo a função de pesquisa.
* **dados.js:** Arquivo JavaScript que contém o banco de dados com as informações dos filmes e séries.

## Como Usar
1. **Clonar o repositório:**
   ```bash
   git clone https://seu-repositorio.git
