# GameOfLive

## Temat: Projekt Gra w życie.

1. Wygląd aplikacji: 

![alt text](./img/main.png)

### Główny kod odpowiadający za tworzenie kolejnej generacji.

![alt text](./img/gen_code.png)


![alt text](./img/generowanie_klatek.png)

* funkcja generation() jest uruchamiana co 0.5s. 


![alt text](./img/gen_array.png)

* funkcja create2dArray(rows, cols) tworzy tablicę 2D [rows,cols], domyślnie wypełnioną wartością 0 ( wartość 0 przedstawiana jest na planszy jako pole czarne/nieżywe, natomiast wartość 1, to pole które jest koloru szarego/żywe)

![alt text](./img/neib.png)

* funkcja odpowiadająca za zliczanie sąsiadów.