# Naruto

[English](README.md) · **Español**

Tema oscuro para Omarchy inspirado en Naruto: carbón casi negro, naranja ámbar,
amarillo dorado y rojo coral, con texto marfil y comentarios en gris cálido.

## Paleta

`colors.toml` es la única fuente de colores. Omarchy genera a partir de ella
los archivos de todas las apps (terminal, Hyprland, btop, Neovim, etc.), así que
el tema no necesita Lua ni configuraciones propias.

- La paleta es cálida (naranja, dorado, coral), pero verde y azul son tonos
  apagados de verdad (verde hoja y azul acero) para que en la terminal se
  distingan bien los diffs, los errores y los avisos.
- En Neovim (Aether v3): palabras clave naranjas, funciones azul acero, cadenas
  color pergamino y errores coral.
- Íconos: `icons.theme` usa Yaru con carpetas naranjas.

Si tu configuración de Neovim fuerza la transparencia, desactívala para
conservar los fondos oscuros del tema.

## Instalación

```sh
omarchy theme install https://github.com/zamuxdev/omarchy-naruto-theme
```

O copia esta carpeta a `~/.config/omarchy/themes/naruto` y ejecuta:

```sh
omarchy theme set naruto
```

Si editas `colors.toml`, vuelve a ejecutar el mismo comando para aplicar los cambios.

## Fondos

El tema incluye dos fondos:

- `backgrounds/nostalgia-minimal.png`: un columpio dibujado a lápiz sobre fondo
  carbón, con hojas naranjas cayendo. Es una ilustración generada con IA para este
  tema, con referencias indirectas y sin logos ni fotogramas del anime.
- `backgrounds/omarchy.png`: el logo de Omarchy en naranja ámbar sobre carbón,
  con los colores del tema.

Puedes agregar otros fondos a `~/.config/omarchy/backgrounds/naruto/`
y cambiarlos con:

```sh
omarchy theme bg next
```

Quedan bien los fondos oscuros con tonos naranjas o dorados.

## Nota

Tema no oficial. Naruto y sus personajes pertenecen a sus respectivos
titulares; este tema no está afiliado ni respaldado por ellos.
