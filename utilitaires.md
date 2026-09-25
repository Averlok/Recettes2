---
layout: default
title: <i class="fa-solid fa-calculator"></i> Outils & Conversions
nav_order: 15
---

<div class="categorie-header" markdown="1">
**<i class="fa-solid fa-calculator"></i> Outils & Conversions**
</div>


<div class="sous-titre">
Un petit coin pratique pour ajuster tes mesures sans te casser la tête la farine jusqu'aux coudes!
</div>

---

## <i class="fa-solid fa-arrows-rotate"></i> Convertisseur interactif

<div style="background: rgba(66, 41, 86, 0.05); padding: 18px; border-radius: 10px; border: 1px solid #422956; margin-bottom: 25px;">
  
  <div style="font-weight: bold; color: #422956; margin-bottom: 5px;">Volume (Tasses <i class="fa-solid fa-right-long" style="font-size: 0.8em; margin: 0 5px;"></i> ml)</div>
  <div style="display: flex; gap: 10px; align-items: center; margin-bottom: 15px;">
    <input type="number" id="tassesInput" oninput="calculerTasses()" placeholder="0" step="0.25" style="padding: 8px; border-radius: 5px; border: 1px solid #ccc; width: 50%; font-size: 16px;">
    <span style="font-weight: bold; color: #422956;">= <span id="mlResult">0</span> ml</span>
  </div>

  <div style="font-weight: bold; color: #422956; margin-bottom: 5px;">Cuillères à soupe (c. à soupe <i class="fa-solid fa-right-long" style="font-size: 0.8em; margin: 0 5px;"></i> ml)</div>
  <div style="display: flex; gap: 10px; align-items: center; margin-bottom: 15px;">
    <input type="number" id="casInput" oninput="calculerCas()" placeholder="0" step="1" style="padding: 8px; border-radius: 5px; border: 1px solid #ccc; width: 50%; font-size: 16px;">
    <span style="font-weight: bold; color: #422956;">= <span id="casMlResult">0</span> ml</span>
  </div>

  <div style="font-weight: bold; color: #422956; margin-bottom: 5px;">Température (°F <i class="fa-solid fa-right-long" style="font-size: 0.8em; margin: 0 5px;"></i> °C)</div>
  <div style="display: flex; gap: 10px; align-items: center;">
    <input type="number" id="fahrInput" oninput="calculerTemp()" placeholder="0" step="5" style="padding: 8px; border-radius: 5px; border: 1px solid #ccc; width: 50%; font-size: 16px;">
    <span style="font-weight: bold; color: #422956;">= <span id="celsiusResult">0</span> °C</span>
  </div>

</div>

<script>
  function calculerTasses() {
    let val = parseFloat(document.getElementById('tassesInput').value);
    document.getElementById('mlResult').innerText = isNaN(val) ? 0 : Math.round(val * 250);
  }

  function calculerCas() {
    let val = parseFloat(document.getElementById('casInput').value);
    document.getElementById('casMlResult').innerText = isNaN(val) ? 0 : Math.round(val * 15);
  }

  function calculerTemp() {
    let val = parseFloat(document.getElementById('fahrInput').value);
    document.getElementById('celsiusResult').innerText = isNaN(val) ? 0 : Math.round((val - 32) * 5 / 9);
  }
</script>

---

## <i class="fa-solid fa-spoon"></i> Équivalences de cuillères et tasses

| Mesure | Équivalent en cuillères | Métrique (ml) |
| :--- | :--- | :--- |
| **1 c. à thé (tsp)** | 1/3 c. à soupe | 5 ml |
| **1 c. à soupe (tbsp)** | 3 c. à thé | 15 ml |
| **1/4 tasse** | 4 c. à soupe | 60 ml |
| **1/3 tasse** | 5 c. à soupe + 1 c. à thé | 80 ml |
| **1/2 tasse** | 8 c. à soupe | 125 ml |
| **1 tasse** | 16 c. à soupe | 250 ml |

---

## <i class="fa-solid fa-weight-hanging"></i> Équivalences de poids courantes

| Ingrédient | 1/4 tasse | 1/2 tasse | 1 tasse |
| :--- | :--- | :--- | :--- |
| **Farine tout-usage** | 30 g | 60 g | 120 g |
| **Sucre blanc** | 50 g | 100 g | 200 g |
| **Cassonade (tassée)** | 55 g | 110 g | 220 g |
| **Beurre** | 55 g | 115 g | 230 g |
| **Pépites de chocolat** | 45 g | 90 g | 180 g |
| **Cacao en poudre** | 25 g | 50 g | 100 g |

---

## <i class="fa-solid fa-temperature-high"></i> Températures du four

* **275 °F (140 °C)** : Réchauffer / Cuisson très lente
* **350 °F (180 °C)** : La température standard (Gâteaux, biscuits, gratins)
* **400 °F (200 °C)** : Rôtissage des légumes et viandes
* **450 °F (230 °C)** : Pizzas et pains maison

---

## <i class="fa-solid fa-kit-medical"></i> Substituts de dépannage

* **1 tasse de babeurre** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 1 tasse de lait + 1 c. à soupe de jus de citron (attendre 5 min).
* **1 c. à thé de poudre à pâte** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 1/4 c. à thé de bicarbonate de soude + 1/2 c. à thé de crème de tartre.
* **1 c. à soupe de fécule de maïs** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 2 c. à soupe de farine tout-usage.
* **1 oeuf (en pâtisserie)** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 1/2 banane écrasée OU 1 c. à soupe de graines de lin moulues + 3 c. à soupe d'eau.
* **1 gousse d'ail** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 1/8 c. à thé d'ail en poudre.
* **1 tasse de crème sûre** <i class="fa-solid fa-arrow-right" style="color: #422956; font-size: 0.9em; margin: 0 5px;"></i> 1 tasse de yogourt grec nature.
