# Favicons do IFRN

O favicon dos projeto do IFRN para usar nos sites. Atualmente temos o favicon do Instituto e do Painel AVA.

## Como usar

Baixe a pasta equivalente ao favicon que você deseja usar e insira o código a seguir dentro da seção <head> do template base de sua página/aplicação, cuidando para que os `href` estejam corretos.

### Intituto

```html
<link
    rel="apple-touch-icon"
    sizes="180x180"
    href="FAVICON_FOLDER/apple-touch-icon.png"
/>
<link
    rel="icon"
    type="image/png"
    sizes="32x32"
    href="FAVICON_FOLDER/favicon-32x32.png"
/>
<link
    rel="icon"
    type="image/png"
    sizes="16x16"
    href="FAVICON_FOLDER/favicon-16x16.png"
/>
<link rel="manifest" href="FAVICON_FOLDER/site.webmanifest" />
<link
    rel="mask-icon"
    href="FAVICON_FOLDER/safari-pinned-tab.svg"
    color="#5bbad5"
/>
<meta name="msapplication-TileColor" content="#ffffff" />
<meta name="theme-color" content="#ffffff" />
```

### Painel AVA

```html
<link
    rel="apple-touch-icon"
    sizes="180x180"
    href="FAVICON_FOLDER/apple-touch-icon.png"
/>
<link
    rel="icon"
    type="image/png"
    sizes="32x32"
    href="FAVICON_FOLDER/favicon-32x32.png"
/>
<link
    rel="icon"
    type="image/png"
    sizes="16x16"
    href="FAVICON_FOLDER/favicon-16x16.png"
/>
<link rel="manifest" href="FAVICON_FOLDER/site.webmanifest" />
<link
    rel="mask-icon"
    href="FAVICON_FOLDER/safari-pinned-tab.svg"
    color="#00a300"
/>
<meta name="msapplication-TileColor" content="#00a300" />
<meta name="theme-color" content="#00a300" />
```
