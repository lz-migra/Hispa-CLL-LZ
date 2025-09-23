Aquí tienes la lista actualizada con los datos de las nuevas imágenes, respetando el formato original y dentro de un recuadro de texto plano:

# USD
```
📱 PLANES Y RECARGAS DISPONIBLES 📱

1. *Plan 80 MIN*
Reciben 📞 80 minutos nacionales x 35 días
*$ 5.99*

---

2. *Recarga 600 X5 + Internet*
Reciben 💵 3000 CUP 💵 Saldo + Internet Nocturno de 12 am a 7 am por 30 días
*$ 25.99*

---

3. *Recarga 500 CUP + Internet x 10 días*
Reciben 💵 500 CUP de 💵 Saldo + Internet ⚡ Ilimitado las 24 h x 10 días
*$ 22.99*

---

4. *Standard*
Reciben 🌐 9GB + 📞 75MIN + ✉️ 80SMS x 35 días
*$ 22.99*

---

5. *Recarga 250 CUP*
Tu contacto recibe 💵 250 CUP.
*$ 11.99*

---

6. *Recarga 250 CUP + 40 MIN*
Reciben 💵 250 CUP y 📞 40 minutos nacionales x 35 días
*$ 13.99*

---

7. *Plan 3 GB + 40 MIN*
Reciben 🌐 3 GB y 📞 40 minutos nacionales x 35 días
*$ 13.99*

---

8. *Recarga 360 CUP*
Tu contacto recibe 💵 360 CUP.
*$ 16.50*

---

9. *El Fuerte*
Reciben 🌐 14GB + 📞 115MIN + ✉️ 120SMS x 35 días
*$ 33.99*

---

10. *Cacique*
Reciben 🌐 20GB + 📞 165MIN + ✉️ 160SMS x 35 días
*$ 44.49*

---

11. *Lo Más Grande*
Reciben 🌐 29GB + 📞 240MIN + ✉️ 240SMS x 35 días
*$ 64.99*

```
# EUR

```
📱 PLANES Y RECARGAS DISPONIBLES 📱

1. *Plan 80 MIN*
Reciben 📞 80 minutos nacionales x 35 días
*5,69 €*

---

2. *Recarga 600 X5 + Internet*
Reciben 💵 3000 CUP 💵 Saldo + Internet Nocturno de 12 am a 7 am por 30 días
*22,99 €*

---

3. *Recarga 500 CUP + Internet x 10 días*
Reciben 💵 500 CUP de 💵 Saldo + Internet ⚡ Ilimitado las 24 h x 10 días
*21,84 €*

---

4. *Standard*
Reciben 🌐 9GB + 📞 75MIN + ✉️ 80SMS x 35 días
*21,84 €*

---

5. *Recarga 250 CUP*
Tu contacto recibe 💵 250 CUP.
*11,39 €*

---

6. *Recarga 250 CUP + 40 MIN*
Reciben 💵 250 CUP y 📞 40 minutos nacionales x 35 días
*13,29 €*

---

7. *Plan 3 GB + 40 MIN*
Reciben 🌐 3 GB y 📞 40 minutos nacionales x 35 días
*13,29 €*

---

8. *Recarga 360 CUP*
Tu contacto recibe 💵 360 CUP.
*15,67 €*

---

9. *El Fuerte*
Reciben 🌐 14GB + 📞 115MIN + ✉️ 120SMS x 35 días
*32,29 €*

---

10. *Cacique*
Reciben 🌐 20GB + 📞 165MIN + ✉️ 160SMS x 35 días
*42,27 €*

---

11. *Lo Más Grande*
Reciben 🌐 29GB + 📞 240MIN + ✉️ 240SMS x 35 días
*61,74 €*
```

# CAD

```
📱 PLANES Y RECARGAS DISPONIBLES 📱

1. *Plan 80 MIN*
Reciben 📞 80 minutos nacionales x 35 días
*CAD 7.99*

---

2. *Recarga 600 X5 + Internet*
Reciben 💵 3000 CUP 💵 Saldo + Internet Nocturno de 12 am a 7 am por 30 días
*CAD 33.99*

---

3. *Recarga 500 CUP + Internet x 10 días*
Reciben 💵 500 CUP de 💵 Saldo + Internet ⚡ Ilimitado las 24 h x 10 días
*CAD 29.99*

---

4. *Standard*
Reciben 🌐 9GB + 📞 75MIN + ✉️ 80SMS x 35 días
*CAD 29.99*

---

5. *Recarga 250 CUP*
Tu contacto recibe 💵 250 CUP.
*CAD 15.99*

---

6. *Recarga 250 CUP + 40 MIN*
Reciben 💵 250 CUP y 📞 40 minutos nacionales x 35 días
*CAD 17.99*

---

7. *Plan 3 GB + 40 MIN*
Reciben 🌐 3 GB y 📞 40 minutos nacionales x 35 días
*CAD 17.99*

---

8. *Recarga 360 CUP*
Tu contacto recibe 💵 360 CUP.
*CAD 20.99*

---

9. *El Fuerte*
Reciben 🌐 14GB + 📞 115MIN + ✉️ 120SMS x 35 días
*CAD 43.99*

---

10. *Cacique*
Reciben 🌐 20GB + 📞 165MIN + ✉️ 160SMS x 35 días
*CAD 56.99*

---

11. *Lo Más Grande*
Reciben 🌐 29GB + 📞 240MIN + ✉️ 240SMS x 35 días
*CAD 82.99*
```


# Extracción oferta

¡Claro que sí! 😎🔥  
Podemos hacer que el script **inyecte emojis según el tipo de beneficio detectado** en la descripción o el nombre. Por ejemplo:

- Si encuentra **GB / Internet → 🌐**
    
- Si encuentra **MIN / minutos → 📞**
    
- Si encuentra **SMS → ✉️**
    
- Si encuentra **CUP / saldo → 💵**
    

Aquí te dejo el script mejorado con lógica de emojis:

```javascript
// 📦 Extrae nombre, descripción y precio de cada oferta
const ofertas = Array.from(document.querySelectorAll('[role="button"]')).map(el => {
  const nombre = el.querySelector('p:nth-of-type(1)')?.innerText.trim();
  const descripcion = el.querySelector('p:nth-of-type(2)')?.innerText.trim();
  const precio = el.querySelector('div.MuiBox-root')?.innerText.trim();
  return { nombre, descripcion, precio };
});

// 🎨 Función para añadir emojis automáticamente
function aplicarEmojis(texto) {
  return texto
    .replace(/(\d+ ?GB)/gi, "🌐 $1")
    .replace(/(\d+ ?MIN|\bminutos?\b)/gi, "📞 $1")
    .replace(/(\d+ ?SMS)/gi, "✉️ $1")
    .replace(/(\d+ ?CUP|saldo)/gi, "💵 $1")
    .replace(/(Ilimitado|ilimitada)/gi, "⚡ $1");
}

// 🛠️ Formatea las ofertas al estilo catálogo con emojis
function formatearOfertas(ofertas) {
  let salida = "📱 PLANES Y RECARGAS DISPONIBLES 📱\n\n";

  ofertas.forEach((oferta, i) => {
    salida += `${i + 1}. *${oferta.nombre}*\n`;
    salida += `${aplicarEmojis(oferta.descripcion)}\n`;
    salida += `*${oferta.precio}*\n\n`;
    if (i < ofertas.length - 1) {
      salida += "---\n\n"; // separador entre ofertas
    }
  });

  return salida;
}

// 🚀 Genera el catálogo en texto plano con emojis
const catalogo = formatearOfertas(ofertas);

// 📋 Muestra el resultado en consola listo para copiar
console.log(catalogo);
```

Con esto tu catálogo se arma automáticamente y cada línea detecta palabras clave para añadir el emoji correcto.

https://api.cuballama.com/catalog/offers/cll/TOPUP?operator=CUBACEL&countryCode=CUB&currency=CAD