# Crunchyroll iFrame Player [![Built with love](https://img.shields.io/badge/made%20with-javascript-yellow?style=for-the-badge)](https://github.com/Luco1421/Luco1421.github.io/tree/main/assets/js) [![Downloads](https://img.shields.io/github/downloads/Dev4Mod/crp-iframe-player/total.svg?style=for-the-badge)](https://github.com/Luco1421/Luco1421.github.io/releases/tag/Releases)

Esta es una extension de comunidad que permite ver todo el contenido de Crunchyroll.  
Originalmente criada por [itallolegal](https://github.com/itallolegal) (desativado) e [Hyper-Tx](https://github.com/Hyper-Tx), atualmente mantenida por [mateus7g](https://github.com/mateus7g) y atualizado por [Dev4Mod](https://github.com/Dev4Mod) con el MOD en español por [Luco1421](https://github.com/Luco1421).
Un agradecimento especial a todos los colaboradores.

Muchas Gracias por utilizar. :)

## Download

Usted puede encontrar las últimas versiones disponibles debajo:

<a href="https://github.com/Luco1421/Luco1421.github.io/releases/tag/Releases" target="_blank"><img align="right" alt="Desktop" src="https://img.shields.io/badge/desktop-v1.4.0-violet?style=for-the-badge&logo=windows"></a>

#### Desktop (PC)

Actualmente la version para Desktop está disponible [aqui](https://github.com/Luco1421/Luco1421.github.io/releases/tag/Releases).  
Para instalar ver el paso a paso [para pc](#%EF%B8%8F-como-instalar-desktop).

## 🖥️ Como instalar? (desktop)

La extensión de escritorio solo funciona en los navegadores **basados en Chromium**, como: Google Chrome, Opera, etc.  
Verifique si su browser está atualizado y prosiga:

<img align="right" width="350" height="124" alt="Extrayendo archivo descargado" src="https://github.com/Luco1421/Luco1421.github.io/blob/main/Screenshots/instalacao-3.png?raw=true">

**1** ➜ Proceda [download](#download) el archivo `Crunchyroll_Premium.zip`, y extraiga:

**2** ➜ Entra en la pestaña de [extensiones](https://github.com/Luco1421/Luco1421.github.io/blob/main/Screenshots/instalacao-1.png?raw=true) su navegador (o acceda diretamente [`chrome://extensions`](chrome://extensions))

**3** ➜ Habilite el **Modo programador**, y luego haga clic en el botón **Cargar Extension sin Empaquetar**:

![Habilitando modo programador, y cargando extension](https://github.com/Luco1421/Luco1421.github.io/blob/main/Screenshots/instalacao-2.png?raw=true)

**4** ➜ seleccione la carpeta [que fue extraída](https://github.com/Luco1421/Luco1421.github.io/blob/main/Screenshots/instalacao-4.png?raw=true) al inicio del tutorial

<img align="right" width="350" height="190" alt="Detalles de extension instalada" src="https://github.com/Luco1421/Luco1421.github.io/blob/main/Screenshots/instalacao-5.png?raw=true">

**5** ➜ Si hiciste todo bien, deberías ver esto en tu navegador.

**6** ➜ Ahora mirar y disfrutar 😉

<br /><br /><br />

**Mensajes que actualmente se pueden enviar al jugador a través de un script:**

```yml
tampermonkey: usar un proxy para hacer las solicitudes
lang: código de idioma/localización predeterminado
playback: actualmente sin usar
beta: si usa crunchyroll en beta (requiere pasar old_url)
old_url: url de video en la versión anterior del sitio
up_next_enable: omitir episodios automáticamente (cuando se da up_next)
up_next_cooldown: segundos para finalizar y mostrar la ventana emergente del próximo episodio (0 para deshabilitar la ventana emergente)
up_next: URL del próximo video que se reproducirá/redireccionará (requiere up_next_enable)
force_mp4: obliga a que los videos se reproduzcan en mp4 y no en m3u8 (habilitar esta opción ralentizará la carga, solo se recomienda para chromecasting)
webvideocaster: cambiar el botón de descarga para la transmisión de WebVideoCaster
```

## 📝 Aviso Crunchyroll Beta

El nuevo sitio web de Crunchyroll **rompe por completo** la extensión: [26#issuecomment-1006569041](https://github.com/Dev4Mod/crp-iframe-player/issues/26#issuecomment-1006569041)

Las nuevas versiones (v1.1.0+) **todavía** son compatibles porque al acceder al nuevo sitio, su navegador extrae los datos de video del sitio anterior.
Esto significa que si la versión anterior de Crunchyroll se **reemplaza por completo**, la extensión dejará de funcionar de forma permanente.
