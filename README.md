# Criptoanálisis mediante análisis de frecuencias

Este código Python tiene como objetivo realizar un criptoanálisis a través del análisis de frecuencias de un mensaje cifrado. El proceso se lleva a cabo en dos etapas principales:

Contar la frecuencia de cada letra en el mensaje cifrado.
Sustituir cada letra del mensaje cifrado por la letra más común en el idioma español.
El código comienza importando la clase Counter desde el módulo collections. Luego, se define la variable text con el mensaje cifrado. La función Counter se utiliza para contar la frecuencia de cada letra en el mensaje cifrado y el resultado se guarda en la variable letters.

Después, se reemplazan las letras del mensaje cifrado por las letras más comunes en el idioma español utilizando la función replace(). Cada letra del mensaje cifrado se reemplaza por la letra más común correspondiente en el idioma español. Por ejemplo, la letra "X" se reemplaza por la letra "e", ya que "e" es la letra más común en el idioma español.

Finalmente, se imprime el mensaje decodificado en la pantalla.
