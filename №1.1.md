# PR1_Selynina_lab_rab_6
<!DOCTYPE html>
<html>
<head>
<script src="http://code.jquery.com/jquery-latest.js">
</script>
<script>
$(document).ready(function () 
{
$("#but1").click(function () 
{
$( '.MsoNormal:odd').hide();
});
$("#but2").click(function () 
{

$('.MsoNormal:odd').show();

});
});
</script>
</head>

<body>
<h2>Задание 1</h2>
<p class="MsoNormal">Четные элементы.</p>
<p class="MsoNormal">Нечетный элемент.</p>

<button id="but1">Скрыть</button>
<button id="but2">Развернуть</button>
</body>

</html>
