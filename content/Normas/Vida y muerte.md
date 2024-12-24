#Jugadores
## **Sistema de Puntos de Golpe (PG), Puntos de Salud (PS) y Fatiga**

### **Definiciones**

1. **Puntos de Golpe (PG):**
    
    - Representan la capacidad del personaje para esquivar, resistir o minimizar daño sin recibir heridas graves.
    - Los **PG nunca pueden superar los PS actuales**.
    - Los PG se regeneran fácilmente y son la primera línea de defensa.
    - Si el personaje supera la tirada de colapso, queda inconsciente hasta tener PS positivos.
    - Si el personaje no la supera... RIP
1. **Puntos de Salud (PS):**
    
    - Reflejan la fortaleza física y el estado de salud real del personaje.
    - Perder PS indica heridas graves, agotamiento físico o debilitamiento extremo.
    - Recuperar PS es más difícil y requiere descanso prolongado o magia avanzada.
3. **Fatiga:**
    
    - Mide el desgaste físico y mental acumulado del personaje.
    - Cada nivel de fatiga aplica un penalizador de **-1 a todas las tiradas de d20**.
    - Si un personaje acumula **10 niveles de fatiga**, entra en **colapso**.

---

### **Mecánicas de Daño y Recuperación**

1. **Daño Recibido:**
    
    - El daño primero reduce los **PG**.
    - Si los PG llegan a 0, cualquier daño restante afecta directamente a los **PS**.
    - Si los PS llegan a 0, el personaje entra en **colapso** y aumenta en 1 punto su **fatiga**.
1. **Recuperar PG:**
    
    - En su turno, un personaje puede usar una **Acción Adicional** para regenerar PG.
        - **Regeneración:** Recupera PG igual a la mitad de sus PS actuales (redondeado hacia abajo).
        - **Costo:** Gana **1 nivel de fatiga**.
    - Ejemplo: Un personaje con 12 PS recupera 6 PG al usar esta acción.
3. **Recuperar PS:**
    
    - **Descanso Largo:** Recupera PS igual al modificador de Constitución (mínimo 1).
    - **Medios Mágicos Especiales:** Solo magia avanzada o recursos únicos pueden recuperar PS directamente (no los hechizos de curación convencionales).
    - Ejemplo: **Restauración Mayor** o un ritual de sanación.
4. **Recuperar Fatiga:**
    
    - Los personajes solo pueden reducir **1 nivel de fatiga** tras un Descanso Largo.

---

### **Estados Críticos**

1. **Colapso (PS = 0 o menos):**
    
    - Cuando un personaje llega a 0 PS, entra en **estado de colapso**.
    - En su turno, debe realizar una tirada especial con **6d20**:
        - Si logra **3 o más resultados de 11+**, estabiliza su condición:
            - Queda con 0 PS, inconsciente y ya no está en colapso.
        - Si no logra **3 éxitos**, el personaje muere.
    - Si un personaje en colapso recibe daño adicional, vuelve a entrar en colapso y repite la tirada en su siguiente turno.
2. **Fatiga Extrema (10 niveles):**
    
    - Si un personaje acumula 10 niveles de fatiga:
        - Cae inconsciente automáticamente.
        - No puede despertar hasta reducir su fatiga por debajo de 10 niveles.

---

### **Regeneración de Recursos**

1. **Puntos de Golpe (PG):**
    
    - Se recuperan completamente con un **Descanso Corto**.
    - También pueden recuperarse con curaciones convencionales.
2. **Puntos de Salud (PS):**
    
    - Solo se recuperan durante un **Descanso Largo** o con magia avanzada.
    - Los PS representan un recurso limitado y difícil de regenerar.
3. **Fatiga:**
    
    - Solo se reduce **1 nivel por Descanso Largo**.
    - Representa un desgaste acumulativo que debe gestionarse cuidadosamente.

---

### **Ejemplo de Combate con el Sistema**

1. **Inicio del Combate:**
    - Un personaje tiene 10 PG, 12 PS y 0 fatiga.
2. **Primer Ataque:**
    - Recibe 15 puntos de daño.
    - Los PG se reducen a 0, y los 5 puntos restantes afectan a los PS (quedando con 7 PS).
3. **Acción de Recuperación:**
    - En su turno, el personaje usa una **Acción Adicional** para regenerar PG.
        - Recupera 7/2 = 3 PG (redondeado hacia abajo).
        - Gana **1 nivel de fatiga**.
4. **Segundo Ataque:**
    - Recibe 12 puntos de daño.
    - Los 3 PG se reducen a 0, y los 9 puntos restantes afectan a los PS (quedando con -2 PS).
    - El personaje entra en **colapso** y aumenta en 1 punto su **fatiga**.
5. **Tirada de Colapso:**
    - En su siguiente turno, tira **6d20**.
        - Obtiene los resultados: 15, 14, 9, 11, 8, 16 (4 resultados de 11+).
        - El personaje estabiliza su condición, queda inconsciente y con 0 PS.
6. **Intervención de Aliados:**
    - Un aliado usa un hechizo avanzado para recuperar 5 PS, permitiendo que el personaje vuelva a actuar tras despertar.

---

