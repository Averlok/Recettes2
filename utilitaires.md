---
layout: default
title: <i class="fa-solid fa-calculator"></i> Outils & Conversions
nav_order: 15
---

# <i class="fa-solid fa-calculator"></i> Outils & Conversions
{:.titre-accueil}

Un petit coin pratique pour ajuster tes mesures sans te casser la tête la farine jusqu'aux coudes!

---

## 🔄 Convertisseur interactif

<div style="background: rgba(66, 41, 86, 0.05); padding: 18px; border-radius: 10px; border: 1px solid #422956; margin-bottom: 25px;">
  <h3 style="margin-top: 0; color: #422956;">Volume (Tasses ➔ ml)</h3>
  <div style="display: flex; gap: 10px; align-items: center; margin-bottom: 15px;">
    <input type="number" id="tassesInput" placeholder="Nombre de tasses" step="0.25" style="padding: 8px; border-radius: 5px; border: 1px solid #ccc; width: 60%;">
    <span style="font-weight: bold; color: #422956;">= <span id="mlResult">0</span> ml</span>
  </div>

  <h3 style="color: #422956;">Température (°F ➔ °C)</h3>
  <div style="display: flex; gap: 10px; align-items: center;">
    <input type="number" id="fahrInput" placeholder="Degrés Fahrenheit" step="5" style="padding: 8px; border-radius: 5px; border: 1px solid #ccc; width: 60%;">
    <span style="font-weight: bold; color: #422956;">= <span id="celsiusResult">0</span> °C</span>
  </div>
</div>

<script>
  // Calculateur Tasses -> ML
  document.getElementById('tassesInput').addEventListener('input', function(e) {
    let val = parseFloat(e.target.value);
    document.getElementById('mlResult').innerText = isNaN(val) ? 0 : Math.round(val * 250);
  });

  // Calculateur °F -> °C
  document.getElementById('fahrInput').addEventListener('input', function(e) {
    let val = parseFloat(e.target.value);
    document.getElementById('celsiusResult').innerText = isNaN(val) ? 0 : Math.round((val - 32) * 5 / 9);
  });
</script>

---

## 📊 Équivalences de poids courantes

| Ingrédient | 1/4 tasse | 1/2 tasse | 1 tasse |
| :--- | :--- | :--- | :--- |
| **Farine tout-usage** | 30 g | 60 g | 120 g |
| **Sucre blanc** | 50 g | 100 g | 200 g |
| **Cassonade (tassée)** | 55 g | 110 g | 220 g |
| **Beurre** | 55 g | 115 g | 230 g |
| **Pépites de chocolat** | 45 g | 90 g | 180 g |

---

## 🌡️ Températures du four

* **275 °F (140 °C)** : Rechauffer / Cuisson très lente
* **350 °F (180 °C)** : La température standard (Gâteaux, biscuits, gratins)
* **400 °F (200 °C)** : Rôtissage des légumes et viandes
* **450 °F (230 °C)** : Pizzas et pains maison

---

## 🆘 Substituts de dépannage

* **1 tasse de babeurre** $\rightarrow$ 1 tasse de lait + 1 c. à soupe de jus de citron (attendre 5 min).
* **1 c. à thé de poudre à pâte** $\rightarrow$ 1/4 c. à thé de bicarbonate de soude + 1/2 c. à thé de crème de tartre.
* **1 c. à soupe de fécule de maïs (épaississant)** $\rightarrow$ 2 c. à soupe de farine tout-usage.
