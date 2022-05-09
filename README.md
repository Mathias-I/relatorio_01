<!DOCTYPE html>
<html lang="pt_br">
    <head>
        <title>teste Questionario</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=divicewidth, initial-scale=1.0">
        <link rel = "stylesheet" type=" text/css" href="style.css">
        <link rel="selecao" type="acao/java" href="seleção.js">
        
    </head>
    <body>
        <div class="box">
            <form>
                <fieldset>
                    <legend><b>Formulario</b></legend>
                    <br>
                    <div class="inputBox">
                        <input type="text" name="Nome" id="nome" class="inputUser" required>
                        <label for="Nome" class="labelInput">Nome Completo:</label>
                    </div>
                    <br><br>
                    <div class="inputBox">
                        <input type="email" name="email" id="email" class="inputUser" required>
                        <label for="email" class="labelInput">E-mail:</label>
                    </div>
                    <br><br>
                    <div class="inputBox">
                        <input type="tel" name="tel" id="telefone" class="inputUser" required>
                        <label for="telefone" class="labelInput">Telefone:</label>
                    </div>
                    <br>
                    <p>Sexo</p>
                    <input type="radio" name="genero" value="feminino" required>
                    <label for="feminino">Feminino</label>
                    <br>
                    <input type="radio" name="genero" value="masculino" required>
                    <label for="masculino">Masculino</label>
                    <br>
                    <input type="radio" name="genero" value="outros" required>
                    <label for="outros">Outros</label>
                    
                    <br><br>
                    
                        <label for="date">Data de Nascimento:</label>
                        <input type="date" name="date" id="data" required>
               
                    <br><br>
                    <div class="inputBox">
                        <input type="text" name="cidade" id="cidade" class="inputUser" required>
                        <label for="cidade" class="labelInput">Cidade:</label>
                    </div>
                    <br>  <br>
                    <div class="inputBox">
                        <label for="login" class="labelInput">Login:</label>
                        <input type="text" name="login" id="login" class="inputUser" required>
                    </div>
                    <br><br>
                    <div class="inputBox">
                        <input type="password" name="passoword" id="passoword" class="inputUser" required>
                        <label for="passoword" class="labelInput">Senha:</label>
                    </div>
                    <br><br>
                    <div class="inputBox">
                        <input type="text" name="cidade" id="cidade" class="inputUser" required>
                        <label for="cidade" class="labelInput">Cidade:</label>
                    </div>
                    <br>  <br>
                    <div class="inputBox">
                        <br>
                        <label for="estado" class="labelInput">Estado:</label>
                        <select  id="estado"  required>
                            <option>Acre</option>
                            <option>Alagoas</option>
                            <option>amapá</option>
                            <option>Anazonas</option>
                            <option>Bahia</option>
                            <option>Ceará</option>
                            <option>Distrito Federal</option>
                            <option>Espirito Santo</option>
                            <option>Goiás</option>
                            <option>Maranão</option>
                            <option>Mato Grosso</option>
                            <option>Mato Grosso do Sul</option>
                            <option>Minas Gerais</option>
                            <option>Pará</option>
                            <option>Paraíba</option>
                            <option>Paraná</option>
                            <option>Pernanbuco</option>
                            <option>Piauí</option>
                            <option>Rio de Janeiro</option>
                            <option>Rio Grande do Norte</option>
                            <option>Rio Grande do Sul</option>
                            <option>Rondônia</option>
                            <option>Roraima</option>
                            <option>Santa Catarina</option>
                            <option>São Paulo</option>
                            <option>Sergipe</option>
                            <option>Tocantins</option>
                        </div>
                    <br><br>
                    <input type="submit" name="submit" id="submit">
                    <br>
                </fieldset>
            </form>
        </div>



    </body>

</html>
