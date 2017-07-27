# BetterFormattingRedux (BFRedux) - [Download](https://raw.githubusercontent.com/rauenzi/BetterDiscordAddons/master/Plugins/BetterFormattingRedux/BetterFormattingRedux.plugin.js)

Una re edición de BetterFormatting de Anxeal que incluye nuevas opciones y configuraciones. Para soporte y anuncios de actualizaciones tu puedes visitar [el servidor de Zere](http://discord.zackrauen.com/).

**Nota:** ~~Actualmente incompatible con Canary~~ La compatibilidad con Canary/PTB fue resuelta.

![BFRedux Demo](https://zippy.gfycat.com/HugeDeadDuckling.gif)

Sientete libre de mandarle un mensaje directo a el creador del plugin (Zerebos#7790) con cualquier pedido de caracteristica o reporte de bugs. Solo abre una sugerencia [aquí en GitHub (En Ingles unicamente por favor.)](https://github.com/rauenzi/BetterDiscordAddons/issues).

## Caracteristicas

### Barra de herramientas de formato
BFRedux agrega una barra de herramientas útil para facilitar el formato.

Haz clic en los botones para insertar etiquetas o rodear el texto seleccionado con etiquetas.

![BFRedux Demo](http://discord.zackrauen.com/BFRedux/bfredux.png)

### Nuevas opciones de formato

#### SuperÍndice (^)
`^Texto de Ejemplo^` deberia mostrarse como ᵀᵉˣᵗᵒ ᵈᵉ ᴱʲᵉᵐᵖˡᵒ

#### Small Caps (%)
`%Texto de Ejemplo%` deberia mostrarse como Tᴇxᴛᴏ ᴅᴇ Eᴊᴇᴍᴘʟᴏ

#### Fullwidth (##)
`##Texto de Ejemplo##` deberia mostrarse como Ｔｅｘｔｏ　ｄｅ　Ｅｊｅｍｐｌｏ o T E X T O   D E   E J E M P L O

#### Invertir (&&)
`&&Texto de Ejemplo&&` deberia mostrarse como oldɯǝɾƎ ǝp oʇxǝ┴ o ┴ǝxʇo pǝ Ǝɾǝɯdlo

#### Letras Variadas (||)
`||Texto de Ejemplo||` deberia mostrarse como TeXtO dE eJeMpLo o tExTo De EjEmPlO

#### Escaping Unwanted Tags (\\)
Ponga una barra invertida antes de las etiquetas si desea que se representen normalmente.

`\##Texto de Ejemplo\##` deberia mostrarse como \##Texto de Ejemplo\##

## Opciones del Plugin

Los ajustes se pueden encontrar en Ajustes del Usuario > BetterDiscord > Plugins

Nota: No hay botón Guardar para hacer clic, la configuración se actualiza automáticamente.

### Etiquetas
Las etiquetas predeterminadas (`^`, `%`, `##`, `&&`, `||`) se pueden personalizar en el panel de configuración. Pueden ser cualquier símbolo o letras de cualquier longitud.

![BFRedux Wrappers](http://discord.zackrauen.com/BFRedux/wrappers.png)

### Formatos
 - El formato de fullwidth puede cambiar entre Ｔｅｘｔｏ　ｄｅ　Ｅｊｅｍｐｌｏ y T E X T O   D E   E J E M P L O
 - El texto invertido puede cambiar entre oldɯǝɾƎ ǝp oʇxǝ┴ y ┴ǝxʇo pǝ Ǝɾǝɯdlo.
 - Las letras variadas pueden cambiar entre TeXtO dE eJeMpLo and tExTo De EjEmPlO. (Cambia si se debe comenzar por letra capital o no)
 
![BFRedux Formatting](http://discord.zackrauen.com/BFRedux/formatting_new.png)
 
### Funcion de Configuración del Plugin
![BFRedux Chaining](http://discord.zackrauen.com/BFRedux/functional.png)

 - Tu puedes cambiar la opción de ver la barra de herramientas entre pasar el mouse por encima (desde arriba), o haciendo click.
 
![BFRedux Click Mode](https://zippy.gfycat.com/RectangularGargantuanIndianjackal.gif)
 - Opcionalmente, puede hacer que desaparezca cuando se envía el mensaje
 
![BFRedux Send Clear](https://zippy.gfycat.com/IllfatedDimpledGalapagossealion.gif)

 - También puede cambiar el orden de encadenamiento de formato desde el exterior primero al interior primero lo que significa:
 
`&&##Texto de Ejemplo##&&` dara ｏｌｐｍｅｊＥ　ｅｄ　ｏｔｘｅＴ en lugar de ｏｌｄɯǝɾƎ　ǝｐ　ｏʇｘǝ┴ (Puede que no se muestre bien en algunos navegadores)

`##&&Texto de Ejemplo&&##` dara ｏｌｄɯǝɾƎ　ǝｐ　ｏʇｘǝ┴ en lugar de ＆＆Ｔｅｘｔｏ　ｄｅ　Ｅｊｅｍｐｌｏ＆＆ (Puede que no se muestre bien en algunos navegadores)

 ![BFRedux Chaining](http://discord.zackrauen.com/BFRedux/chaining_order.png)
 
### Configuración del Estilo
![BFRedux Style](http://discord.zackrauen.com/BFRedux/style.png)

 - Cambiar la opacidad de la barra de herramientas
 - Cambiar el tamaño del texto
 - Cambiar la barra de herramientas (y la flecha) desde el lado derecho (encima) a el lado izquierdo
 
 ![BFRedux Sideswap](https://zippy.gfycat.com/FlusteredViciousEnglishpointer.gif)


 

## Coming Soon (Possibly)
 - Code Blocks (```) and the auto-inserting languages
 - 1337 (Leet) formatting
 - Ability to enable/disable which formats are on the toolbar

## Known Bugs and Issues
 - ~~Clicking the buttons on the toolbar too rapidly will cause the tags to be inserted on a different place than where the caret is and move the caret.~~ Should be resolved

## Special Thanks
 - Anxeal#4160 for the original Better Formatting - This is based on the original BetterFormatting by Anxeal#4160 although it has been nearly entirely rewritten. You can find that [here](https://github.com/Anxeal/BDEnhancements/tree/master/plugins/BetterFormatting). 
 - BeardDesign#6223 - The CSS for the toolbar is a modified version of the CSS written by BeardDesign creator of Beard's Material Design Theme, a theme for BetterDiscord. His theme is compatible with several plugins so be sure to check it out [here](http://www.beard-design.com/discord-material-theme).
 
## Changelog

#### 2.0.0
 
 - Complete rewrite to ES6 style classes
 - Refactor settings code to be more generic
 - Remake settings panel
 - Add new setting types (Pill, Slider)
 - New setting: opacity
 - New setting: font size
 - Fix issue with toolbar closing
 - Remove need to save default discord wrappers
 - Improved and reduced parsing for formatting
 - Other minor code cleaning

#### 1.1.5

 - Fixes toolbar not showing up in Canary/PTB
 - Fixes not actually changing the text before sending in Canary/PTB

#### 1.1.4

 - Adds update notification in settings panel.
 - Added the ability to swap the toolbar (and the arrow) from the right hand side to the left hand side (by popular demand)
 - Added in the features promised last time, I made a goof and committed the wrong file
 - Fixed a bug where button would reload discord (and also pressing enter)
 - Update description in discord

#### 1.1.3

 - Added settings to close the toolbar on message send (when hover is turned off)
 - Added ability to change format chaining order and the corresponding setting in the panel
 - Fixed a bug where backslash didn't prevent formatting
 - CSS bugfixes

#### 1.1.2

 - New CSS courtesy of Beard Design
 - Settings panel cleanup
 - Backend of settings abstracted for future development
 - New setting to click open versus hover open

#### 1.1.1

 - Squashed more bugs
 - Half-baked code cleaning
 - Initial release for testing

#### 1.1.0

 - Added varied caps formatting
 - Settings panel created
 - Squashed a couple pesky bugs

#### 1.0.0

 - Initial version of this rewrite
 - Abstracted wrapper replacement
 - Improved Regex
 - Added capability for multiple character wrappers

