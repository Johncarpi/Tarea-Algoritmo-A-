# Tarea-Algoritmo-A- 
![Croquis](https://github.com/Johncarpi/Tarea-Algoritmo-A-/assets/150828183/8beab5af-9c44-4f6e-b1f9-ef667ab96118)

![Solución A](https://github.com/Johncarpi/Tarea-Algoritmo-A-/assets/150828183/feb6f0b0-8b44-45cc-a220-12a21ae12f75)

![1707733416931](https://github.com/Johncarpi/Tarea-Algoritmo-A-/assets/150828183/cb281d08-f550-489f-ba52-ad62e0efcbda)



1- Interación: Empezamos desde el nodo A ya que hera el único nodo disponible:
Cerrados{A}    Frontera{B,C}

2- Interación: Expandimos al nodo C ya que es el nodo con la f más favorable: 
Cerrados{A,C}    Frontera{B,E,F}

3- Interación: Expandimos al nodo F ya que es el nodo con la f más favorable: 
Cerrados{A,C,F}    Frontera{B,E,H,I}

4- Interación: Expandimos al nodo B ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B}    Frontera{E,H,I,J,E}

5- Interación: Expandimos al nodo J ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J}    Frontera{E,H,I,K}

6- Interación: Expandimos al nodo K ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K}    Frontera{E,H,I,L}

7- Interación: Expandimos al nodo E ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E}    Frontera{I,L,B,H}

8- Interación: Expandimos al nodo I ya que es el nodo con la f más favorable:  
Cerrados{A,C,F,B,J,K,E,I}    Frontera{L,H,M}

9- Interación: Expandimos al nodo H ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H}    Frontera{L,M,E}

10- Interación: Expandimos al nodo L ya que es el nodo con la f más favorable:  
Cerrados{A,C,F,B,J,K,E,I,H,L}    Frontera{M,N}

11- Interación: Expandimos al nodo M ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M}    Frontera{N,Ñ}

12- Interación: Expandimos al nodo N ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N}    Frontera{Ñ,O}

13- Interación: Expandimos al nodo Ñ ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N,Ñ}  Frontera{O,P}  

14- Interación: Expandimos al nodo P ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N,Ñ,P}  Frontera{O,Q}  

15- Interación: Expandimos al nodo Q ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N,Ñ,P,Q}  Frontera{O,R} 

16- Interación: Expandimos al nodo R ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N,Ñ,P,Q,R}  Frontera{O}  

17- Interación: Expandimos al nodo O ya que es el nodo con la f más favorable: 
Cerrados{A,C,F,B,J,K,E,I,H,L,M,N,Ñ,P,Q,R,O} FRontera{}
