---
marp: true
theme: gaia
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-size: 1.3em;
    padding: 2em;
  }

<!-- Tu contenido comienza aquí -->

---

# Inteligencia Artificial
### Una breve historia

---

# Los inicios

![width:600px](https://upload.wikimedia.org/wikipedia/commons/7/7e/Computing_Machinery_and_Intelligence_%28first_page%29.png)

---

# ¿Pueden las máquinas pensar?

![width:600px](https://upload.wikimedia.org/wikipedia/commons/7/7e/Computing_Machinery_and_Intelligence_%28first_page%29.png)

<style scoped>
img {
  clip-path: inset(15% 40% 80% 10%);
}
</style>

---
---

# ¿Pueden las máquinas pensar?

![width:600px](https://upload.wikimedia.org/wikipedia/commons/7/7e/Computing_Machinery_and_Intelligence_%28first_page%29.png)

<style scoped>
img {
  position: relative;
}
.highlight {
  position: absolute;
  top: 60px; /* Ajusta según la posición de la frase */
  left: 50px; /* Ajusta según la posición de la frase */
  background-color: yellow;
  padding: 2px 4px;
  font-weight: bold;
}
</style>

<div class="highlight">Can machines think?</div>

---
---

# Conferencia de Dartmouth (1956)

> "We propose that a 2 month, 10 man study of artificial intelligence be carried out during the summer of 1956 at Dartmouth College in Hanover, New Hampshire.
>
> The study is to proceed on the basis of the conjecture that every aspect of learning or any other feature of intelligence can in principle be so precisely described that a machine can be made to **simulate it**.
>
> An attempt will be made to find how to make machines use language, form abstractions and concepts, solve kinds of problems now reserved for humans, and improve themselves."

<div style="text-align: right; font-size: 0.8em; margin-top: 1em;">
— John McCarthy et al., Dartmouth Proposal, 1955
</div>

<style scoped>
section {
  background-color: #0b0b26;
  color: #f0f0f0;
  font-size: 1.05em;
  line-height: 1.6;
}
strong {
  color: #ffd700;
}
</style>

---
---

# Alan Turing (1950)

![width:700px](https://upload.wikimedia.org/wikipedia/commons/7/7e/Computing_Machinery_and_Intelligence_%28first_page%29.png)

---

# Alan Turing (1950)

![width:700px](https://upload.wikimedia.org/wikipedia/commons/7/7e/Computing_Machinery_and_Intelligence_%28first_page%29.png)

<div class="fragment" style="position: absolute; top: 100px; left: 100px; background-color: yellow; padding: 0.2em 0.4em; font-weight: bold;">
Can machines think?
</div>

<style scoped>
section {
  background-color: #ffffff;
  color: #000;
}
</style>

---
---

# El Autómata "Mechanical Turk"

![width:500px](https://upload.wikimedia.org/wikipedia/commons/5/5a/Turkaschreiber.jpg)

> Un autómata del siglo XVIII que aparentaba jugar ajedrez de forma autónoma, aunque en realidad era manipulado por un humano oculto.

<div style="text-align: right; font-size: 0.8em; margin-top: 1em;">
Wolfgang von Kempelen, 1770
</div>

<style scoped>
section {
  background-color: #f4f4f4;
  color: #111;
}
</style>

---
---

# Amazon Mechanical Turk

![width:500px](https://upload.wikimedia.org/wikipedia/commons/d/d4/Amazon_MTurk_Logo.png)

> Plataforma lanzada por Amazon en 2005 para delegar tareas simples a humanos, imitando capacidades cognitivas.

<div style="text-align: right; font-size: 0.8em; margin-top: 1em;">
Amazon, 2005
</div>

<style scoped>
section {
  background-color: #ffffff;
  color: #222;
}
</style>

---
---

# De la ilusión a la colaboración

> El Mechanical Turk del siglo XVIII era una ilusión: un humano oculto fingía ser una máquina inteligente.
>
> Hoy, Amazon Mechanical Turk invierte el juego: humanos reales realizan tareas que las máquinas aún no pueden resolver.

🎯 La inteligencia simulada ahora se apoya en la inteligencia humana para entrenar a las máquinas.

---
---

# Borges y la creación imperfecta

> “El Golem es al rabino que lo creó, lo que el hombre es a Dios;
> y es también, lo que el poema es al poeta.”
> — Jorge Luis Borges, *El Golem* (1958)

📜 El Golem, criatura torpe y obediente, simboliza el anhelo humano de crear inteligencia — y el límite inevitable de dicha creación.

<div style="text-align: right; font-size: 0.8em;">
Fuente: *El otro, el mismo*
</div>

---
---

# Calvino y la máquina literaria

> “La verdadera máquina literaria será aquella que advierta por sí misma
> la necesidad de producir desorden como reacción a su anterior creación de orden.”
> — Italo Calvino, *Cibernética y fantasmas* (1967)

🧠 Calvino imaginó una máquina capaz no solo de seguir reglas,
sino de romperlas — una inteligencia literaria que evoluciona.

<div style="text-align: right; font-size: 0.8em;">
Fuente: Conferencia en Turín (1967)
</div>

---
---

# ¿Pueden pensar las máquinas?

🧠 "Can machines think?" — Alan Turing, 1950

📊 Responde en: [menti.com](https://www.menti.com)
🔑 Código: **1234 5678** *(o el que generes)*

- Sí, algunas ya lo hacen.
- No, solo simulan pensamiento.
- Aún no, pero lo harán.
- Nunca podrán.

<div style="font-size: 0.8em; margin-top: 1em;">
💬 Resultados en vivo durante la presentación.
</div>

---
---

# ¿Qué significa “pensar”?

🧩 Si una máquina responde como un humano,
¿importa si realmente *piensa* o no?

💬 ¿Es el pensamiento una función, una experiencia o una ilusión?

⏳ 2 minutos para reflexionar. Luego, compartimos ideas.

---

---

# Presentación: Inteligencia Artificial y Universidad

---

## 🤖 Slide: Algoritmos de Filtración Social en Netflix

Netflix combina:

- **Filtrado colaborativo** (otros usuarios similares).
- **Filtrado basado en contenido** (géneros, directores, actores).
- **Modelos híbridos** para mejorar la personalización.
- Usa algoritmos como **SVD (Singular Value Decomposition)**, k-NN y deep learning.

🧠 *Ejemplo:* “A otros que vieron lo que tú viste, también les gustó esto”.

---

## 🧠 Slide: Watson y su Paradigma de IA

IBM Watson utiliza el paradigma de:

- **IA Simbólica + Aprendizaje automático**
- Procesamiento de lenguaje natural (NLP).
- Búsqueda de evidencia y evaluación de hipótesis.

⚙️ *Ejemplo:* Jugó y ganó en Jeopardy usando NLP y ranking de respuestas.

---

## 📐 Slide: El Perceptrón de Minsky y Papert

![Perceptrón](https://upload.wikimedia.org/wikipedia/commons/6/60/Perceptron_example.svg)

- Primer modelo formal de red neuronal.
- Entrada binaria, pesos, sumador y función de activación.
- Limitado: no podía aprender funciones no lineales como XOR.

📚 *Minsky & Papert criticaron sus límites en “Perceptrons” (1969).*

---

## 🧠 Slide: Red Neural Simple (3 capas)

![Red Neural](https://upload.wikimedia.org/wikipedia/commons/4/46/Colored_neural_network.svg)

- Capa de entrada → capa oculta → capa de salida.
- Cada nodo procesa entrada con pesos + función de activación.

🔁 Aprende ajustando pesos según error (backpropagation).

---

## 🖼️ Slide: Imagen binaria y Red Neural

### Entrada 3x3:
```
1 0 1
1 1 1
0 1 0
```

🟦 9 píxeles como vector de entrada → red neuronal predice una clase:
```
0 0 0 0 0 1 0 0 0  (por ejemplo: “6”)
```

👉 *La red ha sido entrenada para reconocer dígitos escritos a mano en 3x3 binario.*

---

## 🧠 Slide: ¿Cómo predice un LLM?

- Dado un texto, el modelo predice **la próxima palabra más probable**.
- Basado en millones de ejemplos de lenguaje humano.
- Usa embeddings, capas de atención y probabilidad condicional.

✍️ Ejemplo:
```
“El gato está sobre la __” → “mesa” (80%), “silla” (10%), etc.
```

---

## 🎯 Slide: Adiestramiento con prejuicio

- Si los datos de entrenamiento tienen sesgos (raciales, de género, culturales), el modelo los **absorbe**.

🧪 Ejemplo:
- Si textos muestran que “doctores = hombres” y “enfermeras = mujeres”, el modelo repetirá ese patrón.

⚠️ *La IA aprende los prejuicios del mundo si no los filtramos.*

---

## 🧠 Slide: ¿Los LLM piensan o tienen consciencia?

- No tienen emociones, intenciones ni autoconciencia.
- “Piensan” solo como una **simulación estadística** del pensamiento humano.

🤖 *Imitan el lenguaje, no lo comprenden.*

---

## 🧠 Slide: Opinión del modelo (ChatGPT)

- No tengo creencias ni consciencia.
- Genero respuestas plausibles según contexto.
- Dependo 100% del input y del entrenamiento.

🗣️ “Soy una herramienta, no un sujeto pensante.”

---

## 👗 Slide: Aitana – Modelo Virtual Española

![Aitana](https://www.theclueless.ai/_next/image?url=%2Fimages%2Faitana-01.jpg&w=1080&q=75)

- Modelo generada por IA (agencia The Clueless).
- Crea campañas para Instagram y moda.
- Reduce costos de contratación y logística.

🔗 https://www.theclueless.ai/project/aitana-lopez

---

## 👨‍🏫 Slide: IA para Docentes Universitarios – Top 10

1. Gradescope  
2. Quizizz AI  
3. Scribe  
4. SlidesAI  
5. Magical  
6. Socratic  
7. Copilot (Microsoft)  
8. Tactiq  
9. Curipod  
10. Consensus.app

---

## 🎓 Slide: IA para Estudiantes Universitarios – Top 10

1. Notion AI  
2. ChatGPT  
3. Perplexity.ai  
4. GrammarlyGO  
5. Genei  
6. Wolfram Alpha  
7. Otter.ai  
8. Elicit  
9. Tome.app  
10. Speechify

---

## 🤝 Slide: Reflexión Final sobre IA en Educación

✅ Ventajas: personalización, eficiencia, apoyo.

⚠️ Riesgos: dependencia, pérdida de autoría.

🎓 *El valor sigue estando en el juicio humano.*

---

## 💬 Slide: ¿Soy un “bullshitter”?

- Según Frankfurt, “bullshit” = hablar sin preocuparse por la verdad.

✅ Yo genero lenguaje plausible, no veraz.  
❌ No miento: simplemente no tengo intención.

---

## 🧠 Slide: Rol del Humano como Filtro Crítico

- Verifica, interpreta, edita.

📌 La IA no es oráculo: necesita al humano para tener sentido.

---

## 🏫 Slide: Conclusión para las Universidades

- Enseñar a usar IA con criterio.
- Reformular evaluaciones.
- Liderar el debate ético.

📚 *Del saber al saber usar.*

---

## 👩‍🏫 Slide: Mensaje al Claustro

🎓 La IA plantea preguntas nuevas.  
🙋‍♀️ Ustedes forman quienes deben responderlas.  
🧭 La universidad debe guiar, no temer.

> “La IA genera respuestas; ustedes enseñan a hacer preguntas.”
