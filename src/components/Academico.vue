<template>
    <body>
           <center>
    <article class="tabla2">

        <h2 class="titulo2">Informacion Academica</h2>
    
        <table width="600px" border="">
            <tr>
                <td> <b> Institucion</b></td>
                <td> <b> Metropolitano Maria Occidende</b></td>
               
            </tr>
            <tr>
                <td> <b> Titulo obtenido</b></td>
                <td> <b> bachiller</b></td>
               
            </tr>
            <tr>
                <td> <b> Fecha de graduacion</b></td>
                <td> <b>27/11/2021 </b></td>
               
            </tr>
            <tr>
                <td> <b> Institucion</b></td>
                <td> <b>SENA </b></td>
               
            </tr>
            <tr>
                <td> <b> Programa</b></td>
                <td> <b>ADSI</b></td>
               
            </tr>
        
            <tr>
                <td> <b> Nivel</b></td>
                <td> <b>Etapa Electiva</b></td>
               
            </tr>
        
        </table>
    
    </article>

</center>
   
   </body>
     </template>


















     
     <script>
     export default {
       name: 'HelloWorld',
       props: {
         msg: String
       }
     }
     </script>
     
     <!-- Add "scoped" attribute to limit CSS to this component only -->
     <style scoped>
   * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: darkgray;


}

header {
    text-align: center;
    justify-content: space-around;
    -webkit-text-stroke:1px black;
    color: cornflowerblue;   
    background-color: floralwhite;
     height: 7vh;
}

.titulo1{
    text-align: center;
-webkit-text-stroke: 1px cornflowerblue;
color: black;
font-size: 40px;

}
ul {
    background-color: floralwhite;
    font-size: 18px;
    height: 10vh;
    justify-content: space-evenly;
    display: flex;
    list-style: none;
   
}

td{
    border: 2px solid cornflowerblue;
}

.tabla1{
    background-color: floralwhite;
        margin-left: auto;
margin-right: auto;
}
.imgenes{
                
 margin-left: 77ch;
margin-right: auto;
}



.tabla2{
    background-color: cornsilk;
    height: 35vh;
    margin-left: auto;
    margin-right: auto;
    
}
.titulo2{
    text-align: center;
    -webkit-text-stroke: 1px cornflowerblue;
    color: black;
    font-size: 40px;
}
     </style>
     