# BookExplorer

**BookExplorer** é um aplicativo de gerenciamento de livros que permite aos usuários explorar, pesquisar e salvar livros usando a API Google Books. O aplicativo foi desenvolvido em Kotlin, utilizando Jetpack Compose para a interface de usuário moderna e interativa.

## Funcionalidades

- **Pesquisa de Livros**: Pesquise por livros usando a API Google Books.
- **Detalhes do Livro**: Veja informações detalhadas sobre cada livro, como título, autor, descrição, capa e mais.
- **Navegação Simples**: Navegue facilmente entre diferentes seções do aplicativo usando componentes do Jetpack Compose.
- **Armazenamento Local**: Salve seus livros favoritos no dispositivo para acesso offline.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem de programação principal.
- **Jetpack Compose**: Framework para construção de interfaces de usuário declarativas.
- **Retrofit**: Para consumo de APIs REST, incluindo a API Google Books.
- **ViewModel**: Para gerenciamento de estado e ciclo de vida.
- **Room Database**: Para armazenamento local de livros favoritos.

## Integração com API Google Books

- **Configuração da API**: Insira sua chave de API no local apropriado em `ApiService.kt`.
- **Consumo de Dados**: Os dados dos livros são consumidos utilizando Retrofit. O aplicativo faz requisições para a API Google Books e exibe os resultados na interface de usuário através do ViewModel e LiveData.
