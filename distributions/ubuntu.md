<script>
function op(obj) {
x=document.getElementById(obj);
if(x.style.display == "none") x.style.display = "block";
else x.style.display = "none"
}
</script>
<a href="/" onClick="op('div1'); return false;"> Показать \Скрыть</a>
<div id="div1" style="display:none">Скрытый или показаный  текст  =)</div>
