<HTML>
<HEAD>
<META http-equiv="Content-Type" content="text/html; charset=windows-1252">
<META name="GENERATOR" content="Microsoft FrontPage 4.0">
<META name="ProgId" content="FrontPage.Editor.Document">
<TITLE>!Cadastro!</TITLE>
<STYLE type="text/css"><!-- table, body  { font-size: 10px; margin-left: 2px; margin-top: 1px }
input, select { font-family: Arial Narrow; font-size: 10x; font-weight: bold }
-->
</STYLE>
<script language="JavaScript">
<!--
function CadCSV() {
  var fso, f, r, nome, mail, nick, pass, pcmobile, series, console, marca, modelo, operadora, UserLink, DNascAno, DNascMes, DNascDia, sexo;
  var ForAppending = 8;
  var strVariable = "Voltar ao site";
  var BackForm = "Tentar novo cadastro";
  var site = "Brasil";
  strVariable = strVariable.link("scripts3.htm");
    nome = document.all.nome.value;
  ail = document.all.mail.value;
  nick = document.all.nick.value;
  pass = document.all.pass.value;
  console = document.all.console.value;
  series = document.all.series.value;
  pcmobile = document.all.pcmobile.value;
  marca = document.all.marca.value;
  modelo = document.all.modelo.value;
  operadora = document.all.operadora.value;
  UserLink = document.all.UserLink.value;
  DNascDia = document.all.DNascDia.value;
  DNascMes = document.all.DNascMes.value;
  DNascAno = document.all.DNascAno.value;
  sexo = document.all.sexo.value;
  fso = new ActiveXObject("Scripting.FileSystemObject");
  f = fso.OpenTextFile("c:\\UserCad.csv", ForAppending, true);
  f.WriteLine("|Name:" + nome + "|;" + "|Nasc:" + DNascDia + "/" + DNascMes + "/" + DNascAno + "|;" + "|Sexo:" + sexo + "|;" + "|Email:" + mail + "|;" + "|Link:http://" + UserLink + "|;" + "|Nick:" + nick + "|;" + "|Senha:" + pass + "|;" + "|Console:" + console + "|;" + "|Serie:" + series + "|;" + "|PcMobile:" + pcmobile + "|;" + "|Celular:" + marca + " " + modelo + "|;" + "|Operadora:" + operadora + "|;");
  f.Close();
  if (f) {
    document.write("<title>Resultado do cadastro de "+ nick + "</title>");
    document.write("<font size=2><b>" + nome + "</b>, seu cadastro foi realizado com sucesso!");
    document.write("<BR>Confira seus dados:<br><br>");
    document.write("Sexo: <font color=darkblue>" + sexo + "</font><br>Data de Nascimento: <font color=darkblue>" + DNascDia + "/" + DNascMes + "/" + DNascAno  + "</font><br>E-mail: <font color=darkblue>" + mail + "</font><br>Link pessoal: <font color=darkblue>" + UserLink + "</font><br>Nick: <font color=darkblue>" + nick + "</font><br>Senha: <font color=darkblue>" + pass + "</font><br>Vídeo-game: <font color=darkblue>" + console + "</font><br>Série: <font color=darkblue>" + series + "</font><br>Seu celular: <font color=darkblue>" + marca + "&nbsp;" + modelo + "</font><br>Operadora: <font color=darkblue>" + operadora + "</font>");
    document.write("<br><br>Copie e guarde esses dados.<br>" + strVariable);
    document.write("<br><br>Bem-vindo a " + site + "<br><br>");
    document.write("Obs.: <i style=color:darkred>Volte para a página principal do site, efetue seu log-in com o Nick e Senha cadastrado.</i></font>");
    } else {
    document.write("<title>Erro do cadastro!</title>");
    document.write("Desculpe, devido a um erro não conseguimos realizar seu cadastro, tente novamente ou mais tarde.<br>" + BackForm);
    }
  return(r);
}
-->
</script>
</HEAD>
<BODY>
<TABLE border="0" cellpadding="0" cellspacing="1" width="300" align="left">
<TBODY>
<TR><TD valign="top" align="left">


<img src="vac_baner.jpg" height="300" width="700">
<img src="pren_form.jpg" height="100" width="300">


<FORM action="javascript:CadCSV();" language="JavaScript" method="post">
   <FIELDSET style="width:400px; border:1px solid darkblue; height:170px">
      <LEGEND>Dados Pessoais</LEGEND>
      Nome:
      <INPUT type="text" name="nome" size="50" id="nome"><BR>
      Data de nascimento:<BR>
      <SELECT name="DNascDia" size="1">
         <OPTION selected></OPTION>
         <OPTION value="01">01</OPTION>
         <OPTION value="02">02</OPTION>
         <OPTION value="03">03</OPTION>
         <OPTION value="04">04</OPTION>
         <OPTION value="05">05</OPTION>
         <OPTION value="06">06</OPTION>
         <OPTION value="07">07</OPTION>
         <OPTION value="08">08</OPTION>
         <OPTION value="09">09</OPTION>
         <OPTION value="10">10</OPTION>
         <OPTION value="11">11</OPTION>
         <OPTION value="12">12</OPTION>
         <OPTION value="13">13</OPTION>
         <OPTION value="14">14</OPTION>
         <OPTION value="15">15</OPTION>
         <OPTION value="16">16</OPTION>
         <OPTION value="17">17</OPTION>
         <OPTION value="18">18</OPTION>
         <OPTION value="19">19</OPTION>
         <OPTION value="20">20</OPTION>
         <OPTION value="21">21</OPTION>
         <OPTION value="22">22</OPTION>
         <OPTION value="23">23</OPTION>
         <OPTION value="24">24</OPTION>
         <OPTION value="25">25</OPTION>
         <OPTION value="26">26</OPTION>
         <OPTION value="27">27</OPTION>
         <OPTION value="28">28</OPTION>
         <OPTION value="29">29</OPTION>
         <OPTION value="30">30</OPTION>
         <OPTION value="31">31</OPTION>
      </SELECT><SELECT name="DNascMes" size="1">
         <OPTION selected></OPTION>
         <OPTION value="01">Janeiro</OPTION>
         <OPTION value="02">Fevereiro</OPTION>
         <OPTION value="03">Março</OPTION>
         <OPTION value="04">Abril</OPTION>
         <OPTION value="05">Maio</OPTION>
         <OPTION value="06">Junho</OPTION>
         <OPTION value="07">Julho</OPTION>
         <OPTION value="08">Agosto</OPTION>
         <OPTION value="09">Setembro</OPTION>
         <OPTION value="10">Outubro</OPTION>
         <OPTION value="11">Novembro</OPTION>
         <OPTION value="12">Dezembro</OPTION>
      </SELECT><SELECT name="DNascAno" size="1">
         <OPTION selected></OPTION>
         <OPTION value="1970">1970</OPTION>
         <OPTION value="1971">1971</OPTION>
         <OPTION value="1972">1972</OPTION>
         <OPTION value="1973">1973</OPTION>
         <OPTION value="1974">1974</OPTION>
         <OPTION value="1975">1975</OPTION>
         <OPTION value="1976">1976</OPTION>
         <OPTION value="1977">1977</OPTION>
         <OPTION value="1978">1978</OPTION>
         <OPTION value="1979">1979</OPTION>
         <OPTION value="1980">1980</OPTION>
         <OPTION value="1981">1981</OPTION>
         <OPTION value="1982">1982</OPTION>
         <OPTION value="1983">1983</OPTION>
         <OPTION value="1984">1984</OPTION>
         <OPTION value="1985">1985</OPTION>
         <OPTION value="1986">1986</OPTION>
         <OPTION value="1987">1987</OPTION>
         <OPTION value="1988">1988</OPTION>
         <OPTION value="1989">1989</OPTION>
         <OPTION value="1990">1990</OPTION>
         <OPTION value="1991">1991</OPTION>
         <OPTION value="1992">1992</OPTION>
         <OPTION value="1993">1993</OPTION>
         <OPTION value="1994">1994</OPTION>
         <OPTION value="1995">1995</OPTION>
         <OPTION value="1996">1996</OPTION>
         <OPTION value="1997">1997</OPTION>
         <OPTION value="1998">1998</OPTION>
         <OPTION value="1999">1999</OPTION>
         <OPTION value="2000">2000</OPTION>
         <OPTION value="2001">2001</OPTION>
         <OPTION value="2002">2002</OPTION>
         <OPTION value="2003">2003</OPTION>
      </SELECT><BR>
      Sexo:<BR>
      <SELECT name="sexo" size="1">
         <OPTION selected></OPTION>
         <OPTION value="masculino">masculino</OPTION>
         <OPTION value="feminino">feminino</OPTION>
      </SELECT><BR>
      E-mail:<BR>
      <INPUT type="text" name="mail" size="50" id="mail"><BR>
      Observação.<BR>
      <INPUT type="text" name="UserLink" size="50" id="UserLink"><BR>
      
   
</TR>
<TR><TD valign="bottom" align="left"><INPUT type="submit" value="Cadastrar" name="send"><INPUT type="reset" value="Recomeçar" name="resetar"></TD>
</TR>
</TBODY>
</TABLE>
</FORM>
</BODY>
</HTML>





# vacinacao Form AP3
 PCA: SISTEMAS DE INFORMACAO DISTRIBUIDA - AP3
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>Formulário HTML</title>
    <meta charset="utf-8"/>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
    <form action="exibir-dados.php" class="formulario" method="post"> 
        <p> Consulta local de Vacinação Covid19</p>
        
        <div class="field">
            <label for="nome">Seu Nome:</label>
            <input type="text" id="nome" name="nome" placeholder="Digite seu nome*" required>
        </div>
        
        <div class="field">
            <label for="telefone">Seu Telefone:</label>
            <input type="text" id="telefone" name="telefone" placeholder="Digite seu Telefone">
        </div>

        <div class="field">
            <label for="email">Seu E-Mail:</label>
            <input type="email" id="email" name="email" placeholder="Digite seu E-Mail*" required>
        </div>        
        <div class="field radiobox">
            <span>Qual dose da vacina?</span>
            <input type="radio" name="novidades" id="sim" value="sim" checked><label for="sim">1 dose</label>
            <input type="radio" name="novidades" id="nao" value="nao"><label for="nao">2 dose </label>
        </div>
        <div class="field">
            <label for="mensagem">Alguma obeservação ?:</label>
            <textarea name="mensagem" id="mensagem" placeholder="Mensagem*" required></textarea>
        </div>

       


<button id="btn" onclick="alert(' foi enviado para  seu email  o local e data do seu agendamento para vacinação!.')">Enviar Email </button>
</body>
</html>



    </form>



</body>
</html>



.formulario{
    width: 400px;
    padding: 30px;
    border:1px solid #ccc;
}
.formulario p{
    width: 100%;
    font-size: 1.5em;
}
.field{
    width: 100%;
    margin: 15px 0;
}
.field label, 
.field span{
    padding-left: 10px;
    font-size: 1.1em;
    display: block;
    width: 100%;
}
.radiobox label{
    width: auto;
    display: inline-block;
}
input[type=text],
input[type=email],
textarea{
    width: 100%;
    padding-left: 10px;
    height: 30px;
    line-height: 30px;
    border-radius: 15px;
    border: 1px solid #ccc;
    outline: none;
}
input#nao{
    margin-left: 30px;
}
textarea{
    line-height: 20px;
    padding: 10px;
    height: 90px;
    resize: none;
}
input[type=submit]{
    display: block;
    background-color: #ccc;
    height: 35px;
    border: none;
    outline: 0;
    cursor: pointer;
    width: 100px;
    margin: 0 auto;
    text-align: center;
    border-radius: 15px;
