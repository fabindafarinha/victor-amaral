<!-- HTML -->
<h1>Cálculo IMC</h1>

<!-- Criando e nomeando tabela imcTable -->
<table class="imcTable">
  <tr>
    <th>Classificação</th>
    <th>IMC</th>
  </tr>
  <tr>
    <tbody>
      <td>Abaixo</td>
      <td>18,5</td>

  </tr>
  <tr>
    <td>Normal</td>
    <td>18,5 a 24,9</td>
  </tr>
  <tr>
    <td>Sobrepeso</td>
    <td> 25,0 a 29,9</td>
  </tr>
  <tr>
    <td>Obesidade 1</td>
    <td>30,0 a 34,9</td>
  </tr>
  <tr>
    <td>Obesidade2</td>
    <td>35,0 a 39,9</td>
  </tr>
  <tr>
    <td>Obesidade3</td>
    <td>Maior ou igual a 40</td>
  </tr>
  </tbody>
</table>
body {
css//
font-family: arial;
  background: black;
  color: white;
  text-align: center;
}
h1{width: 100%; black; text-align: center;}
.imcTable{width: 100%; text-align: center;}
  .imcTable thead{ background: black; font-weight: bold; color: white;}
/* alterando fundo da linha #ccc para cinza ou azul*/
  .imcTable tbody tr:nth-child(2n){background: gray;}
.imcTable th , .imcTable td{padding: 7px 0;}

@media screen and (max-width: 480 px){
  .content{width: 94%;}
  
  .imcTable thead{display:nome;}
  .imcTable tbody td{display: flex; flex-direction: column; }
}

@media only screen and (min-width: 1200px){
  .content{width=100%;}
  .imcTable tbody tr td:nth-child(1){width:10%;}
  .imcTable tbody tr td:nth-child(2){width:30%;}
  .imcTable tbody tr td:nth-child(3){width:20%;}
  .imcTable tbody tr td:nth-child(4){width:10%;}
  .imcTable tbody tr td:nth-child(5){width:30%;}
}
js//
document.getElementsByTagName("h1")[0].style.fontSize = "12vw";
document.getElementsByTagName("imcTable")[0].style.fontSize = "12vw";
