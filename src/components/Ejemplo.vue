<template>
 <body>
<header>
        <h1> HOJA DE VIDA </h1>
</header>




  <section>
        <h2>Datos Personales</h2>
  </section>


<section class="imgenes">
    <img src="../assets/karen.png" width="150">
    
</section>
 
  
        <table width="600px" border="">
            <tr>
                <td> <b> Nombres</b></td>
                <td> <b> Karen Dayana</b></td>
               
            </tr>

            <tr>
                <td>  <b>Apellidos</b> </td>
                <td><b>Restrepo Castaño</b> </td>
               
            </tr>

            <tr>
                <td> <b> Tipo de Documento</b></td>
                <td><b> Cedula Ciudadania</b></td>
               
            </tr>

            
            <tr>
                <td>  <b> Numero de Identificacion</b></td>
                <td> <b> 1061689614 </b> </td>
               
            </tr>


            <tr>
                <td>  <b> Fecha de Nacimiento </b> </td>
                <td>  <b> 29/06/2004 </b> </td>
               
            </tr>


            <tr>
                <td> <b> Pais</b> </td>
                <td> <b> Colombia</b></td>
               
            </tr>


            
            <tr>
                <td>  <b> Departamento</b> </td>
                <td> <b>  Cauca</b></td>
               
            </tr>


            
            <tr>
                <td> <b>Municipio</b> </td>
                <td>  <b>Popayan</b> </td>
               
            </tr>

            <tr>
                <td>  <b>Direccion</b> </td>
                <td> <b>crr 47#7c08 </b>  </td>
               
            </tr>

            <tr>
                <td> <b>Barrio </b> </td>
                <td> <b> Santo Domingo Sabio </b> </td>
               
            </tr>
        </table>
    
               







   
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

ul {
    background-color: floralwhite;
    font-size: 18px;
    height: 10vh;
    justify-content: space-evenly;
    display: flex;
    list-style: none;
   
}

h2{
     text-align: center;
    -webkit-text-stroke: 1px cornflowerblue;
    color: black;
    font-size: 40px;

    }
    article{
        justify-content: space-evenly;
        align-content: center;
        
    }
    
    a:active{
        text-decoration: none;
        background-color: black;
    }

    table{
        
 margin-left: auto;
margin-right: auto;
    }

    .imgenes{
                
        margin-left: 5ch;
margin-right: auto;
    }
  
    
    td{
        border: 2px solid cornflowerblue;
    }

    table{
        background-color: floralwhite;
    }
    div:hover{
        background-color: brown;
    }
    a:visited{
        background-color: cornsilk;
    }
    a:link{
        background-color: cornflowerblue;
    }
    a:active{
        background-color: crimson;
    }
  </style>
  