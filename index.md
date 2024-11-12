<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--  ----------------------------------------------------------------------  -->
    <!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
    <!--  If necessary, please modify the charset parameter to specify the        -->
    <!--  character set of your HTML page.                                        -->
    <!--  ----------------------------------------------------------------------  -->
    <META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
        <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="/node_modules/bootstrap/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="/node_modules/bootstrap-icons/font/bootstrap-icons.css">
    <link rel="stylesheet" href="/style.css">
    <title>Solicitação de suporte</title>
</head>

<body>


    <main class="flex-fill d-flex flex-column wrapper bg-black text-white " >
        <div class="container">
           
           
            <!--  ----------------------------------------------------------------------  -->
            <!--  NOTE: Please add the following <FORM> element to your page.             -->
            <!--  ----------------------------------------------------------------------  -->
            <form action="https://webto.salesforce.com/servlet/servlet.WebToCase?encoding=UTF-8" method="POST">
    
                <input type=hidden name="orgid" value="00D8b0000021iUt">
                <input type=hidden name="retURL" value="https://abrircasotestepratico.netlify.app/success.html">
                <!--  ----------------------------------------------------------------------  -->
                <!--  ----------------------------------------------------------------------  -->
                <!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
                <!--  these lines if you wish to test in debug mode.                          -->
                <!--  <input type="hidden" name="debug" value=1>                              -->
                <!--  <input type="hidden" name="debugEmail"                                  -->
                <!--  value="esdrasrubro@outlook.com">                                        -->
                <!--  ----------------------------------------------------------------------  -->
                <h1 class="">Solicite suporte através desse forms!</h1>
                <p class="">Web to case para teste prático</p>

                <label for="name" class="col-sm-2 col-form-label">Nome do contato</label><input  id="name" maxlength="80" name="name" size="20" class="form-control" type="text" /><br>
    
                <label for="email" class="col-sm-2 col-form-label">Email</label><input  id="email" maxlength="80" name="email" size="20" class="form-control" type="email" /><br>
                
                <label for="product" class="col-sm-2 col-form-label">Produto</label><select  id="00N8b00000Hxg5r" name="00N8b00000Hxg5r" title="Product" class="form-select" required="">
                    <option value="">-- Nenhum --</option>
                    <option value="TV">TV</option>
                    <option value="Soundbar">Soundbar</option>
                </select><br>
                
                <label for="subject" class="col-sm-2 col-form-label">Assunto</label><input  id="subject" maxlength="80" name="subject" size="20" class="form-control" type="text" /><br>
                
                <label for="description" class="col-sm-2 col-form-label">Descrição</label><textarea name="description" class="form-control"></textarea><br>
                

        
                <input type="hidden" id="external" name="external" value="1" />
        
                <input type="submit" name="submit" class="btn btn-primary" value="Send Case"><br>
        
            </form>
        </div>
    </main>        


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
        crossorigin="anonymous">
    </script>
    <script type='text/javascript'>
            function initEmbeddedMessaging() {
                try {
                    embeddedservice_bootstrap.settings.language = 'pt_BR'; // For example, enter 'en' or 'en-US'
        
                    embeddedservice_bootstrap.init(
                        '00DHZ000003dGT1',
                        'PocChatBotArticle',
                        'https://resultadosdigitais--devesdras.sandbox.my.site.com/ESWPocChatBotArticle1731419602366',
                        {
                            scrt2URL: 'https://resultadosdigitais--devesdras.sandbox.my.salesforce-scrt.com'
                        }
                    );
                } catch (err) {
                    console.error('Error loading Embedded Messaging: ', err);
                }
            };
        </script>
        <script type='text/javascript' src='https://resultadosdigitais--devesdras.sandbox.my.site.com/ESWPocChatBotArticle1731419602366/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
        
</body>

</html>