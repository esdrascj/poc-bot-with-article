<html lang="pt-br">
<body>
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
        <script type='text/javascript' src='https://resultadosdigitais--devesdras.sandbox.my.site.com/ESWPocChatBotArticle1731419602366/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'>
        </script>
        
</body>

</html>