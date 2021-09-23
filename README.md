# gn-docker
re

Dzień dobry. Działam na komputerze zastępczym i nie mogę doprowadzić środowiska do porządku.
Za każdym razem, kiedy nadpisałem pliki js lub css, te nie chciały się zaktualizować w głównych plikach (coś nie tak z gulp lub browsersync) 
Pomagało tylko budowanie całego środowiska na nowo. (co długo trwało) 

Docker odmówił posłuszeństwa zapisania obrazu, dlatego wysyłam cały spakowany projekt oraz screeny potwierdzające wykonanie zadania 2 (dodani eprimary menu oraz jego elementów) 
oraz 7 (redirect 301 zrobiony za pomocą pluginu).

Zadanie 3 - rozwiązane w pliku priority-menu.js
Zadanie 4 - żądane elementy nie pojawiają się przy zmniejszeniu szerokości obrazu. 
zadanie 5 - menu "sticky" wystylizowane w pliku _menu-main-navigation.scss (działa poprawnie)

zadanie 6: 

$(window).scroll(function(element) {

    if ($(window).scrollTop() > 300) {
        $element.addClass('sticky');
    } else {
        $element.removeClass('sticky');
    }
});


zadanie 8 - brak rozwiązania 

zadanie 9 - strona ma problem z responsywnością oraz stylami. LCP zbyt wysokie FID zbyt wysokie (zalecana optymalizacja)




