Js
function carregar ()  {
var msg = document.getElementById('msg')
var img = document.getElementById('imagem')
var data = new Date()
var hora = data.getHours()
msg.innerHTML= `agora são ${hora} horas.`

if (hora >= 0 && hora < 12) {
  img.src = "fotoManha.jpg"

} else if (hora >= 12 && hora <18){
  img.src = "fotoTarde.jpg"
  

} else {
  img.src = "fotoNoite.jpg"
  
} 

style.css
body{
 background: rgb(10, 65, 133);
 font: normal 15pt arial;
}
header{
text-align: center;
color: white;
}
section{
background:white;
border-radius:10px;
padding:15px;
width:500px;
margin:auto;
box-shadow: black;
}
footer{
color: white;
text-align: center;
font-style: italic;

}
div {
  text-align: center;
  padding: 12px;
}
