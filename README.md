<h1 align="center">Consultas de filmes</h1>

## Sobre o projeto

O foco do projeto é a manipulação de uma lista de filmes, oferecendo consultas otimizadas que resultam em estruturas de dados relevantes, tais como `Map`, `List` e `Set`.

Estrutura de um filme:

```Java
import java.util.Map;
import java.util.Set;

public class Filme {

  public final String titulo;
  public final int anoDeLancamento;
  public final Set<String> categorias;
  public final Set<String> diretores;
  public final Set<String> atores;
  public final Set<String> personagens;
  public final Map<String, Set<String>> atoresPorPersonagem;

  // ...
}
```

## Tecnologias utilizadas

- [Java](https://www.java.com/pt-BR/) - Linguagem de programação

## Funcionalidades

- Manipular uma lista de filmes
- Consultar filmes onde os atores interpretaram a si próprios
- Consultar filmes onde os atores atuaram em pelo menos um filme de determinado diretor
- Consultar filmes onde os diretores atuaram, ordenados pelo mais recente primeiro
- Consultar filmes lançados em um determinado ano, agrupados por categoria

## Instalação

```bash
# Clonar Projeto
$ git clone git@github.com:lucas-da-silva/java-consulta-filmes.git

# Entrar no diretório
$ cd java-consulta-filmes

# Execute o arquivo Principal.java pela IDE
```

## Estrutura do projeto

```
$PROJECT_ROOT
|   # Arquivos de configuração do Maven
├── .mvn
|   # Código fonte da aplicação
└── src
```

## Autor

- [@lucas-da-silva](https://github.com/lucas-da-silva)
