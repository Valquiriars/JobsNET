<!DOCTYPE html>
<html lang ="pt -br" > 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type = "text/css" href="jobsNet.css">
    
    
       
    <title>JobsNet</title>

</head>
 
<body>

<header>
           <div class = "flex-container">
           <div> 
        <img src="./Jobs-09.png" width = "250" alt= "logo" id= "logo">                       
          </div>
         <div>
          <h1 id= "titulo">CADASTRO - BANCO DE TALENTOS</h1>
          <p id= "frase" > As melhores vagas para a sua recolocação é aqui na JobsNET!</p> 
           </div>
                             
        
            <ul>
                 <li> 
                     <a target="_blank" href="mailto:valquiria.rodrigues17@hotmail.com">E-mail</a>
                    </li>
                 <li> 
                     <a target="_blank" href="https://wa.me/11957715272">Whatsapp</a>
                     </li>
           </ul>                
          </div> 
</header>  

     <form>   
          <div>
            <h3 id= "subtitulo"> DADOS PESSOAIS </h3><br>
           </div>

    <fieldset class= "grupo">
            <div class= preenchimento >
              <label for ="nome "><strong>Nome Completo</strong></label>
                <label for = "*" style = "color: red;">*</label>
                <input type ="text"  name= "nome"  id ="nome" required>
            </div>

            <div class= "preenchimento">
                <label for="Cargo Pretendido"><strong>Cargo Pretendido</strong></label>                
                <label for = "*" style = "color: red;">*</label>
                <input type= "text",  name= "cargo" id ="cargo"  required>
            </div>
    </fieldset>

    <fieldset class="grupo">
        <div class="preenchimento">
            <label for="data"><strong>Data de Nascimento</strong></label>
             <label for = "*" style = "color: red;">*</label>
             <input id="date"  type="date" value="date" id ="date" required id= "Data de nascimento ">           
              </div>   

             
        <div class ="preenchimento">
                <label for="sexo" name="sexo"><strong>Sexo </strong></label>                  
            <select id = "sexo">
                 <option selected disabled value="" >Selecione</option>
                 <option value="1">Feminino</option>
                 <option value="2">Masculino</option>
                 <option valeu="3">Outros</option>
            </select>
        </div>
                  <div class= "preenchimento" >
                    <label for="civil" name= "civil" ><strong>Estado Civil </strong></label>
                     <select id= civil >
                        <option selected disabled value= ""> selecione </option>
                        <option value="1"> Solteiro(a) </option>
                        <option value= "2"> Casado(a) </option>
                        <option value="3">Divorciado(a)</option>
                        <option value="4">Viúvo(a)</option>
                    </select>
             </div>
     </fieldset>
                              
               
       <fieldset class="grupo">
               <div class= "preenchimento">            
                <label for="cep"><strong>CEP</strong></label>   
                <label for = "*" style = "color: red;">*</label><br>         
                <input type="numero" name="cep" id='cep' required>
                                   
              </div>                           

             <div class= "preenchimento">
                <label for="endereco"><strong>Endereço</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
                <input type= "text", name= "endereco" id ="endereco" required>
            </div>
       
                   
            <div class= "preenchimento">
                <label for="num"><strong>Número</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
                <input type= "text" name= "numero" id ="numero" required>
            </div>
        </fieldset>

        <fieldset class="grupo">
                <div class= "preenchimento" >
                <label for="bairro" > <strong>Bairro</strong> </label> 
                <label for = "*" style = "color: red;">*</label><br>
                <input type= "text" name= "bairro" id ="bairro" required >
            </div>
            
               <div class= "preenchimento">
                <label for="cidade"><strong>Cidade</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
                <input type= "text"  name= "cidade" id ="cidade" required>
           </div>
 
           <div id= preenchimento>            
            <label for="uf" name= "uf"><strong>Estado</strong></label>
            <select id= "estado">
                <option selected disabled value =""></option>
                <option value="AC">Acre</option>
	            <option value="AL">Alagoas</option>
                <option value="AP">Amapá</option>
                <option value="AM">Amazonas</option>
                <option value="BA">Bahia</option>
                <option value="CE">Ceará</option>
                <option value="DF">Distrito Federal</option>
                <option value="ES">Espírito Santo</option>
                <option value="GO">Goiás</option>
                <option value="MA">Maranhão</option>
                <option value="MT">Mato Grosso</option>
                <option value="MS">Mato Grosso do Sul</option>
                <option value="MG">Minas Gerais</option>
                <option value="PA">Pará</option>
                <option value="PB">Paraíba</option>
                <option value="PR">Paraná</option>
                <option value="PE">Pernambuco</option>
                <option value="PI">Piauí</option>
                <option value="RJ">Rio de Janeiro</option>
                <option value="RN">Rio Grande do Norte</option>
                <option value="RS">Rio Grande do Sul</option>
                <option value="RO">Rondônia</option>
                <option value="RR">Roraima</option>
                <option value="SC">Santa Catarina</option>
                <option value="SP">São Paulo</option>
                <option value="SE">Sergipe</option>
                <option value="TO">Tocantins</option>
                                
                </select>
        </div>
 </fieldset>         
               
 <fieldset class= "grupo">
 
         <div class= "preenchimento" >
                <label for ="Telefone Fixo 1"><strong>Telefone Fixo 1</strong></label><br>
                <input type="numero" name="Telefone Fixo 1" id = "contato">

        </div>
                
             <div class= "preenchimento" >
                <label for="fone"><strong>Telefone Fixo 2</strong> </label><br>
                <input type="numero" name="Telefone Fixo 2"  id ="contato">
             </div>
             
             <div class= "preenchimento" >
                <label for="fone"><strong>Ceular</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
                <input type="numero" name="celuar" required id ="contato"> 
             </div> 

    </fieldset> <br>
    
    <fieldset class= "grupo">
            <div class= "preenchimento" >
            <label for= "email" ><strong>E-mail</strong></label>
            <label for = "*" style = "color: red;">*</label><br>
            <input type= "email" name = "email" id= "email" required> 
        </div>

    </fieldset>

       <div class= "campo">
          <h4 id ="subtitulo" >DOCUMENTOS</h4> 
        </div>


        <fieldset class= "grupo">

           <div class= "preenchimento" >
                <label for="rg"><strong>RG</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
                <input type="numero" id= "rg" name="rg" placeholder="21.212.212-1"  required>
             </div>

             <div class= "preenchimento">
                 
                <label for="cpf"><strong>CPF</strong></label>
                <label for = "*" style = "color: red;">*</label><br>
               <input type="text" maxlength="11" name="cpf" placeholder=" Somente os números" id = 'cpf_digitado' >
                 <div id= 'success' class= "alert alert-success" style= "display: none;" role="alert">
                    <strong>CPF Válido </strong> </div>
                   <div id= "error" class = "alert alert-danger" style="display: none"; role= "alert">
                   <strong>Seu CPF não é válido !</strong> </div>
               
               
             </div>
        </fieldset>
       
          
    <fieldset class = "grupo">
       
        <div class= "preenchimento" >
        <label for= "possui veiculo" id= "possui veiculo"><strong>Possui veículo?</strong> </label>
        <label>
             <input type = "radio" name= "veículo" value= "Sim" checked required> Sim </label>
        <label>
            <input type= "radio" name= "veículo"  value = "Não" required > Não  </label>

        </div>

          <div class= "preenchimento" >
         <label for ="Habilitação"id=" habilitação"><strong>Habilitação?</strong> </label>
        <label>
             <input type = "radio" name= "Habilitação" value= "Sim" checked required> Sim  </label>
        <label>
            <input type= "radio" name= "Habilitação"  value = "Não" required > Não    </label>
          </div>
       
           
     </fieldset> 

        <button type = "submit" name= "enviar " value= "Enviar" onclick="validacao()"> ENVIAR </button>

   
        
</form>
    
</body>

<script src="./script.js"></script>
</html>
