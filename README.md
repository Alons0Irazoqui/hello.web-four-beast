# Four Beats – The Tribute | Brief de Proyecto Web

## 1. Resumen del proyecto

- **Tipo de proyecto:** Landing page.
- **Negocio:** Four Beats – The Tribute (banda tributo a The Beatles).
- El desarrollo se realiza sobre una **plantilla base de HTML ya existente**. La estructura de secciones de la página ya está definida por esa plantilla y debe respetarse tal cual: este documento **no indica** qué secciones debe tener la página.
- Ya se entregó por separado un **prompt inicial** para adaptar la plantilla al negocio. Este README es el brief complementario con la información de marca, del negocio y los requisitos visuales.

## 2. Información del negocio

Toda la información de contacto y operativa del negocio (teléfono, dirección, horarios, servicios/shows, redes sociales, etc.) debe obtenerse directamente de la página de Facebook oficial:

**https://web.facebook.com/profile.php?id=61572524777031**

No se recibió ningún documento con estos datos, por lo que es responsabilidad del desarrollador entrar a la página, revisar la sección "Información"/"Acerca de", las publicaciones y cualquier dato de contacto visible, y volcar esa información en la plantilla.

Dato confirmado en la página: el negocio es una banda tributo a The Beatles llamada **"Four Beats – The Tribute"**, con actividad en la zona de León. Cualquier otro dato (teléfono, dirección exacta, horarios, servicios, redes adicionales) debe confirmarse directamente en Facebook, ya que no fue posible acceder al contenido completo del perfil de forma automática.

## 3. Branding (a partir del logo)

Fuente analizada: `imagenes/logo.jpeg`

### Paleta de colores

| Color | HEX | Uso sugerido |
|---|---|---|
| Negro | `#000000` | Texto principal, siluetas, fondos oscuros |
| Blanco | `#FFFFFF` | Fondos claros, espacios negativos |
| Rojo Beatles | `#C8102E` | Acentos, CTAs, detalles de marca (color del texto "The Tribute" del logo) |
| Azul marino (bandera UK) | `#012169` | Acentos secundarios |

### Tipografía sugerida

- **Encabezados / Display:** fuente serif de alto contraste y trazo grueso (ej. Playfair Display, Abril Fatface o Bodoni), inspirada en el wordmark "FOUR BEATS" del logo.
- **Acentos / detalles tipo firma:** fuente estilo máquina de escribir con letter-spacing (ej. Special Elite, Courier Prime), inspirada en el texto "The Tribute" del logo.
- **Cuerpo de texto / UI:** fuente sans-serif moderna y limpia (ej. Inter, Helvetica Neue), para sostener el estándar premium/big tech exigido sin sacrificar legibilidad.

### Identidad visual

- Estética inspirada en la Beatlemanía: siluetas en blanco y negro con el corte de cabello característico, bandera del Reino Unido y tipografía retro de alto contraste.
- El reto de diseño es fusionar esta identidad vintage/rock con una ejecución visual moderna, minimalista y de nivel big tech (ver sección 4): se conservan los colores y motivos de marca, pero la ejecución (espaciado, jerarquía, composición) debe sentirse actual y premium, no como un póster de los años 60.

## 4. Estilo visual obligatorio

El proyecto debe manejar:

- Estilo **premium, enterprise y corporativo** de marca.
- Nivel **big tech**: elegante y a la vez minimalista.

## 5. Efectos y animaciones requeridos

- Efectos visuales y animaciones activadas por scroll.
- Pantalla de carga (**preloader**) con spinner + logo del negocio.
- Animación en el título del hero: efecto **máquina de escribir**, **cambio de color en las letras** u otros efectos tipográficos equivalentes.

## 6. Assets

- El logo (`imagenes/logo.jpeg`) viene **con fondo blanco**: se debe **remover el fondo** antes de usarlo en el sitio (ej. remove.bg, Photoshop o una herramienta de IA) y exportarlo en PNG con transparencia.
- Al venir en formato JPEG, evaluar si la resolución es suficiente para los tamaños en los que se usará el logo (preloader, header, etc.); si se ve pixelado al escalar, reconstruirlo o vectorizarlo.
- En la carpeta `imagenes/` solo se incluyó el logo. No hay fotos adicionales del negocio (banda, shows, eventos, etc.): cualquier fotografía o material visual adicional debe obtenerse de la página de Facebook del negocio.

## 7. Nota para el desarrollador

Este brief es un punto de partida, no un documento cerrado. Podés **iterar sobre el proyecto dándole instrucciones a Claude Code las veces que sea necesario** hasta lograr el resultado deseado: ajustar colores, tipografías, animaciones, textos, etc.

## 8. Checklist

- [ ] Extraer del Facebook del negocio: teléfono, dirección, horarios, servicios/shows y cualquier otro dato de contacto.
- [ ] Remover el fondo del logo y exportarlo en PNG transparente.
- [ ] Aplicar la paleta de colores y la tipografía de marca a la plantilla base.
- [ ] Adaptar el contenido de la plantilla base al negocio usando el prompt inicial ya entregado (sin modificar la estructura de secciones).
- [ ] Implementar el preloader con spinner + logo.
- [ ] Implementar animaciones/efectos de scroll.
- [ ] Implementar la animación del título del hero (máquina de escribir / cambio de color / efecto tipográfico equivalente).
- [ ] Validar que el resultado final tenga un acabado premium, enterprise y minimalista tipo big tech.
- [ ] Iterar con Claude Code sobre el resultado hasta cerrar el proyecto.
