## Sass notes
[Sass](http://sass-lang.com/guide) </br>

1. upravit typografiu
2. skontrolovat co vsetko upravuje centrovanie jednotlivych predmetov
4. obrazky tak ako treba

3. theme color na .class nie na buttons konkretne
5. grid 
6.media queries.





Spustenie watchera : sass --watch scss/css

1. mixins - @mixin nazov/ pouziva sa na zhromazdenie kodu ktory sa da potom aplikovat na rozne miesta. </br>
Pri definici mixinu sa da pouzit @content ktory umozni pri jednotlivych selectoroch pridat specificke stylingy.

2. & znak sa pouziva na oznacenie parent elementu, pouziva sa v nestingu

3. pouzivat nesting ale nie viac ako 2 urovne

4. Pouzivat variables.

5. Partials

6. Extend - rovnaky princip ako Flask/jinja2 extend template

!NEUPRAVOVAT .CSS SUBOR!


## Refactor
1. Break related sections into partials
2. Extract repeating patterns into extends
3. Nest rules where it makes sense
4. Create variables for repetitive values
5. Convert repeating declaration groups into mixins


