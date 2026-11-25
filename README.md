# Gremio Gamer — Negocios Informáticos del Gremio Gamer

Web de una tienda de montaje de PCs a medida. Es la empresa ficticia de nuestro proyecto de 1º de SMR: tiene un catálogo de equipos montados, un configurador que comprueba la compatibilidad de las piezas y un formulario para pedir presupuesto.

**En vivo:** https://niggremio.web.app

## Tecnologías

- HTML5 semántico
- CSS3 (Grid, Flexbox, propiedades personalizadas)
- JavaScript (sin frameworks ni dependencias)
- Firebase Hosting
- Google Fonts (Chakra Petch y Source Sans 3)

## Qué tiene

- **Catálogo de equipos**: cinco PCs montados con filtros por uso (gaming, creadores, oficina y estudio) y un botón «Personalizar» que carga cada uno en el configurador.
- **Configurador con compatibilidad**: comprueba el socket del procesador y la placa, el tipo de RAM, si hace falta gráfica dedicada, el formato de la placa en la caja, la longitud de la gráfica, la potencia de la fuente, el disipador y el Wi-Fi. El total con el 21 % de IVA se actualiza al momento.
- **Presupuesto**: el formulario prepara un correo con la configuración elegida, o la copia para pegarla donde quieras.
- **Condiciones claras**: entrega en 5 días laborables, garantía del fabricante más 1 año de montaje, pago 50 % y 50 %, presupuestos válidos 15 días. Los equipos se entregan sin sistema operativo.
- **Páginas legales**: aviso legal, política de privacidad y política de cookies en una ventana dentro de la propia página.
- **Adaptada a móvil**.

Todos los datos de la empresa (dirección, teléfono, correo y NIF) son ficticios.

## Estructura

```
firebase.json     Configuración de Firebase Hosting y cabeceras de caché
.firebaserc       A qué proyecto de Firebase se despliega
public/           Todo lo que se publica
  index.html      La web completa (estilos y código incluidos)
  logo-oscuro.png Logo para fondo oscuro
  favicon...      Iconos de pestaña y de móvil
```

## Cómo desplegarlo

```bash
firebase deploy --only hosting
```

Se despliega en el proyecto de Firebase `niggremio`.

---

Hecho por **Enrique Segura** y **Marcos Martínez** — 1º SMR.
