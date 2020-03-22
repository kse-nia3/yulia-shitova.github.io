---
layout: post
title: Тест "Система маркетинговых коммуникаций"
---

<script type="text/javascript" language="JavaScript">// <![CDATA[
 var res="3222"; 
function check_me()
{
    var count=0;
    with(document.test) {
if (!Q1[0].checked&&!Q1[1].checked&&!Q1[2].checked&&!Q1[3].checked)  
{count+=1};  
if (!Q2[0].checked&&!Q2[1].checked&&!Q2[2].checked&&!Q2[3].checked)  
{count+=1};  
if (!Q3[0].checked&&!Q3[1].checked&&!Q3[2].checked&&!Q3[3].checked)  
{count+=1};  
if (!Q4[0].checked&&!Q4[1].checked&&!Q4[2].checked&&!Q4[3].checked)  
{count+=1};  
if (count>0) alert("Вы выполнили не все задания. Проверьте себя!")    
        else answer();
    }
} 
 
function control(k, f1,f2,f3,f4) {
if (k==1&&f1.checked) return true;
if (k==2&&f2.checked) return true;
if (k==3&&f3.checked) return true;
if (k==4&&f4.checked) return true;
return false;
}

function answer() {
answ="";
     with(document)    {
    answ+=control(res.charAt(0) ,test.Q1[0],test.Q1[1],test.Q1[2],test.Q1[3])?"1":"0";
answ+=control(res.charAt(1) ,test.Q2[0],test.Q2[1],test.Q2[2],test.Q2[3])?"1":"0";
answ+=control(res.charAt(2) ,test.Q3[0],test.Q3[1],test.Q3[2],test.Q3[3])?"1":"0";
answ+=control(res.charAt(3) ,test.Q4[0],test.Q4[1],test.Q4[2],test.Q4[3])?"1":"0";

showResult();
    }
}
 
function showResult()   {
    var nok=0;
    var i,s;
 
for (i=0; i<answ.length;i++) {nok+=answ.charAt(i)=="1"?1:0;}
if(nok==4) s="ОТЛИЧНО";
if(nok<4) s="ХОРОШО";
if(nok<3) s="УДОВЛЕТВОРИТЕЛЬНО";
if (nok<2) s="НЕУДОВЛЕТВОРИТЕЛЬНО";
    document.test.s1.
    value="Количество правильных ответов "+nok+". Ваша оценка "+s+". Посмотрите на окно рядом с номером вопроса. Если ответ правильный, там (+). Если ответ ошибочен, там (-).";
 
with(document.test)
    {
    if (answ.charAt(0)=="1") {T1.value=" + "} else {T1.value=" - "};
   if (answ.charAt(1)=="1") {T2.value=" + "} else {T2.value=" - "};
   if (answ.charAt(2)=="1") {T3.value=" + "} else {T3.value=" - "};
   if (answ.charAt(3)=="1") {T4.value=" + "} else {T4.value=" - "};
     }
}
function showhide(obj){
    if(obj == 'none') return 'inline';
    else return 'none';
}
// ]]>
</script>
<center><b>Система маркетинговых коммуникаций</b></center><br/><br/>
&nbsp;&nbsp;&nbsp;<span style="color:#006699;text-decoration:underline;cursor:pointer;" onclick="document.getElementById('instruction').style.display = showhide(document.getElementById('instruction').style.display)">
Инструкция</span>
 <br/>
<div id="instruction" style="display: none; width: 100%;">
<ul>
<li>Выберите один из вариантов в каждом из 4 вопросов;</li>
<li>Нажмите на кнопку "Показать результат";</li>
<li>Скрипт не покажет результат, пока Вы не ответите на все вопросы;</li>
<li>Загляните в окно рядом с номером задания. Если ответ правильный, то там (+). Если Вы ошиблись, там (-).</li>
<li>За каждый правильный ответ начисляется 1 балл;</li>
<li>Оценки: менее 2 баллов - НЕУДОВЛЕТВОРИТЕЛЬНО, от 2 но менее 3 - УДОВЛЕТВОРИТЕЛЬНО, 3 и менее 4 - ХОРОШО, 4 - ОТЛИЧНО;</li>
<li>Чтобы сбросить результат тестирования, нажать кнопку "Сбросить ответы";</li>
</ul>
</div>
<form name="test"><ol>
<li><INPUT type="text" size="1" value="" name="T1"/><b> 1. Бизнес-стратегия, предполагающая тщательное сегментирование целевого рынка фирмы, это</b><br/>
<input type="radio" value="0" name="Q1"/> современная стратегия бизнеса;<br />
<input type="radio" value="1" name="Q1"/> рыночно-ориентированная стратегия;<br />
<input type="radio" value="2" name="Q1"/> клиенто-ориентированная стратегия;<br />
<input type="radio" value="3" name="Q1"/> производственно-ориентированная стратегия.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T2"/><b> 2. Возникновение современной стратегии бизнеса относится к периоду</b><br/>
<input type="radio" value="0" name="Q2"/> 50-е гг. XX в.;<br />
<input type="radio" value="1" name="Q2"/> 90-е гг. XX в.;<br />
<input type="radio" value="2" name="Q2"/> 80-е гг. XX в.;<br />
<input type="radio" value="3" name="Q2"/> 2000-е гг. XX в.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T3"/><b> 3. В современной стратегии бизнеса глобальная конкуренция</b><br/>
<input type="radio" value="0" name="Q3"/> снижается;<br />
<input type="radio" value="1" name="Q3"/> растет;<br />
<input type="radio" value="2" name="Q3"/> не имеет значения;<br />
<input type="radio" value="3" name="Q3"/> остается на прежнем уровне.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T4"/><b> 4. Роман Якобсон опубликовал свою модель коммуникации в</b><br/>
<input type="radio" value="0" name="Q4"/> 1950 г.;<br />
<input type="radio" value="1" name="Q4"/> 1960 г.;<br />
<input type="radio" value="2" name="Q4"/> 1970 г.;<br />
<input type="radio" value="3" name="Q4"/> 1980 г..<br />
<br/></li></ol>      
<CENTER>
<P><TEXTAREA name="s1" rows="4" cols="70" readonly> </TEXTAREA> </P>
<INPUT onclick="check_me()" type="button" value="Показать результат"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<INPUT type="reset" value="Сбросить ответы"/> 
</CENTER>        
</form> 
<!-- Test created by service http://test.fromgomel.com -->
