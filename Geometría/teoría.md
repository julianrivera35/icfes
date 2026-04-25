# Sólidos Congruentes y Semejantes  
## Matemáticas – Grado 11° – Preparación ICFES  
(Basado en Saberes 11 – CEINFES)

---

## 1. Introducción a los sólidos geométricos

En geometría espacial, los **sólidos** (o cuerpos geométricos) son figuras tridimensionales que ocupan un volumen en el espacio. Se clasifican en **poliedros** (caras planas, como prismas y pirámides) y **cuerpos de revolución** (superficies curvas generadas por rotación, como cilindros, conos y esferas).

Para resolver problemas del ICFES es fundamental distinguir entre **sólidos congruentes** y **sólidos semejantes**, ya que estas relaciones permiten comparar formas, tamaños, áreas y volúmenes. Además, se estudian elementos como la **generatriz**, áreas lateral y total, y volúmenes de los sólidos más comunes.

---

## 2. Sólidos Congruentes

Dos sólidos son **congruentes** si son **exactamente iguales** en forma y tamaño, independientemente de su posición o rotación en el espacio. Es decir, uno puede superponerse perfectamente al otro mediante movimientos rígidos (traslaciones, rotaciones o reflexiones).

### Características principales:
- Tienen la **misma forma** y el **mismo tamaño**.
- Sus **aristas (lados) correspondientes** son iguales en longitud.
- Sus **ángulos correspondientes** (diédricos o triedros) son iguales.
- Sus **áreas superficiales** son iguales.
- Sus **volúmenes** son iguales.

**Ejemplo práctico:**  
Dos dados idénticos de un juego de mesa son congruentes. Aunque uno esté girado, sus seis caras cuadradas miden lo mismo, sus aristas miden igual y su volumen es idéntico.  
Otro ejemplo: las dos ruedas delanteras de un automóvil (si son del mismo modelo y no están desgastadas) son congruentes.

**Representación:**  
Si dos sólidos A y B son congruentes, se denota A ≅ B.

**Importancia en el ICFES:**  
Permite reconocer que, si dos figuras son congruentes, cualquier medida calculada en una sirve exactamente para la otra (área, volumen, longitudes).

---

## 3. Sólidos Semejantes

Dos sólidos son **semejantes** si tienen la **misma forma**, pero **tamaños diferentes**. Uno es una versión “escalada” del otro.

### Características principales:
- Tienen la **misma forma** (ángulos correspondientes iguales).
- Las **medidas lineales correspondientes** (aristas, alturas, radios, generatrices) guardan una **razón de proporcionalidad constante**, llamada **razón de semejanza** (k).
- Las **áreas superficiales** son proporcionales al **cuadrado** de la razón de semejanza (k²).
- Los **volúmenes** son proporcionales al **cubo** de la razón de semejanza (k³).

**Ejemplo práctico:**  
Un modelo a escala de un automóvil (1:50) y el automóvil real son semejantes. Si el modelo mide 10 cm de largo, el real mide 5 metros (razón k = 50). Todas las longitudes se multiplican por 50, las áreas por 2500 y los volúmenes por 125000.

**Fórmulas clave para sólidos semejantes:**
- Si razón de semejanza = k  
  → Longitudes: multiplicar por k  
  → Áreas: multiplicar por k²  
  → Volúmenes: multiplicar por k³

**Ejemplo numérico:**  
Dos pirámides son semejantes con razón k = 2.  
Si la pirámide pequeña tiene volumen 27 cm³, la grande tiene volumen 27 × 2³ = 27 × 8 = 216 cm³.  
Si el área lateral de la pequeña es 36 cm², la de la grande es 36 × 2² = 36 × 4 = 144 cm².

---

## 4. Elementos comunes en sólidos de revolución y poliedros

### Generatriz
- En un **cilindro** o **cono**: es la línea recta que genera la superficie lateral al rotar (en el cono es la distancia desde el vértice hasta un punto del borde de la base; en el cilindro es la altura).
- Se calcula frecuentemente con el **Teorema de Pitágoras**: g = √(r² + h²) en un cono recto.

### Área Lateral (A_L)
- Superficie que no incluye las bases.

### Área Total (A_T)
- A_L + áreas de las bases.

### Volumen (V)
- Espacio interior que ocupa el sólido.

---

## 5. Cilindros

**Elementos:**
- Dos bases circulares paralelas e iguales (radio r).
- Altura h (distancia entre bases).
- Generatriz g = h (en cilindro recto).

**Fórmulas:**
- Área de una base: A_b = π r²
- **Área lateral:** A_L = 2 π r h  (o 2 π r g)
- **Área total:** A_T = 2 π r h + 2 π r² = 2 π r (h + r)
- **Volumen:** V = π r² h

**Ejemplo resuelto:**  
Un cilindro tiene radio 5 cm y altura 12 cm.  
- A_b = π (5)² = 25π cm²  
- A_L = 2 π (5)(12) = 120π cm²  
- A_T = 120π + 50π = 170π cm²  
- V = 25π × 12 = 300π cm³ ≈ 942.48 cm³

---

## 6. Conos

**Elementos:**
- Una base circular (radio r).
- Vértice.
- Altura h (perpendicular desde vértice a la base).
- Generatriz g = √(r² + h²)

**Fórmulas:**
- Área de la base: A_b = π r²
- **Área lateral:** A_L = π r g
- **Área total:** A_T = π r g + π r² = π r (g + r)
- **Volumen:** V = (1/3) π r² h

**Ejemplo resuelto:**  
Cono con radio 6 cm y altura 8 cm.  
- g = √(6² + 8²) = √(36 + 64) = √100 = 10 cm  
- A_L = π × 6 × 10 = 60π cm²  
- A_T = 60π + 36π = 96π cm²  
- V = (1/3) π (36) (8) = 96π cm³ ≈ 301.59 cm³

### Construcción de un cono a partir de un sector circular
Para armar un cono se corta un sector de círculo de radio igual a la generatriz g y se une.

**Fórmula del ángulo central del sector (θ en grados):**  
θ = (360° × r) / g  
o equivalentemente:  
θ = 360° × (perímetro de la base / circunferencia del sector) = 360° × (2πr / 2πg) = 360° × (r / g)

**Ejemplo:**  
Cono con r = 6 cm, g = 10 cm → θ = 360 × (6/10) = 216°  
Se recorta un sector de 216° de un círculo de radio 10 cm y se une para formar el cono.

---

## 7. Prismas

**Elementos:**
- Dos bases polígonales paralelas e iguales.
- Caras laterales rectangulares (en prisma recto).
- Altura h (distancia entre bases).

**Fórmulas (base de área A_b y perímetro P_b):**
- **Área lateral:** A_L = P_b × h
- **Área total:** A_T = 2 A_b + P_b × h
- **Volumen:** V = A_b × h

**Ejemplo: Prisma rectangular (caja):**  
Base 4 cm × 3 cm, altura 5 cm.  
A_b = 12 cm²  
A_L = (2×4 + 2×3) × 5 = 14 × 5 = 70 cm²  
A_T = 2×12 + 70 = 94 cm²  
V = 12 × 5 = 60 cm³

**Ejemplo: Prisma pentagonal regular**  
Supongamos base pentagonal regular con lado l = 4 cm, apotema a = 2.75 cm, altura h = 9 cm.  
A_b = (5 × l × a)/2 = (5 × 4 × 2.75)/2 = 27.5 cm²  
A_L = 5 × 4 × 9 = 180 cm²  
A_T = 2×27.5 + 180 = 235 cm²  
V = 27.5 × 9 = 247.5 cm³

---

## 8. Pirámides

**Elementos:**
- Una base poligonal.
- Vértice (no necesariamente centrado).
- Altura h (perpendicular desde vértice a la base).
- Apotema de la pirámide (distancia desde vértice a punto medio de un lado de la base, en pirámide regular).

**Fórmulas:**
- **Área lateral:** suma de áreas de triángulos laterales (cada uno (1/2) × lado base × apotema lateral).
- **Área total:** A_T = A_b + A_L
- **Volumen:** V = (1/3) A_b × h

**Ejemplo: Pirámide pentagonal regular**  
Base pentagonal A_b = 24.8 cm², altura h = 9.5 cm.  
V = (1/3) × 24.8 × 9.5 ≈ 78.53 cm³

**Ejemplo general de pirámide cuadrangular:**  
Base cuadrada lado 6 cm (A_b = 36 cm²), altura 10 cm → V = (1/3)×36×10 = 120 cm³

---

## 9. Área superficial de un cubo o prisma rectangular

**Cubo** (arista a):  
- Área de una cara: a²  
- Área total: 6a²  
- Volumen: a³

**Prisma rectangular** (largo l, ancho w, altura h):  
- A_T = 2(lw + lh + wh)  
- V = l × w × h

---

## 10. Resumen de fórmulas clave

| Sólido          | Área Lateral                  | Área Total                          | Volumen                     |
|-----------------|-------------------------------|-------------------------------------|-----------------------------|
| **Cilindro**    | 2πrh                         | 2πr(h + r)                         | πr²h                       |
| **Cono**        | πrg                          | πr(g + r)                          | (1/3)πr²h                  |
| **Prisma**      | P_b × h                      | 2A_b + P_b × h                     | A_b × h                    |
| **Pirámide**    | (1/2) P_b × apotema lateral  | A_b + A_L                          | (1/3) A_b × h              |
| **Cubo**        | —                            | 6a²                                | a³                         |

**Nota sobre áreas de triángulos y rectángulos (usadas en caras laterales):**  
- Triángulo: (1/2) base × altura  
- Rectángulo: base × altura

---

## 11. Ejercicios de aplicación (estilo ICFES)

1. Dos conos son semejantes con razón de semejanza 3. Si el volumen del cono pequeño es 54π cm³, ¿cuál es el volumen del grande?  
   **Respuesta:** 54π × 27 = 1458π cm³

2. Un cilindro y un cono tienen la misma base (r=7 cm) y misma altura (h=10 cm). ¿Cuántas veces cabe el volumen del cono en el cilindro?  
   **Respuesta:** Exactamente 3 veces.

3. Se construye un cono a partir de un sector circular de radio 15 cm y ángulo central 240°. Hallar el radio de la base del cono.  
   **Respuesta:** Longitud arco = (240/360)×2π×15 = 20π cm → 2πr = 20π → r = 10 cm

4. Un prisma pentagonal regular tiene área de base 50 cm² y altura 8 cm. Calcular su volumen.  
   **Respuesta:** 400 cm³

5. Dos cubos son semejantes con razón k=2. Si el área total del pequeño es 24 cm², ¿cuál es el volumen del grande?  
   **Respuesta:** Área grande = 24×4 = 96 cm² → arista grande = √(96/6) = 4 cm → volumen = 64 cm³

---

## 12. Consejos para el ICFES
- Identifica siempre si el problema habla de **congruencia** (mismas medidas) o **semejanza** (proporciones).
- Usa el **Teorema de Pitágoras** para hallar generatrices.
- Recuerda las relaciones k, k², k³ para semejanza.
- En problemas de construcción de conos, relaciona el arco del sector con la circunferencia de la base.
- Dibuja el desarrollo plano cuando sea necesario.