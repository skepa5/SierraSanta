<script setup></script>

<template>
   <div class="background">
    <div class="cuerpo">
        <div class="izq">
            <div class="login-container">
                <div class="arriba-crede">
                    <label>Labelo</label>
                </div>
                <div class="credenciales-container">
                    <form action="">
                        <label for="email">Correo</label> <br>
                        <input class="emailinput" type="text" id="email" name="email" >
                        <br>
                        <label for="password">Contraseña</label><br>
                        <input class="passwordinput" type="password" id="password" name="password" >
                        <br>
                        <label for="password">Label</label><br>
                        <input class="input" type="text">
                        <br>
                        <label for="password">Contraseña</label><br>
                        <input class="input" type="text"  >
                        <br>
                    </form>
                    <br>
                    <div class="login-buttons">
                        <button class="login btn a">Return home</button>
                        <button class="login btn b">Label</button>
                    </div>
                </div>
                <div class="abajo-crede">
                    <label>Label</label>
                </div>
            </div>
        </div>
        <div class="der">
            
        </div>
    </div>
</div>
 
</template>

<!--

En esta página hay varios contenedores anidados unos dentro de otros. Uno llamado credenciales-container contiene inputs de inicio de registro.  

-->
<style scoped>
body{
        height: 100%;
        margin:0;
    }
    .background{
        color:white;
        height: 100vh;
    }
    .cuerpo{
        display: flex;
        height: 100%;

    }
    .izq{
        background-color: green;
        width: 100%;
        display: flexbox;
    }

    .der{
        background-color: navy;
        width: 100%;
    }

    .login-container{
       margin-top: 30%;
       display: flex; 
       flex-direction: column;
       border-color: black 1px;
       border-style: solid;
       align-items: center;
    }
    
    .login-buttons{
        display: flex;
        justify-content: space-around;
    }
    
    .credenciales-container{
        border-style: solid;
        border-color: green;
        width: 80%;
      
       
    }

    .arriba-crede{
        margin-bottom: 20%;
    }
    
    .abajo-crede{
        margin-top:10%;
    }

    .emailinput 
    {
        width: 100%;
    }
    
    .passwordinput{
        width: 100%;
    }
    .input{
        width: 100%;
    }
</style>