<html>
    <head>
        <title>Site do Projeto</title>

        <style>

            .bloco1{
                background-color: #2ecc71;
                padding: 20px;
                font-family: sans-serif;
                text-align: center;
                color: white;
            }

            .caixa-meio {
                border: 2px solid #0e0a0a;
                margin: 20px;
                padding: 15px;
                color: black;
            } 

            #btn1 {
                background: #d6d0b5;
                border: none;
                padding: 10px;
                font-weight: bold; 
                cursor: pointer;
            }

            .texto1 {
                font-size: 12px; 
                margin-top: 50px; 
                border-top: 1px solid #000;
            }

            
        </style>
    </head>
    <body>
        
        <div class="bloco1">

            <div style="font-size: 25px;">Meu Projeto de Tecnologia</div>
            <div class="caixa-meio">
                <p>O milho vira bioplástico e depois vira música!</p>

                <div id="btn1" onclick="alert('Incrível, né?')">CLIQUE AQUI</div>
            </div>

            <div class="texto1">Criado por mim</div>
        </div>

        <script>
            console.log("O site abriu.");
        </script>
    </body>
</html>