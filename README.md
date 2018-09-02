# javascript_verk1
1. Hvað er null og undefined?
svar : null gæti þýtt ekki neitt eða bara tómt "value", undefined gæti verið breyta sem er til en hefur ekki útskýrt hvað "value" er.

2. Hvað gerir 'use strict' í JavaScript kóða?
svar: þegar maður gerir ´use strict' þá virkar ferlið eins og "strict mode" og þá verður ferlið strangara, t.d. þú mátt ekki gera óskýrar breytur, og þá fær maður minna af villum í kóðanum, 'use strict' var nýtt í ECMAScript 5.

3. Hver er munurinn á let og var?
svar :Ef þú býrð til var breytu fyrir for-lykkju eða hvað sem er, þá er enþá hægt að nota það í næsta dæmi, en ef þú myndirð gera let breytu þá er það ekki virkt fyrir önnur dæmi...

4. Skilgreindu fall á þrjá mismunandi vegu með kóðasýnidæmi.

svar: function fallnafn1(eihv1,eihv2){
        return eivh1,eivh2;
        }
        
      function fallnafn2(eitthvad1,eitthvad2,eitthvad3){
        var breyta1=eitthvad1+eitthvad2+eitthvad3;
        return breyta1;
        }
      var a = fallid(1,2);
      function fallid(b,c){
        return a+b;
}

5. Útskýrðu hvað eftirfarandi kóði gerir, hvað gera svigarnir?
 (function() { alert('Hello World'); })();
 svar :Ef þú skrifar "alert('hello world')" þá færðu popupp kassa sem segir 'Hello world', nema það sem við höfum er það sama bara í falli.
 
6. Í hvaða röð er kóðinn keyrður í raun eftir að JS þýðandinn (e. interpreter) er búinn að fá
hann til sín? Raðaðu kóðanum rétt fyrir JS þýðandanum. Afhverju er útkoman 8? Útskýrðu.
function foo(){
function bar() {
return 3;
}
return bar();
function bar() {
return 8;
}
}
alert(foo());
7. Hver er munurinn á for, for-in og for-of lykkjum?
svar :for-in og for-of hafa ekki sama sýnishorn á hvað 'value' er svo þeir skila ekki því sama eða í sumum tilföllum þá svara þeir sirka því sama.

8. forEach() Leystu lið 20 í Arrays á Udacity https://classroom.udacity.com/courses/ud803
svar:Búið.

9. Hvað gerir .map() fylkjaaðferðin? Leystu lið 22 í Arrays á Udacity
https://classroom.udacity.com/courses/ud803
svar: .map gefur rótina af tölunum sem eru gefnar upp. 

10. Leystu lið 25 í Arrays í lesson 6 á Udacity https://classroom.udacity.com/courses/ud803
