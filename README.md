# 🛳️ Titanic - Machine Learning from Disaster

## 🚢 El Reto
El hundimiento del Titanic es uno de los naufragios más famosos de la historia.  

- **Fecha:** 15 de abril de 1912  
- **Evento:** El RMS Titanic se hundió en su viaje inaugural tras chocar con un iceberg.  
- **Impacto:** 1502 de las 2224 personas a bordo fallecieron.  

Lamentablemente, no había suficientes botes salvavidas para todos.  
Aunque hubo un factor de suerte en la supervivencia, ciertos grupos de personas tenían **más probabilidades de sobrevivir que otros**.  

**Tu tarea es:**  
Construir un modelo predictivo que responda:  
👉 *“¿Qué tipo de personas tenían más probabilidades de sobrevivir?”*  

Usando datos de pasajeros como:  
- Nombre  
- Edad  
- Género  
- Clase socioeconómica  
- Familiares a bordo  

---

## ⚖️ Evaluación

### 🎯 Objetivo
Tu trabajo es predecir si un pasajero sobrevivió al hundimiento del Titanic o no.  
Para cada pasajero en el **conjunto de prueba**, debes predecir un valor **0** (no sobrevivió) o **1** (sobrevivió).  

---

### 📊 Métrica
- La métrica utilizada es la **exactitud (accuracy)**.  
- Es decir, el porcentaje de pasajeros que predices correctamente.  

---

### 📂 Formato del archivo de envío
Debes enviar un archivo `.csv` con exactamente **418 filas** más una fila de encabezado.  

⚠️ Importante:  
- El archivo no debe contener más columnas que `PassengerId` y `Survived`.  
- Debe tener exactamente **2 columnas**:  
  - `PassengerId`  
  - `Survived` (predicción binaria: 0 = no sobrevivió, 1 = sobrevivió)  

✅ Ejemplo:
```csv
PassengerId,Survived
892,0
893,1
894,0
