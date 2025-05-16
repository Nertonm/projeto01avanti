# projeto01avanti
 portfólio virtual em HTML e CSS do Avanti Capacita Brasil] FSN5- Módulo Básico
 
<style>
         body {
             background-color: #cb9ce48d;
         }
         h3 {
             color: #8142ab;
             font-family:cursive; 
         }
         p {
             color: #200537dc;
                font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif
         }
         ul {
             list-style-type: none; color: rgba(128, 4, 4, 0.799);
                font-family:cursive;
         }
     </style>
            
    
        </section>
        <section>
            <h3>Aprendizado</h3>
            <h4>Atualmente, estou aprendendo três tecnologias para desenvolver para a web ou automatizar tarefas: HTML, CSS e Python.</h4>
         <ul> 
            <p><li>HTML</li></p>
            <p>🖼️ É a estrutura básica de qualquer página da web:</p>
<pre><code>&lt;header&gt;, &lt;section&gt;, &lt;article&gt; e &lt;footer&gt;</code></pre>

<p>Exemplo:</p>
<pre style="background: #2d2d2d; color: #f8f8f2; padding: 1rem; border-radius: 6px;"><code>&lt;form aria-label="Formulário de Contato"&gt;
  &lt;label for="nome"&gt;Nome:&lt;/label&gt;
  &lt;input type="text" id="nome" name="nome" required&gt;
  
  &lt;label for="email"&gt;Email:&lt;/label&gt;
  &lt;input type="email" id="email" name="email" required&gt;

  &lt;button type="submit"&gt;Enviar&lt;/button&gt;
&lt;/form&gt;
</code></pre>
 <p>Exemplo 2:</p>
  <pre style="background: #2d2d2d; color: #f8f8f2; padding: 1rem; border-radius: 6px;">
<code>&lt;!DOCTYPE html&gt;
&lt;html lang="pt-br"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;title&gt;Minha Página&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;h1&gt;Olá, mundo!&lt;/h1&gt;
&lt;/body&gt;
&lt;/html&gt;</code>
  </pre>
</form></p> <br><br>
         
        <p><li>Css</li></p> 
        <h3>🎨 Define a aparência e o layout das páginas da web:</h3>
      <p>Exemplo:</p>
       <pre style="background: #2d2d2d; color: #f8f8f2; padding: 1rem; border-radius: 6px;"><code>
p {
  color: blue;
  font-size: 16px;
}
</code></pre><br><br>

        <p><li>Pyton</li></p>  
        <h3>🐍 Pode Verificar se um número é par ou ímpar</h3>
        <p>Exemplo:</p>
  <pre style="background: #2d2d2d; color: #f8f8f2; padding: 1rem; border-radius: 6px;">
<code>numero = int(input("Digite um número: "))
if numero % 2 == 0:
    print("É par.")
else:
    print("É ímpar.")</code>
  </pre><br><br>

    <h3>💬 Deixe seu comentário:</h3>
  <form style="display: flex; flex-direction: column; max-width: 500px;">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required style="padding: 0.5rem; margin-bottom: 1rem;">

    <label for="comentario">Comentário:</label>
    <textarea id="comentario" name="comentario" rows="4" placeholder="Escreva aqui seu comentário" required style="padding: 0.5rem; margin-bottom: 1rem;"></textarea>

    <button type="submit" style="background-color: #4caf50; color: white; padding: 0.7rem; border: none; border-radius: 4px; cursor: pointer;">
      Enviar
    </button>
  </form>
  </body>
</html>


Oi, Railane aqui
minha parte foi os tópicos 2 e 3:


<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale-1.0">
        <title>Página de Contato</title>
        <link rel="stylesheet" href="style.css">
        <style>
            body{
                 font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                 font-size: medium;
                 background-color: #ffffff;
                 margin: 0;
                 padding: 20px;
                 text-align: center;
            }
            .container{
                     max-width: 600px;
                     margin: auto;
                     background: white;
                     padding: 20px;
                     border-radius: 5px;
                     box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }            
                

            h1{
            
                text-align: center;
                
                
            }
            label{
                
                display: block;
                margin: 10px 0 5px;
                font-size: 20px;
            }
            input, textarea{
                
                width: 100%; 
                height: 50px; 
                resize: none;
            }
    
            button{
                background-color: blue;
                color: #cec7c7;
                border: none;
                padding: 10px 15px;
                border-radius: 4px;
                cursor: pointer;
                width: 100%;
            }
            button:hover{
                background-color: rgb(46, 195, 61);
            }

        </style>
    </head>
    <body>
        <div class="container">
        <h1>Página de Contato</h1>
        <form action="malito:railanemesquita34@gmail.com" method="post" enctype="text/plain"></form>
    </form>
    <a href="https://wa.me/5585981360256?text=fale%20comigo" target="_blank">
        <img src="c:\Users\Samsung\Downloads\10000486.jpg" alt="Envie-me mensagem no WhatsApp" style="width: 40px;">
    </a>
    <form action="mailto:railanemesquita342gmail.com" method="post" enctype="text/plain">

         <p><label for="Nome">Nome:</label></p>
         <input type="text" id="nome" name="nome" required>

         <p><label for="email">Endereço de email:</label></p>
         <input type="email" id="email" name="email" required>

         <p><label for="assunto">Motivo do assunto:</label></p>
         <textarea id="assunto" name="assunto" rows="4" required></textarea>

         <p><label for="telefone">Número de telefone:</label></p>
         <input type="tel" id="telefone" name="telefone" required>

         <p><label for="mensagem">Mensagem:</label>
         <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

         <p><button type="submit">Enviar formulário</button></p>
       </form>
      </div>
</body>
</html>

Contei com a ajuda de meus colegas de equipe, em especial a Julianny, e também com a ajuda da Alanis.
Foi uma experiência divertida, e um bom trabalho em equipe.
