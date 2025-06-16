---
tags:
  - proyecto
---
# 🔥 El dilema eterno de la carnita asada 🔥

Cada que armamos la carnita, siempre surge la misma bronca:  
**¿Qué hay que comprar? ¿Cuánto cuesta? ¿Y cuánto le toca a cada quien?**

Para evitar discusiones y hacer todo más fácil, tu misión es crear un programa que nos ayude a organizar la compra:

- Le dices qué cosas se necesitan y cuánto cuesta cada una.  
- El programa calcula automáticamente cuánto hay que comprar y cuánto debe cooperar cada persona.

> Porque entre menos tiempo hagamos cuentas, ¡más rápido cae la cheve! 🍻

## 🧪 Ejemplo

Supongamos que se necesitan:

- 2 kg de carne a $180 por kg  
- 1 bolsa de carbón a $70  
- 2 paquetes de tortillas a $25 cada uno  
- 1 six de cerveza a $120  

Y van a cooperar **4 personas**.

El programa debe calcular:

- **Total a pagar:** $180×2 + $70 + $25×2 + $120 = **$600**  
- **Cooperación por persona:** $600 ÷ 4 = **$150**
## 🧠 Cosas que debes considerar

- 👥 **Número de personas** que van a cooperar.
- 🛒 **Lista de productos** con:
  - Nombre
  - Cantidad
  - Precio unitario
- 📦 **Unidades distintas**, como:
  - Por kilo (ej. carne, cebolla)
  - Por pieza (ej. bolsas de carbón, paquetes de tortillas)
  - Por six (ej. cervezas)
- 💵 **Total general** y **cuánto le toca a cada quien**.
- 🧾 Opción para ver un **resumen detallado** de lo que se va a comprar y por qué precio.
- 🪙 (Opcional Bonus) Si alguien quiere poner más o menos dinero, que el programa lo reparta de forma justa.

Así tu programa no solo saca cuentas, ¡también evita peleas! 🙌

---

## ¿Qué necesitas saber para crearlo? (con JavaScript)

Para armar este programa en JavaScript, te conviene dominar lo siguiente:

- [[Math operations]]: usar operadores como `+`, `*`, `/` para hacer cálculos
- [[Data structures]]: manejar [[arrays]] (`[]`) y [[objetos]] (`{}`) para organizar los productos
- [[Loops]]: usar `for`, `forEach` o `while` para recorrer listas de compras
- [[Input/Output]]:
  - En consola: `prompt()`, `console.log()`
  - En navegador: formularios HTML + eventos (`addEventListener`)
- [[Funciones]]: dividir tu programa en funciones reutilizables
- (Opcional) [[DOM manipulation]]: si haces una interfaz visual con HTML/CSS
- (Opcional) [[Data validation]]: asegurar que los datos sean correctos antes de procesarlos


