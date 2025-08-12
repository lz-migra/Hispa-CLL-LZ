Aquí tienes la lista actualizada con los datos de las nuevas imágenes, respetando el formato original y dentro de un recuadro de texto plano:

```
📱 PLANES Y RECARGAS DISPONIBLES 📱
⠀
1. *Plan 80 MIN*  
📞 Reciben 80 minutos nacionales x 35 días  
*$5.99*  
⠀
---  
⠀
2. *Recarga 500 CUP + Internet x 10 días*  
💵 Reciben 500 CUP de Saldo  
🌐 Internet Ilimitado las 24 h x 10 días  
*$22.99*  
⠀
---  
⠀
3. *Recarga 600 CUP + 25 GB + Internet*  
💵 Reciben 600 CUP Saldo  
🌐 25 GB + Internet Nocturno de 12 am a 7 am por 35 días  
*$25.99*  
⠀
---  
⠀
4. *Standard*  
🌐 9GB + 📞 75 MIN + ✉️ 80 SMS x 35 días  
*$22.99*  
⠀
---  
⠀
5. *Recarga 250 CUP + 40 MIN*  
💵 Reciben 250 CUP y 📞 40 minutos nacionales x 35 días  
*$13.99*  
⠀
---  
⠀
6. *Recarga 250 CUP*  
💵 Tu contacto recibe 250 CUP  
*$11.99*  
⠀
---  
⠀
7. *Plan 3 GB + 40 MIN*  
🌐 Reciben 3 GB y 📞 40 minutos nacionales x 35 días  
*$13.99*  
⠀
---  
⠀
8. *Recarga 360 CUP*  
💵 Tu contacto recibe 360 CUP  
*$16.50*  
⠀
---  
⠀
9. *El Fuerte*  
🌐 14GB + 📞 115 MIN + ✉️ 120 SMS x 35 días  
*$33.99*  
⠀
---  
⠀
10. *Cacique*  
🌐 20GB + 📞 165 MIN + ✉️ 160 SMS x 35 días  
*$44.49*  
⠀
---  
⠀
11. *Lo Más Grande*  
🌐 29GB + 📞 240 MIN + ✉️ 240 SMS x 35 días  
*$64.99*  
```

# CAD

```
📱 PLANES Y RECARGAS DISPONIBLES 📱
⠀
1. *Plan 80 MIN*  
📞 Reciben 80 minutos nacionales x 35 días  
*CAD 7.99*  
⠀
---  
⠀
2. *Recarga 500 CUP + Internet x 10 días*  
💵 Reciben 500 CUP de Saldo  
🌐 Internet Ilimitado las 24 h x 10 días  
*CAD 29.99*  
⠀
---  
⠀
3. *Recarga 600 CUP + 25 GB + Internet*  
💵 Reciben 600 CUP Saldo  
🌐 25 GB + Internet Nocturno de 12 am a 7 am por 35 días  
*CAD 33.99*  
⠀
---  
⠀
4. *Standard*  
🌐 9GB + 📞 75 MIN + ✉️ 80 SMS x 35 días  
*CAD 29.99*  
⠀
---  
⠀
5. *Recarga 250 CUP + 40 MIN*  
💵 Reciben 250 CUP y 📞 40 minutos nacionales x 35 días  
*CAD 17.99*  
⠀
---  
⠀
6. *Recarga 250 CUP*  
💵 Tu contacto recibe 250 CUP  
*CAD 15.99*  
⠀
---  
⠀
7. *Plan 3 GB + 40 MIN*  
🌐 Reciben 3 GB y 📞 40 minutos nacionales x 35 días  
*CAD 17.99*  
⠀
---  
⠀
8. *Recarga 360 CUP*  
💵 Tu contacto recibe 360 CUP  
*CAD 20.99*  
⠀
---  
⠀
9. *El Fuerte*  
🌐 14GB + 📞 115 MIN + ✉️ 120 SMS x 35 días  
*CAD 43.99*  
⠀
---  
⠀
10. *Cacique*  
🌐 20GB + 📞 165 MIN + ✉️ 160 SMS x 35 días  
*CAD 56.99*  
⠀
---  
⠀
11. *Lo Más Grande*  
🌐 29GB + 📞 240 MIN + ✉️ 240 SMS x 35 días  
*CAD 82.99*  
```

Extracción oferta
```
// 📦 Extrae nombre, descripción y precio de cada oferta
const ofertas = Array.from(document.querySelectorAll('[role="button"]')).map(el => {
  const nombre = el.querySelector('p:nth-of-type(1)')?.innerText.trim();
  const descripcion = el.querySelector('p:nth-of-type(2)')?.innerText.trim();
  const precio = el.querySelector('div.MuiBox-root')?.innerText.trim();
  return { nombre, descripcion, precio };
});

console.log("📋 Ofertas encontradas:", ofertas);
```