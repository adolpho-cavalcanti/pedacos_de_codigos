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

<script>
function verificaChecks() {
    var aChk = document.getElementsByName("item"); 
    for (var i=0;i<aChk.length;i++){ 
        if (aChk[i].checked == true){ 
            // CheckBox Marcado... Faça alguma coisa... Ex:
            alert(aChk[i].value + " marcado.");
        }  else {
            // CheckBox Não Marcado... Faça alguma outra coisa...
        }
    }
}
</script>

<br><input type="checkbox" name="item" value="UM"> 1
<br><input type="checkbox" name="item" value="DOIS"> 2
<br><input type="checkbox" name="item" value="TRES"> 3
<br><input type="checkbox" name="item" value="QUATRO"> 4
<br><input type="checkbox" name="item" value="CINCO"> 5
<br><input type="button" value="Valida Checks" onclick="verificaChecks()">
