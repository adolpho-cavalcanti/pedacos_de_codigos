# pedacos_de_codigos
Pedaços de códigos em várias linguagens
#Enviar formulário por clique
<form name="formulario" action="/action_page.php">
	<input type="checkbox" name="campo" value="Adolpho" onclick="submitform()">
</form>
<script type="text/javascript">
    function submitform() {
        document.formulario.submit();
    }
</script>
