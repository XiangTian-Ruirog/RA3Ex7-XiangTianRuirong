# 0376RA4PR1 - Pràctica de Manipulació del DOM

Aquest projecte conté una sèrie d'exercicis pràctics per aprendre a manipular el DOM amb JavaScript. Cada exercici demostra una tècnica diferent de treball amb elements HTML, estils i esdeveniments.

## 📁 Estructura del projecte
0376RA4PR1/
│
├── index.html # Pàgina principal amb els elements HTML
├── style.css # Estils visuals de la pàgina
├── script.js # Codi JavaScript amb les solucions dels exercicis
└── README.md # Documentació del projecte

text

## 🚀 Com visualitzar el projecte

Pots veure el projecte en funcionament a:
- **GitHub Pages**: [https://el-teu-usuari.github.io/0376RA4PR1/](https://el-teu-usuari.github.io/0376RA4PR1/)
- **Repositori GitHub**: [https://github.com/XiangTian-Ruirog/RA3Ex7-XiangTianRuirong.git]

## 📝 Exercicis realitzats

### 1️⃣ Selecció d'elements
**Objectiu**: Utilitzar `querySelector` per canviar el color d'un element `<h1>` en carregar la pàgina.

```javascript
let h = document.querySelector("#titol-principal");
h.style.color = "green";
2️⃣ Modificació de contingut
Objectiu: Fer que un paràgraf <p> mostri "Hola Món" utilitzant textContent.

javascript
let p = document.getElementById("paragraf-hola");
p.textContent = "Hola Món";
3️⃣ Modificació d'atributs
Objectiu: Canviar l'atribut src d'una imatge amb setAttribute.

javascript
let img = document.getElementById("imatge-canviant");
img.setAttribute("src", "https://albertonate.com/wp-content/uploads/2022/10/Logo-ILBclaim.png");
4️⃣ Estils dinàmics
Objectiu: Canviar el color de fons d'un element en fer-hi clic.

javascript
let caixa = document.getElementById("caixa-estil");
caixa.addEventListener("click", function() {
    caixa.style.backgroundColor = "#56d661";
});
5️⃣ Manipulació de classes
Objectiu: Crear un botó que afegeixi/tregui la classe 'actiu' amb classList.toggle.

javascript
let botoToggle = document.getElementById("boto-toggle");
let textClasse = document.getElementById("text-classe");
botoToggle.addEventListener("click", function() {
    textClasse.classList.toggle("actiu");
});
6️⃣ Esdeveniments amb alerta
Objectiu: Afegir un addEventListener a un botó per mostrar una alerta.

javascript
let botoAlerta = document.getElementById("boto-alerta");
botoAlerta.addEventListener("click", function() {
    alert("Hola! Has fet clic al boto.");
});
7️⃣ Creació d'elements
Objectiu: Crear un nou <li> amb createElement i afegir-lo a una <ul> amb appendChild.

javascript
let botoAfegir = document.getElementById("boto-afegir");
let llista = document.getElementById("llista-compra");
botoAfegir.addEventListener("click", function() {
    let nouItem = document.createElement("li");
    nouItem.textContent = "Nou producte";
    llista.appendChild(nouItem);
});
8️⃣ Eliminació d'elements
Objectiu: Fer que un element desaparegui en fer-hi clic utilitzant el mètode remove().

javascript
let elementEliminar = document.getElementById("element-eliminar");
elementEliminar.addEventListener("click", function() {
    elementEliminar.remove();
});
