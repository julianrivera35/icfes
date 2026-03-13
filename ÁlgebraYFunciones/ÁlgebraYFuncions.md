# Material de Clase Pre-ICFES: Álgebra y Funciones

## 1. Construcción de expresiones algebraicas equivalentes
### Teoría
Dos expresiones son equivalentes si producen el mismo valor para todo valor permitido de la variable (excepto donde no estén definidas).  
Operaciones permitidas:
- Factorización (factor común, diferencia de cuadrados, trinomios, cubos perfectos).
- Simplificación de fracciones racionales (cancelación de factores comunes).
- Expansión (distributiva).
- Completar el cuadrado.

**Fórmulas clave:**
- Diferencia de cuadrados: \( a^2 - b^2 = (a - b)(a + b) \)
- Trinomio cuadrático: \( ax^2 + bx + c = a(x - r_1)(x - r_2) \) (si se conocen raíces)
- Cubo perfecto: \( a^3 \pm b^3 = (a \pm b)(a^2 \mp ab + b^2) \)

### Ejemplos resueltos
**Ejemplo 1:** Simplificar \( \frac{x^2 - 9}{x^2 + 5x + 6} \)
\[
\frac{(x-3)(x+3)}{(x+2)(x+3)} = \frac{x-3}{x+2} \quad (x \neq -3)
\]

**Ejemplo 2:** Factorizar \( 2x^3 - 16 = 2(x^3 - 8) = 2(x-2)(x^2 + 2x + 4) \)

**Ejemplo 3:** Expresión equivalente de \( (x+3)^2 - 4(x+1) \)
\[
x^2 + 6x + 9 - 4x - 4 = x^2 + 2x + 5
\]

**Ejercicio para practicar:** Factoriza y simplifica \( \frac{2x^3 - 8x}{x^2 - 4} \). (Respuesta: \( 2x \), \( x \neq \pm 2 \))

---

## 2. Pendiente de una recta y de una curva (media e instantánea)
### Teoría
Pendiente media entre dos puntos \( (x_1, y_1) \) y \( (x_2, y_2) \):
\[
m = \frac{y_2 - y_1}{x_2 - x_1}
\]
Pendiente instantánea en un punto: límite de la pendiente media cuando el segundo punto se acerca (concepto de derivada).

**Ecuación de la recta tangente** en un punto \( (a, f(a)) \):
\[
y - f(a) = f'(a)(x - a)
\]

### Ejemplos
**Ejemplo 1:** Pendiente media de \( f(x) = x^2 \) entre \( x=1 \) y \( x=3 \):
\[
m = \frac{9 - 1}{3 - 1} = 4
\]

**Ejemplo 2:** Recta tangente a \( f(x) = x^2 \) en \( x=2 \) (derivada \( f'(x) = 2x \), \( f'(2)=4 \)):
\[
y - 4 = 4(x - 2) \implies y = 4x - 4
\]

**Ejercicio:** Hallar la pendiente instantánea de \( f(x) = 3x^2 - 2x \) en \( x=1 \) (Respuesta: 4)

---

## 3. Funciones polinómicas (todos los órdenes)
### Teoría
- Grado 1: lineal → recta
- Grado 2: cuadrática → parábola (vértice, forma canónica)
- Grado 3: cúbica → punto de inflexión
Forma canónica cuadrática:
\[
y = a(x - h)^2 + k \quad \text{(vértice en } (h,k)\text{)}
\]
Vértice fórmula: \( x = -\frac{b}{2a} \)

**Dominio:** todos los reales  
**Rango:** depende del signo de \( a \)

### Ejemplos
**Ejemplo:** Dada la gráfica que pasa por \( (-1,0) \), \( (1,4) \), \( (0,3) \), encontrar la función cuadrática.
Sistema:
\[
a + b + c = 3, \quad a - b + c = 0, \quad a - b + c = 4 \quad \text{(sol: } y = x^2 + 2x + 3\text{)}
\]

**Ejercicio:** Convertir \( y = x^2 + 6x + 5 \) a forma canónica (Respuesta: \( y = (x+3)^2 - 4 \))

---

## 4. Funciones racionales
### Teoría
Forma \( f(x) = \frac{P(x)}{Q(x)} \).  
Asíntotas verticales: raíces del denominador.  
Asíntota horizontal: comparar grados.

### Ejemplo
\( f(x) = \frac{x-1}{x+2} \): asíntota vertical \( x=-2 \), horizontal \( y=1 \).

---

## 5. Funciones exponenciales y logarítmicas
### Teoría
Exponencial: \( y = a \cdot b^x \) o \( y = a e^{kx} \)  
Logarítmica: inversa, \( y = \log_b x \)

Despeje de \( t \) en exponencial:
\[
P(t) = 200 e^{0.2t} = 400 \implies e^{0.2t} = 2 \implies 0.2t = \ln 2 \implies t = \frac{\ln 2}{0.2} \approx 3.465
\]

**Dominio:** todos los reales (exp), \( x>0 \) (log)  
**Rango:** \( y>0 \) (exp), todos los reales (log)

### Ejemplo de modelado
Población: \( P(t) = 200 e^{0.2t} \). ¿Cuándo duplica? (Respuesta: \( t \approx 3.465 \) años)

---

## 6. Funciones trigonométricas (seno, coseno, tangente)
### Teoría
- \( y = A \sin(Bx + C) + D \)
- Periodo: \( \frac{2\pi}{|B|} \)
- Amplitud: \( |A| \)
- Desplazamiento de fase: \( -\frac{C}{B} \)

Propiedades:
- \( \sin^2 x + \cos^2 x = 1 \)
- Dominio: todos los reales
- Rango: \([-1,1]\) (sen/cos), todos los reales (tan)
- Periodo seno/cos: \( 2\pi \), tan: \( \pi \)

**Derivadas:**
- \( \frac{d}{dx} \sin x = \cos x \)
- \( \frac{d}{dx} \cos x = -\sin x \)
- \( \frac{d}{dx} \tan x = \sec^2 x \)

### Ejemplo modelado péndulo
Oscilación: \( \theta(t) = 0.3 \sin\left(\frac{2\pi t}{1.8}\right) \)  
Periodo = 1.8 s (fórmula física \( T=2\pi\sqrt{L/g} \approx 1.8 \) s si \( L \approx 0.8 \) m)

**Ejercicio:** Hallar periodo de \( y = 5 \cos(3x - \pi/2) \) (Respuesta: \( \frac{2\pi}{3} \))

---

## 7. Modelado de variación periódica y derivadas
Velocidad instantánea = derivada de posición.  
Aceleración = derivada segunda.

**Ejemplo:** Posición péndulo \( x(t) = 0.3 \sin(3.5 t) \). Velocidad en \( t=0 \): \( v(0) = 0.3 \cdot 3.5 \cdot \cos(0) = 1.05 \) m/s

---

## 8. Magnitudes medias (velocidad media, aceleración media, densidad media)
Velocidad media: \( v_m = \frac{\Delta x}{\Delta t} = \frac{f(b)-f(a)}{b-a} \)  
Aceleración media: \( a_m = \frac{\Delta v}{\Delta t} \)  
Densidad media: \( \rho_m = \frac{m}{V} \)

**Ejemplo:** Densidad media de una barra de longitud 2 m con masa \( m(x) = x^2 + 1 \):  
\( \rho_m = \frac{m(2)-m(0)}{2} = \frac{5}{2} = 2.5 \) kg/m

---

## 9. Sistemas de ecuaciones (lineales y no lineales)
Métodos: sustitución, eliminación, igualación.

**Ejemplo:** Resolver
\[
\begin{cases}
y = x^2 - 3 \\
y = 2x + 1
\end{cases}
\]
\( x^2 - 3 = 2x + 1 \implies x^2 - 2x - 4 = 0 \implies x = 1 \pm \sqrt{5} \)

---

## 10. Resumen de propiedades importantes
| Función       | Dominio       | Rango              | Periodo   | Asíntotas / Vértice          |
|---------------|---------------|--------------------|-----------|------------------------------|
| Lineal        | \(\mathbb{R}\) | \(\mathbb{R}\)     | -         | -                            |
| Cuadrática    | \(\mathbb{R}\) | depende de \(a\)   | -         | Vértice \( (-\frac{b}{2a}, \dots) \) |
| Exponencial   | \(\mathbb{R}\) | \( (0,\infty) \)   | -         | Horizontal \( y=0 \)         |
| Logarítmica   | \( (0,\infty) \) | \(\mathbb{R}\) | -         | Vertical \( x=0 \)           |
| Seno/Coseno   | \(\mathbb{R}\) | \([-1,1]\)         | \( 2\pi \) | -                            |
| Tangente      | \(\mathbb{R} \setminus \frac{\pi}{2} + k\pi \) | \(\mathbb{R}\) | \( \pi \) | Verticales en \( \frac{\pi}{2} + k\pi \) |

---

**Ejercicios finales de síntesis (para resolver cualquier ítem ICFES):**
1. Factoriza y simplifica \( \frac{x^4 - 16}{x^2 + 4x + 4} \).
2. Encuentra la recta tangente a \( y = e^{2x} \) en \( x=0 \).
3. Modelo de crecimiento: población 5000, crece al 3% anual. ¿Cuándo llega a 8000? (usa \( e \)).
4. Periodo y amplitud de \( \theta(t) = 12 \sin(4\pi t) \).
5. Velocidad media de \( s(t) = t^3 - 2t \) entre \( t=1 \) y \( t=3 \).
6. Sistema: \( x^2 + y = 5 \), \( x + y = 3 \).