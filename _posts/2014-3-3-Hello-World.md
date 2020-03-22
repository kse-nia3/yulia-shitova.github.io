---
layout: post
title: Тест "Система маркетинговых коммуникаций"
---

<script type="text/javascript" language="JavaScript">// <![CDATA[
 var res="322231132233"; 
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
if (!Q5[0].checked&&!Q5[1].checked&&!Q5[2].checked&&!Q5[3].checked)  
{count+=1};  
if (!Q6[0].checked&&!Q6[1].checked&&!Q6[2].checked&&!Q6[3].checked)  
{count+=1};  
if (!Q7[0].checked&&!Q7[1].checked&&!Q7[2].checked&&!Q7[3].checked)  
{count+=1};  
if (!Q8[0].checked&&!Q8[1].checked&&!Q8[2].checked&&!Q8[3].checked)  
{count+=1};  
if (!Q9[0].checked&&!Q9[1].checked&&!Q9[2].checked&&!Q9[3].checked)  
{count+=1};  
if (!Q10[0].checked&&!Q10[1].checked&&!Q10[2].checked&&!Q10[3].checked)  
{count+=1};  
if (!Q11[0].checked&&!Q11[1].checked&&!Q11[2].checked&&!Q11[3].checked)  
{count+=1};  
if (!Q12[0].checked&&!Q12[1].checked&&!Q12[2].checked&&!Q12[3].checked)  
{count+=1};  
if (count>0) alert("Вы выполнили не все задания. Проверьте себя!")    
        else answer();
    }
} 
 
function control(k, f1,f2,f3,f4,f5,f6,f7,f8,f9,f10,f11,f12) {
if (k==1&&f1.checked) return true;
if (k==2&&f2.checked) return true;
if (k==3&&f3.checked) return true;
if (k==4&&f4.checked) return true;
if (k==5&&f5.checked) return true;
if (k==6&&f6.checked) return true;
if (k==7&&f7.checked) return true;
if (k==8&&f8.checked) return true;
if (k==9&&f9.checked) return true;
if (k==10&&f10.checked) return true;
if (k==11&&f11.checked) return true;
if (k==12&&f12.checked) return true;
return false;
}

function answer() {
answ="";
     with(document)    {
    answ+=control(res.charAt(0) ,test.Q1[0],test.Q1[1],test.Q1[2],test.Q1[3])?"1":"0";
answ+=control(res.charAt(1) ,test.Q2[0],test.Q2[1],test.Q2[2],test.Q2[3])?"1":"0";
answ+=control(res.charAt(2) ,test.Q3[0],test.Q3[1],test.Q3[2],test.Q3[3])?"1":"0";
answ+=control(res.charAt(3) ,test.Q4[0],test.Q4[1],test.Q4[2],test.Q4[3])?"1":"0";
answ+=control(res.charAt(4) ,test.Q5[0],test.Q5[1],test.Q5[2],test.Q5[3])?"1":"0";
answ+=control(res.charAt(5) ,test.Q6[0],test.Q6[1],test.Q6[2],test.Q6[3])?"1":"0";
answ+=control(res.charAt(6) ,test.Q7[0],test.Q7[1],test.Q7[2],test.Q7[3])?"1":"0";
answ+=control(res.charAt(7) ,test.Q8[0],test.Q8[1],test.Q8[2],test.Q8[3])?"1":"0";
answ+=control(res.charAt(8) ,test.Q9[0],test.Q9[1],test.Q9[2],test.Q9[3])?"1":"0";
answ+=control(res.charAt(9) ,test.Q10[0],test.Q10[1],test.Q10[2],test.Q10[3])?"1":"0";
answ+=control(res.charAt(10) ,test.Q11[0],test.Q11[1],test.Q11[2],test.Q11[3])?"1":"0";
answ+=control(res.charAt(11) ,test.Q12[0],test.Q12[1],test.Q12[2],test.Q12[3])?"1":"0";

showResult();
    }
}
 
function showResult()   {
    var nok=0;
    var i,s;
 
for (i=0; i<answ.length;i++) {nok+=answ.charAt(i)=="1"?1:0;}
if(nok==12) s="ОТЛИЧНО";
if(nok<12) s="ХОРОШО";
if(nok<9) s="УДОВЛЕТВОРИТЕЛЬНО";
if (nok<6) s="НЕУДОВЛЕТВОРИТЕЛЬНО";
    document.test.s1.
    value="Количество правильных ответов "+nok+". Ваша оценка "+s+". Посмотрите на окно рядом с номером вопроса. Если ответ правильный, там (+). Если ответ ошибочен, там (-).";
 
with(document.test)
    {
    if (answ.charAt(0)=="1") {T1.value=" + "} else {T1.value=" - "};
   if (answ.charAt(1)=="1") {T2.value=" + "} else {T2.value=" - "};
   if (answ.charAt(2)=="1") {T3.value=" + "} else {T3.value=" - "};
   if (answ.charAt(3)=="1") {T4.value=" + "} else {T4.value=" - "};
   if (answ.charAt(4)=="1") {T5.value=" + "} else {T5.value=" - "};
   if (answ.charAt(5)=="1") {T6.value=" + "} else {T6.value=" - "};
   if (answ.charAt(6)=="1") {T7.value=" + "} else {T7.value=" - "};
   if (answ.charAt(7)=="1") {T8.value=" + "} else {T8.value=" - "};
   if (answ.charAt(8)=="1") {T9.value=" + "} else {T9.value=" - "};
   if (answ.charAt(9)=="1") {T10.value=" + "} else {T10.value=" - "};
   if (answ.charAt(10)=="1") {T11.value=" + "} else {T11.value=" - "};
   if (answ.charAt(11)=="1") {T12.value=" + "} else {T12.value=" - "};
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
<li>Выберите один из вариантов в каждом из 12 вопросов;</li>
<li>Нажмите на кнопку "Показать результат";</li>
<li>Скрипт не покажет результат, пока Вы не ответите на все вопросы;</li>
<li>Загляните в окно рядом с номером задания. Если ответ правильный, то там (+). Если Вы ошиблись, там (-).</li>
<li>За каждый правильный ответ начисляется 1 балл;</li>
<li>Оценки: менее 6 баллов - НЕУДОВЛЕТВОРИТЕЛЬНО, от 6 но менее 9 - УДОВЛЕТВОРИТЕЛЬНО, 9 и менее 12 - ХОРОШО, 12 - ОТЛИЧНО;</li>
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
<input type="radio" value="0" name="Q4"/> 1950<br />
<input type="radio" value="1" name="Q4"/> 1960<br />
<input type="radio" value="2" name="Q4"/> 1970<br />
<input type="radio" value="3" name="Q4"/> 1980<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T5"/><b>  5. В модели коммуникации Романа Якобсона взаимодействуют</b><br/>
<input type="radio" value="0" name="Q5"/> четыре компонента;<br />
<input type="radio" value="1" name="Q5"/> пять компонентов;<br />
<input type="radio" value="2" name="Q5"/> шесть компонентов;<br />
<input type="radio" value="3" name="Q5"/> семь компонентов.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T6"/><b> 6. Какой компонент не входит в число взаимодействующих элементов модели коммуникации Романа Якобсона</b><br/>
<input type="radio" value="0" name="Q6"/> посредник;<br />
<input type="radio" value="1" name="Q6"/> код;<br />
<input type="radio" value="2" name="Q6"/> контакт;<br />
<input type="radio" value="3" name="Q6"/> сообщение.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T7"/><b> 7. В модели речевой коммуникации адресантом является</b><br/>
<input type="radio" value="0" name="Q7"/> источник сообщения;<br />
<input type="radio" value="1" name="Q7"/> получатель сообщения;<br />
<input type="radio" value="2" name="Q7"/> специфические обстоятельства, которые характеризуют данную коммуникацию;<br />
<input type="radio" value="3" name="Q7"/> то, что передается адресату.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T8"/><b> 8. Маркетинговые коммуникации — это</b><br/>
<input type="radio" value="0" name="Q8"/> процесс обмена информацией между фирмой и другими субъектами маркетинговой деятельности;<br />
<input type="radio" value="1" name="Q8"/> процесс распространения информации о деятельности фирмы с целью продвижения на рынок ее товаров;<br />
<input type="radio" value="2" name="Q8"/> процесс обмена информацией между фирмой и другими субъектами маркетинговой деятельности с целью представления и совершенствования деятельности фирмы и ее товаров.<br />
<input type="radio" value="3" name="Q8"/> первые три варианта вместе<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T9"/><b> 9. Продвижение — это</b><br/>
<input type="radio" value="0" name="Q9"/> маркетинговая компания по внедрению на рынок нового товара;<br />
<input type="radio" value="1" name="Q9"/> совокупность различных видов деятельности по доведению информации о достоинствах продукта до потенциальных потребителей и стимулированию возникновения у них желания его купить;<br />
<input type="radio" value="2" name="Q9"/> совокупность различных видов деятельности по стимулированию у потребителей потребности купить данный товар;<br />
<input type="radio" value="3" name="Q9"/> реклама и другие методы, позволяющие добиться повышения спроса на определенный вид товаров.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T10"/><b> 10. Целями продвижения являются (отметьте лишнее)</b><br/>
<input type="radio" value="0" name="Q10"/> формирование спроса и стимулирования сбыта;<br />
<input type="radio" value="1" name="Q10"/> уменьшение целевого рынка фирмы;<br />
<input type="radio" value="2" name="Q10"/> увеличение объема продаж;<br />
<input type="radio" value="3" name="Q10"/> создание и укрепление имиджа фирмы.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T11"/><b> 11. Представляют собой систему побудительных мер и приемов, носящих кратковременный характер и направленных на поощрение покупки или продажи товара</b><br/>
<input type="radio" value="0" name="Q11"/> рекламные акции;<br />
<input type="radio" value="1" name="Q11"/> связи с общественностью;<br />
<input type="radio" value="2" name="Q11"/> мероприятия стимулирования сбыта;<br />
<input type="radio" value="3" name="Q11"/> личные продажи.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T12"/><b> 12. Мерчендайзинг — это</b><br/>
<input type="radio" value="0" name="Q12"/> предложение различных видов скидок;<br />
<input type="radio" value="1" name="Q12"/> проведение рекламных викторин, лотерей и т.д.;<br />
<input type="radio" value="2" name="Q12"/> оформление места продажи;<br />
<input type="radio" value="3" name="Q12"/> раздача фирменных сувениров.<br />
<br/></li></ol>      
<CENTER>
<P><TEXTAREA name="s1" rows="4" cols="70" readonly> </TEXTAREA> </P>
<INPUT onclick="check_me()" type="button" value="Показать результат"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<INPUT type="reset" value="Сбросить ответы"/> 
</CENTER>        
</form> 
<!-- Test created by service http://test.fromgomel.com -->


---
layout: post
title: Тест "Эффективность рекламной кампании"
---

<script type="text/javascript" language="JavaScript">// <![CDATA[
 var res="34124"; 
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
if (!Q5[0].checked&&!Q5[1].checked&&!Q5[2].checked&&!Q5[3].checked)  
{count+=1};  
if (count>0) alert("Вы выполнили не все задания. Проверьте себя!")    
        else answer();
    }
} 
 
function control(k, f1,f2,f3,f4,f5) {
if (k==1&&f1.checked) return true;
if (k==2&&f2.checked) return true;
if (k==3&&f3.checked) return true;
if (k==4&&f4.checked) return true;
if (k==5&&f5.checked) return true;
return false;
}

function answer() {
answ="";
     with(document)    {
    answ+=control(res.charAt(0) ,test.Q1[0],test.Q1[1],test.Q1[2],test.Q1[3])?"1":"0";
answ+=control(res.charAt(1) ,test.Q2[0],test.Q2[1],test.Q2[2],test.Q2[3])?"1":"0";
answ+=control(res.charAt(2) ,test.Q3[0],test.Q3[1],test.Q3[2],test.Q3[3])?"1":"0";
answ+=control(res.charAt(3) ,test.Q4[0],test.Q4[1],test.Q4[2],test.Q4[3])?"1":"0";
answ+=control(res.charAt(4) ,test.Q5[0],test.Q5[1],test.Q5[2],test.Q5[3])?"1":"0";

showResult();
    }
}
 
function showResult()   {
    var nok=0;
    var i,s;
 
for (i=0; i<answ.length;i++) {nok+=answ.charAt(i)=="1"?1:0;}
if(nok==5) s="ОТЛИЧНО";
if(nok<5) s="ХОРОШО";
if(nok<3.75) s="УДОВЛЕТВОРИТЕЛЬНО";
if (nok<2.5) s="НЕУДОВЛЕТВОРИТЕЛЬНО";
    document.test.s1.
    value="Количество правильных ответов "+nok+". Ваша оценка "+s+". Посмотрите на окно рядом с номером вопроса. Если ответ правильный, там (+). Если ответ ошибочен, там (-).";
 
with(document.test)
    {
    if (answ.charAt(0)=="1") {T1.value=" + "} else {T1.value=" - "};
   if (answ.charAt(1)=="1") {T2.value=" + "} else {T2.value=" - "};
   if (answ.charAt(2)=="1") {T3.value=" + "} else {T3.value=" - "};
   if (answ.charAt(3)=="1") {T4.value=" + "} else {T4.value=" - "};
   if (answ.charAt(4)=="1") {T5.value=" + "} else {T5.value=" - "};
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
<li>Выберите один из вариантов в каждом из 5 вопросов;</li>
<li>Нажмите на кнопку "Показать результат";</li>
<li>Скрипт не покажет результат, пока Вы не ответите на все вопросы;</li>
<li>Загляните в окно рядом с номером задания. Если ответ правильный, то там (+). Если Вы ошиблись, там (-).</li>
<li>За каждый правильный ответ начисляется 1 балл;</li>
<li>Оценки: менее 2.5 баллов - НЕУДОВЛЕТВОРИТЕЛЬНО, от 2.5 но менее 3.75 - УДОВЛЕТВОРИТЕЛЬНО, 3.75 и менее 5 - ХОРОШО, 5 - ОТЛИЧНО;</li>
<li>Чтобы сбросить результат тестирования, нажать кнопку "Сбросить ответы";</li>
</ul>
</div>
<form name="test"><ol>
<li><INPUT type="text" size="1" value="" name="T1"/><b> 1. Основным материалом для анализа экономической эффективности результатов рекламных мероприятий фирмы служат</b><br/>
<input type="radio" value="0" name="Q1"/> рейтинги рекламы на радио и ТВ;<br />
<input type="radio" value="1" name="Q1"/> статистические данные о затратах на рекламные акции;<br />
<input type="radio" value="2" name="Q1"/> статистические и бухгалтерские данные о росте товарооборота;<br />
<input type="radio" value="3" name="Q1"/> данные о количестве новых покупателей после размещения рекламы.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T2"/><b> 2. Отметьте, какой метод определения эффективности рекламной кампании не относится к экономическим методам</b><br/>
<input type="radio" value="0" name="Q2"/> товарооборот до проведения рекламной кампании в определенном временном периоде;<br />
<input type="radio" value="1" name="Q2"/> товарооборот в определенном рекламном периоде;<br />
<input type="radio" value="2" name="Q2"/> средний дневной оборот в вышерассматриваемых периодах;<br />
<input type="radio" value="3" name="Q2"/> изучение степени внимания к конкретному рекламному носителю посредством наблюдения.<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T3"/><b>  3. Основными методами изучения эффективности психологического воздействия рекламы являются</b><br/>
<input type="radio" value="0" name="Q3"/> наблюдение и опрос;<br />
<input type="radio" value="1" name="Q3"/> изучение документов и отчетов;<br />
<input type="radio" value="2" name="Q3"/> изучение рейтингов рекламы.<br />
<input type="radio" value="3" name="Q3"/> -<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T4"/><b> 4. Какой способ изучения эффективности психологического воздействия рекламы является наиболее объективным</b><br/>
<input type="radio" value="0" name="Q4"/> наблюдение;<br />
<input type="radio" value="1" name="Q4"/> опрос определенного числа людей по заранее подготовленной анкете;<br />
<input type="radio" value="2" name="Q4"/> опрос потребителей.<br />
<input type="radio" value="3" name="Q4"/> -<br />
<br/></li><li><INPUT type="text" size="1" value="" name="T5"/><b>  5. К видам осведомленности о товаре (услуге) не относится</b><br/>
<input type="radio" value="0" name="Q5"/> неподсказанное знание марки;<br />
<input type="radio" value="1" name="Q5"/> первое спонтанное знание марки;<br />
<input type="radio" value="2" name="Q5"/> подсказанное знание марки;<br />
<input type="radio" value="3" name="Q5"/> осмысленное знание марки.<br />
<br/></li></ol>      
<CENTER>
<P><TEXTAREA name="s1" rows="4" cols="70" readonly> </TEXTAREA> </P>
<INPUT onclick="check_me()" type="button" value="Показать результат"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<INPUT type="reset" value="Сбросить ответы"/> 
</CENTER>        
</form> 
<!-- Test created by service http://test.fromgomel.com -->
