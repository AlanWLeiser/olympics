# Página das Olímpiadas

### Estrutura da página
- Banner inicial
- Tabela com ranking dos países
- Seção de notícias sobre as Olímpiadas

### Código exemplo

#### Banner

- HTML 

```html
<section class="banner">
        <div>
            <img src="LOGO_OLÍMPIADAS" alt="">
        </div>
    </section>
```

- CSS
```css
.banner{
    width: 100%;
    height: 800px;
    background: url("https://img.olympics.com/images/image/private/t_16-9_1280/f_auto/primary/ly9xuf0jwinrnmdrzmef");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    display: flex;
    justify-content: center;
}
.banner div{
    width: 100px;
}
.banner img{
    width: 100%;
    
}
```

#### Tabela

- HTML

```html
<table>
    <thead>
        <tr>
            <th>Posição</th>
            <th>País</th>
            <th>Ouro</th>
            <th>Prata</th>
            <th>Bronze</th>
            <th>Total</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <p>1º</p>

            </td>
            <td>
                <img
                    src="IMAGEM_BANDEIRA"
                    alt=""
                />
                <p>USA</p>
            </td>
            <td>
                <p>27</p>
            </td>
            <td>
                <p>35</p>
            </td>
            <td>
                <p>33</p>
            </td>
            <td>
                <p>95</p>
            </td>
        </tr>
    </tbody>
</table>
````
- CSS

```css
td {
    width: 60px;
    align-content: center;
    text-align: center;
}
td img {
    width: 15px;
    margin: 2px;
}
```

#### Seção de Noticias

- HTML

```html 
<section class="newsSection">
    <div>
        <div class="newsDiv">
            <img
                src="https://img.olympics.com/images/image/private/t_16-9_640/f_auto/primary/wmzus3toeptpzkadrrdq"
                alt=""
            />
            <div>
                <h5>Titulo da notícia</h5>
                <p>Descrição</p>
                <a
                    href="https://olympics.com/en/paris-2024/videos/images-of-the-day-day-12-olympic-games-paris-2024"
                >
                    <div class="buttonViewMore">
                        <p>Ver mais</p>
                    </div>
                </a>
            </div>
        </div>
    </div>
</section>
```

- CSS

```css
.newsSection {
    display: flex;
    align-items: center;
    justify-content: center;
}
.newsDiv {
    display: flex;
}
.newsDiv img {
    width: 150px;
}
.newsDiv h5 {
    font-size: 20px;
}
.newsDiv p {
    font-size: 15px;
    color: gray;
}
a {
    text-decoration: none;
}
.buttonViewMore {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: aliceblue;
    border-radius: 10px;
    width: 80px;
    height: 20px;
}
```