

# Introducción a Python

## Semana 3
<!-- .element style="text-align:center" -->

![alt text](./img/logo2.png) <!-- .element style="margin-left: auto; margin-right: auto; display: block" -->

---

# Enlaces:


- Tortuga: [https://pythonandturtle.com/turtle](https://pythonandturtle.com/turtle)
- Repl: [https://www.pythonmorsels.com/repl/](https://www.pythonmorsels.com/repl/)
- Presentaciones de las semanas anteriores:
  - [https://avast-python.github.io/semana-1](https://avast-python.github.io/semana-1)
  - [https://avast-python.github.io/semana-2](https://avast-python.github.io/semana-2)


---

### La programación son cinco cosas

1. ~~Secuencia~~ ✓
2. Condicionales <-
3. Repetición <-
4. Variables <-
5. Funciones

---

## Vuelta al `for`


```python
lado = 10
vueltas = 10
for num_vuelta in range(vueltas):
    t.forward(num_vuelta * lado)
    t.left(90)
```
<!-- .element style="font-size: 1em" -->

- Puedo usar variables para pintar
- Puedo acceder a `num_vuelta` dentro del bucle (no hace falta que se llame `num_vuelta`)
- Empieza en cero
- ¿Qué pintará esto?


--

# Ejercicio 1

```
lados = 4
largo_lado = 100

# Aquí tu código
```
<!-- .element style="font-size: 1em" -->

- Pinta un polígono de ese número de lados y con esa longitud
- Tiene que funcionar sin tener que modificar el programa aunque cambies las variables

![Ejercicio 1](./img/ejercicio_1.png) <!-- .element class="noborder center" -->

**Pista**: En un polígono regular todos los ángulos internos son iguales
y la suma es igual a 180° × (lados – 2).


**Extra**: Haz que en la base vaya un vértice, no una arista

---

# Ejercicio 2

![Ejercicio 2.1](./img/ejercicio_2_1.png) <!-- .element class="noborder center" -->

#### Extra: <!-- .element style="text-align:center" -->

![Ejercicio 2.2](./img/ejercicio_2_2.png) <!-- .element class="noborder center" -->
