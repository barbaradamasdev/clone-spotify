# Projeto Clone Spotify + Sharp Coders 2023

Projeto do bootcamp Sharp Coders 2023, nesse desafio da ìmã Tech apliquei conceitos essenciais de desenvolvimento web. O objetivo principal foi desenvolver habilidades práticas na construção de interfaces de usuário atraentes e responsivas, utilizando tecnologias como HTML, CSS e JavaScript.

Veja o site ativo aqui: [https://barbaradamasdev.github.io/clone-spotify/](https://barbaradamasdev.github.io/clone-spotify/)

![Spotify](https://github.com/barbaradamasdev/clone-spotify/blob/main/Spotify-demo.jpg?raw=true)

## 🚀 Implementações adicionais

### Responsividade
O projeto tinha como foco uma versão da Home page do Spotify, adaptado para versão desktop. Adaptei para versão mobile, incluindo um menu sanduíche. Breakpoints utilizados:
- 320px: dispositivos móveis
- 768px: iPads, tablets
- 1024px: telas pequenas, laptops

### Padding e cores em variáveis
Para facilitar a responsividade e diminuir a quantidade de linhas repetidas mudei apenas a variável de padding nos conteineres
```
@media  (min-width: 768px) {
    :root {
        --width-container: 80%;
    }
}
```

### Classe para hover
Da mesma forma incluí uma classe para padronizar o hover em textos e facilitar a implementação adicionando diretamente na classe a ser aplicada
```
.hov-effect-txt {
    transition: all 300ms ease;
}

.hov-effect-txt:hover {
    color: var(--default-green);
    cursor: pointer;
}
```

### 🚀 Deploy
- O deploy deste projeto pode ser acessado na página abaixo:

[https://barbaradamasdev.github.io/clone-spotify/](https://barbaradamasdev.github.io/clone-spotify/)
