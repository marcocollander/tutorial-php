# Wstęp

PHP przeszedł długą drogę: od języka skryptowego używanego głównie do generowania dynamicznych stron, do dojrzałego
narzędzia wykorzystywanego w systemach o dużej skali, wysokich wymaganiach jakościowych i długim cyklu życia. Dzisiejszy
PHP nie jest już kompromisem ani wyborem „z braku alternatyw” — jest świadomą decyzją technologiczną, podejmowaną ze
względu na produktywność, ekosystem oraz dojrzałość narzędzi.

Współczesny PHP (8.x) to język:

* z rozbudowanym i konsekwentnym modelem obiektowym,
* z silnym, ekspresyjnym systemem typów,
* wspierający projektowanie oparte na niezmiennikach i kontraktach,
* dobrze integrujący się z narzędziami statycznej analizy, testów i automatyzacji.

Jednocześnie PHP zachował swoją pierwotną cechę: niski próg wejścia. To połączenie dostępności z zaawansowanymi
mechanizmami sprawia, że PHP jest językiem paradoksalnym — prostym na początku, ale wymagającym dyscypliny i wiedzy przy
projektowaniu systemów trwałych, czytelnych i odpornych na zmiany.

Celem tego tutoriala jest projektowanie: 
* rozumienie odpowiedzialności obiektów, 
* relacji pomiędzy nimi oraz 
* konsekwencji decyzji architektonicznych podejmowanych na wczesnym etapie projektu. 

PHP oferuje dziś wystarczająco dużo narzędzi, aby pisać zarówno kod chaotyczny, jak i kod o wysokiej jakości — różnicę 
robi wyłącznie sposób myślenia programisty.

Wzorce projektowe, omawiane w tym tutorialu, nie są receptami ani gotowymi schematami do bezrefleksyjnego kopiowania.
Stanowią raczej słownik pojęć pozwalający opisywać problemy projektowe oraz sprawdzone sposoby ich rozwiązywania. Ich
największą wartością jest ułatwienie komunikacji — zarówno z innymi programistami, jak i z przyszłą wersją samego
siebie, która będzie musiała utrzymywać i rozwijać istniejący kod.

Istotnym założeniem tej książki jest traktowanie PHP jako języka, w którym: 
* kompozycja jest preferowana nad dziedziczeniem, 
* typy są narzędziem projektowym, a nie formalnością, 
* niezmienność obiektów upraszcza logikę i testowanie, 
* architektura powinna być wspierana przez narzędzia, a nie przez konwencje „na słowo honoru”.

W kolejnych rozdziałach skupimy się na mechanizmach obiektowych PHP, ich konsekwencjach oraz na tym, jak wykorzystać je
do budowy systemów czytelnych, elastycznych i odpornych na zmiany. Omawiane techniki i wzorce nie są związane z
konkretnym frameworkiem — mają zastosowanie zarówno w małych projektach, jak i w dużych aplikacjach korporacyjnych.

Jeżeli czytasz ten tutorial, zakładamy, że chcesz pisać kod, który: 
* da się zrozumieć po miesiącach przerwy, 
* da się bezpiecznie modyfikować, 
* da się testować bez skomplikowanych obejść, 
* i który nie wymusza przepisywania całej aplikacji przy każdej istotnej zmianie wymagań.

PHP dostarcza dziś wszystkich niezbędnych narzędzi, aby było to możliwe. Pozostaje pytanie, jak z nich korzystać
świadomie. Na to pytanie ta książka próbuje odpowiedzieć.
