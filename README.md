<p align="center">
  <img src="./.github/readme-cover.svg" alt="Pokédex: Da resposta da API ao cartão na tela." width="100%" />
</p>

# Pokédex · consumo de API e cartões dinâmicos

Catálogo de Pokémon em JavaScript que consulta a PokéAPI e monta cartões com nome, número, imagem e tipo.

**HTML · CSS · JavaScript**

Exercício de interface da série 50 Projects, mantido também separadamente para explorar consumo de API e manipulação do DOM.

## Explore o diferencial

| Ponto de entrada | O que observar |
| --- | --- |
| [Dados viram interface](script.js) | Nome, número e tipo recebidos da API determinam o conteúdo dos cartões. |
| [Identidade por tipo](style.css) | A folha de estilos organiza a apresentação visual do catálogo. |

## Destaques

- Consulta assíncrona de Pokémon por identificador.
- Criação de cartões no DOM a partir da resposta da API.
- Cores associadas ao tipo e número formatado com zeros à esquerda.

<details>
<summary><strong>Organização e código</strong></summary>

### Por dentro do código

| Arquivo | Responsabilidade |
| --- | --- |
| [`script.js`](script.js) | Requisições e geração dos cartões. |
| [`index.html`](index.html) | Container do catálogo. |
| [`style.css`](style.css) | Estilização dos cartões. |

</details>

<details>
<summary><strong>Executar e consultar</strong></summary>

### Executar localmente

Clone o projeto e sirva a pasta com um servidor estático. Com Python 3 instalado:

```bash
git clone https://github.com/Will-Ifes/project37_pokemon.git
cd project37_pokemon
python3 -m http.server 8080
```

Abra http://localhost:8080. Não há instalação de dependências ou etapa de build.

</details>

<details>
<summary>Escopo e referências</summary>

A implementação consulta até 898 registros em sequência, sem paginação ou tratamento completo de falhas. Carregamento sob demanda, cache e estados de erro são caminhos de evolução. Depende de acesso à PokéAPI e aos sprites externos.

</details>

---

Mantido por **Will Oliveira** · [Perfil](https://github.com/Will-Ifes) · [LinkedIn](https://www.linkedin.com/in/wildemberg-de-jesus-oliveira/)
