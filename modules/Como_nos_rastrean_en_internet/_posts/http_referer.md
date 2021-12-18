## Campo HTTP referer

Otro de los métodos a través de los cuales pueden rastrearnos es el campo referer de la cabecera HTTP.

Este campo es opcional y hace referencia a la dirección del servicio web desde el que hemos llegado al servicio web o recursos en el que estamos (por ejemplo cuando vamos a una web desde un enlace insertado en otra).

Por lo general suele utilizarse en la creación de estadísticas, para permitir iniciar sesión de forma rápida o para cargar de forma más óptima imágenes u otros recursos pero también tiene otros usos más problemáticos que violan nuestra privacidad ya que pueden servir también para recabar información sobre nosotros y nuestra navegación o incluso provocar una fuga accidental de información.

Por ejemplo, si venimos de un servicio web que contiene información sensible en la URL (como podría ser un token de autenticación), dicha información sería transmitida al nuevo servicio web al que hayamos accedido a través de un enlace insertado en el primero debido a que éste recibiría en el campo HTTP referer la URL con dicho token.

Por fortuna existen extensiones que nos permiten bloquear este tipo de cabecera y de las cuales hablaremos más adelante.