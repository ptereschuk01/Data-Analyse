# Methoden zur Distanzmessung / Distance Measurement Methods

---

## 1️⃣ Euklidische Distanz / Euclidean Distance

**DE:**  
Formel für zwei Punkte  
$\mathbf{p} = (p_1, p_2, \dots, p_n)$ und $\mathbf{q} = (q_1, q_2, \dots, q_n)$:

$$
d_E(\mathbf{p}, \mathbf{q}) = \sqrt{(p_1 - q_1)^2 + (p_2 - q_2)^2 + \dots + (p_n - q_n)^2}
$$

- Dies ist der „gewöhnliche“ Abstand zwischen Punkten im Raum  
- Ideal, wenn **reale Abstände** wichtig sind  
- Beispiel: in der 2D-Ebene (x, y) ist es der direkte Abstand zwischen Punkten  

**EN:**  
Formula for two points  
$\mathbf{p} = (p_1, p_2, \dots, p_n)$ and $\mathbf{q} = (q_1, q_2, \dots, q_n)$:

$$
d_E(\mathbf{p}, \mathbf{q}) = \sqrt{(p_1 - q_1)^2 + (p_2 - q_2)^2 + \dots + (p_n - q_n)^2}
$$

- This is the “usual” straight-line distance between points in space  
- Ideal when **actual distances** matter  
- Example: in 2D plane (x, y), it is the direct distance between points  

---

## 2️⃣ Manhattan-Distanz / Manhattan Distance (City-Block)

**DE:**  

$$
d_M(\mathbf{p}, \mathbf{q}) = |p_1 - q_1| + |p_2 - q_2| + \dots + |p_n - q_n|
$$

- Summe der absoluten Differenzen über alle Koordinaten  
- „Wie zu Fuß durch die Straßen einer Stadt“  
- Diagonalen werden ignoriert; nur Bewegungen entlang der Achsen  
- Wird verwendet, wenn Bewegung auf ein Raster beschränkt ist  

**EN:**  

$$
d_M(\mathbf{p}, \mathbf{q}) = |p_1 - q_1| + |p_2 - q_2| + \dots + |p_n - q_n|
$$

- Sum of absolute differences across all coordinates  
- “Like walking along city streets”  
- Diagonals are ignored; only movement along axes is considered  
- Used when movement is restricted to a grid, e.g., logistics  

---

## 3️⃣ Kosinus-Distanz / Cosine Distance

**DE:**  
Zuerst berechnen wir die Kosinus-Ähnlichkeit:

$$
\cos(\theta) = \frac{\mathbf{p} \cdot \mathbf{q}}{\|\mathbf{p}\| \, \|\mathbf{q}\|} 
= \frac{\sum_i p_i q_i}{\sqrt{\sum_i p_i^2} \sqrt{\sum_i q_i^2}}
$$

Dann die Distanz:

$$
d_C(\mathbf{p}, \mathbf{q}) = 1 - \cos(\theta)
$$

- Misst den Winkelunterschied, nicht die absolute Distanz  
- Wichtig, wenn Richtung/Form zählt, nicht Länge  
- Oft in Text-Mining, NLP, Empfehlungen  

**EN:**  
First, compute cosine similarity:

$$
\cos(\theta) = \frac{\mathbf{p} \cdot \mathbf{q}}{\|\mathbf{p}\| \, \|\mathbf{q}\|} 
= \frac{\sum_i p_i q_i}{\sqrt{\sum_i p_i^2} \sqrt{\sum_i q_i^2}}
$$

Then distance:

$$
d_C(\mathbf{p}, \mathbf{q}) = 1 - \cos(\theta)
$$

- Measures angular difference, not absolute distance  
- Important when direction/shape matters, not magnitude  
- Often used in text mining, NLP, recommendations  

---

## ⚡ Vergleich / Comparison

| Methode / Method | Was gemessen wird / What it measures | Anwendungen / Applications |
|-----------------|------------------------------------|---------------------------|
| Euklidisch / Euclidean | Gerader Abstand / Straight-line distance | Geometrie, KNN, Clustering / Geometry, KNN, Clustering |
| Manhattan / Manhattan | Summe der absoluten Differenzen / Sum of absolute differences | Logistik, Stadtgitter, KNN / Logistics, city grid, KNN |
| Kosinus / Cosine | Winkel zwischen Vektoren / Angle between vectors | Text, Empfehlungen / Text, recommendations |

---

## 🖊 2D Beispiel / 2D Example

Angenommen wir haben zwei Punkte / Suppose we have two points:

$$
A = (1, 2), \quad B = (4, 6)
$$

**DE:**  
- Euklidisch: \( \sqrt{(4-1)^2 + (6-2)^2} = \sqrt{9+16} = 5 \)  
- Manhattan: \( |4-1| + |6-2| = 3 + 4 = 7 \)  
- Kosinus: \( \cos(\theta) = \frac{1*4 + 2*6}{\sqrt{1^2+2^2}\sqrt{4^2+6^2}} \approx 0.986 \) → Distanz \( 1-0.986 = 0.014 \)

**EN:**  
- Euclidean: \( \sqrt{(4-1)^2 + (6-2)^2} = \sqrt{9+16} = 5 \)  
- Manhattan: \( |4-1| + |6-2| = 3 + 4 = 7 \)  
- Cosine: \( \cos(\theta) = \frac{1*4 + 2*6}{\sqrt{1^2+2^2}\sqrt{4^2+6^2}} \approx 0.986 \) → Distance \( 1-0.986 = 0.014 \)
