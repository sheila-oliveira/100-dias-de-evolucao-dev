 ## Dia 1:
 Criação do repositório #100DiasEvoluçãoDev.

### Dia 1:

### Media-Queries

Hoje estudei sobre Media-Queries, Aprendi como posso fazer o site ficar responsivo tanto na versão desktop e mobile.

Resumo de Hoje:

@media() {} → È como um função, só vai funcionar se o código estiver dentro dos parênteses.

```css
@media (max-wdith: 600px) {
 font-size: 2rem;
}
```

Max-width → Max-width é uma largura menor que um valor em px, funcionar ao fazer a pagina ficar menor que o valor adicionado.

Min-width → Min-width é a largura maior que um valor em px. Funciona ao fazer a pagina ficar maior que o valor adicionado.

Poder ser adicionado valores de px, rem, em.

### Projeto **Ninbus stark**

Hoje pratiquei sobre media-queries no projeto **Ninbus stark.**

Onde fiz o site ficar responsivo adicionando display: gird; para fazer a pagina ficar no modo mobile e desktop.

```css
@media (min-width: 700px) {
  .titulo {
    grid-column: 1 / -1;
  }

  .content {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .descricao {
    display: grid;
    align-content: center;
    place-content: center;
    gap: 20px;
  }

}
```