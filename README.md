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