# Snake
Jednoduchá webová hra, která byla vytvořena pomocí JavaScriptu (samozřejmě také pomocí html a css).
# **Co kód obsahuje a jak funguje?**
## **Proměné**</br>
**blockSize** určuje velikost každého jednotlivého bloku ve hře.</br>
**snakeX** a **snakeY** představují počáteční pozici hlavy hada.</br>
**foodX** a **foodY** představují náhodnou pozici jídla na hrací ploše.</br>
a další...</br>
## **Funkce**</br>
### **Funkce window.onload**
Funkce window.onload se volá při načítání stránky, čeká, až bude vše připraveno (canvas, obrázky atd.), než spustí samotnou hru.</br>
### **Funkce update**
Funkce update je **srdcem** hry.  Neustále běží a stará se o to, aby se hra plynule hýbala a reagovala na hráčovy akce. Kontroluje konec hry, kreslení jídla, zvětšení hada, posun těla hada, apod.
### **Funkce changeDirection**
Stará se o změnu směru.
