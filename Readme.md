# Lectia 1

<!-- Programatorii buni nu au timp pentru a reinventa roata. Cine are? -->

Programatorii buni dezvolta societatea.


# Ce facem astăzi?

1. Vom instala uneltele pentru dezvoltare (VS Code, Git, and VS Code Extensions)
2. Vom crea proiect pe care colaboram folosind **Git**
3. Vom crea prima pagina web simple (HTML)
4. Vom invata cum functioneaza cele mai simple Servere Web
5. Vom folosi unelte de dezvoltare ale browserului. Ai facut vreodata o radiografie a unui site? Bonus: **Google Lighthouse**
6. Vom crea cateva dintre componentele de baza ale unei pagini web

<!-- Insiruirea de mai sus ar putea fi simplificata  -->

# Cum asiguram cele mai bune resurse? <!-- asiguram=? -->

Scopul nostru este sa invatam psihologic si logic cu ajutorul recompenselor.

In acest caz recompensele sunt:
- Rezultatele finale obtinute
- Antrenarea logica a mintii, folosind Hartile mentale (Mind Maps) si  arborii cunoștințelor (Knowledge Trees). <!-- prea intortocheat; va fi clar cand avem un mindmap/knoledge tree bun ce sa scriu -->

### Knowledge tree (simplificat)

<!-- TODO it would be great to have an animation on the site (using svg) -->
<img src="./WebDev Getting Started Mindmap.png" />



## Uneltele de programare


### 1 Git+GitHub

### 2 VS Code (Visual Studio Code)

### 3 VS Code Extensions (Live Server, Git Graph)







# Lectia 1




<br />

## Web Servers and Websites


Website = colectie de pagini web. 

Indiferent de cum este creata o pagina Web, rezultatul pe care si noi, si ceilalti utilizatori il folosesc este un document HTML.


<hr/>


Server Web = aplicatie care "serveste" utilizatorilor paginile web. 

Pagina curenta este aleasa in functie de **url**-ul prezent (scris in bara browserului) pe care il introduc in bara de cautare, sau la care se ajunge din urmarea link-urilor.


<hr/>


Pe scurt, website-ul este meniul, iar serverul web este chelnerul.
<!-- Alte analogii mai inovative? -->








<br />

## Creating our first web page

<hr/>

### Power of **EMMET**

A programmer is resourceful.

### Let's power up the web server








<br />

## How to add multiple pages

<hr/>

### The path is the way

When the server opens at   `http://localhost:5500/`   it looks for an HTML page inside `/index.html` (our project root path).

This page is usually called **home**.

To add a new page such as **about**, the url will change to `http://localhost:5500/about-us`   and it will correspond to a folder named `about-us/`    where the server will look for a   `about-us/index.html` file.

So we simply create a file named **about-u/index.html**:
<!-- TODO add GIF: -->

### Connecting the pages

No one will type http://localhost:5500/about. Matter of fact, close to none of your users will write things such as   `facebook.com/profile` or `mail.google.com/mail/u/0/`

This is why hyper links (a from anchor) are used:

```html
<body>
    <header>
        <!-- link to Home page-->
        <a href="/" > 
            Home
        </a>
        <!-- link to About page-->
        <a href="/about-us" > 
            About Us
        </a>
    </header>
    <!-- ... -->
</body>
```

!!! The snippet above will be present at the start of each HTML page :).








<br />

## How images and style sheets are used

<hr />

### Keeping track of our images

### The global stylesheet `index.css`

### Using multiple sheets (`header.css`, `footer.css`)

# Important commands:

## Ctrl+Shift+P 
Open a Command Palette used for running any command imaginable.

## Ctrl+P 
Used to open a list + searchbox of the items inside our project, as to open a file efortlessly.

## Ctrl+/
Used to comment the selected lines/ portion of code

<!-- TODO de specificat regulile unei cai url safe: using =,? etc -->





# Tema

1. Pe langa pagina about, sa creezi si o pagina contact,
cu calea /contact, titlul Contact, aceiasi structura (header,main,footer), in care sa pui o descriere a serviciilor oferite (bookshop/coach/therapy/), dar si niste numere (fake) de contact, email si telefon.

Hint: importanta ca sa fie citibil este sa fie pe randuri separate, eventual fiecare cu un mic heading inainte e.g.    
```html
<h2> phone number: </h2> 
<div> +1 (234) 323 234 </div>
```


