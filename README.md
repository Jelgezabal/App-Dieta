# App-Dieta

🚀 Instalación y Uso
1. Clona el repositorio
bash
git clone https://github.com/jegezabal/App-Dieta.git
2. Abre el archivo en tu navegador

    No se requiere instalación adicional, ya que es una aplicación web basada en HTML, CSS y JavaScript.
    Abre el archivo index.html (versión más reciente) en tu navegador favorito (Chrome, Firefox, etc.).
    Nota: El repositorio incluye versiones anteriores (index1.0.html, index1.1.html, index1.2.html) que reflejan la evolución del proyecto. Si deseas probar una versión específica, abre el archivo correspondiente.

3. Personaliza tu dieta

    Selecciona el usuario (Jon o Ainhoa) y el tipo de día (Entrenamiento o Descanso).
    Ajusta tu peso en el campo correspondiente.
    Modifica las cantidades de alimentos y suplementos directamente en las tablas.
    Observa cómo se actualizan los totales y el déficit calórico en tiempo real.

4. Cambia el tema

    Haz clic en el círculo en la esquina superior derecha para alternar entre modo claro (fondo claro, botón amarillo) y modo oscuro (fondo oscuro, botón gris).

📊 Ejemplo de Uso
Jon - Día de Descanso (usando index.html)

    Desayuno:
        Claras de Huevo: 100 g → 33.0 Kilocal | 11.0 Proteína | 0.4 Hidratos | 0.0 Grasa | 0.0 Fibra
        Huevo Completo: 60 g → 85.8 Kilocal | 7.6 Proteína | 0.7 Hidratos | 5.7 Grasa | 0.0 Fibra
        Harina de Avena: 30 g → 117.0 Kilocal | 3.9 Proteína | 20.4 Hidratos | 2.1 Grasa | 2.7 Fibra
        Fresas: 0 g → 0.0 Kilocal | 0.0 Proteína | 0.0 Hidratos | 0.0 Grasa | 0.0 Fibra
        Aguacate: 50 g → 80.0 Kilocal | 1.0 Proteína | 4.3 Hidratos | 7.4 Grasa | 3.4 Fibra
        Nueces: 15 g → 98.1 Kilocal | 2.3 Proteína | 2.1 Hidratos | 9.8 Grasa | 1.0 Fibra
        Subtotal Desayuno: 413.9 Kilocal | 25.8 Proteína | 27.9 Hidratos | 25.0 Grasa | 7.1 Fibra
    Totales Generales:
        Kilocal: 1496.9 | Proteína: 132.8 | Hidratos: 97.9 | Grasa: 62.0 | Fibra: 14.1
        Déficit calórico: 614.31 kcal (TDEE: 2111 kcal) - 478-797 gramos por semana

🛠️ Tecnologías Utilizadas

    HTML5: Estructura de la aplicación.
    CSS3: Estilos responsivos y modo claro/oscuro.
    JavaScript: Lógica para cálculos de macros, TDEE, y actualización dinámica de las tablas.

📂 Estructura del Repositorio

    index.html: Versión más reciente de la aplicación.
    index1.0.html: Primera versión de la app.
    index1.1.html: Versión con ajustes iniciales (nombres de columnas optimizados).
    index1.2.html: Versión con ajustes para días de descanso de Jon.
    README.md: Documentación del proyecto.

📝 Notas

    Las dietas están predefinidas para Jon y Ainhoa, pero puedes modificar las cantidades de alimentos y suplementos según tus necesidades.
    El cálculo del TDEE se basa en la fórmula de Harris-Benedict, ajustada por un factor de actividad (1.55 para días de entrenamiento, 1.375 para días de descanso).
    La estimación de pérdida de peso asume que 7700 kcal equivalen a 1 kg de grasa, con un rango conservador del 60%-100%.

🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar la app, sigue estos pasos:

    Haz un fork del repositorio.
    Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
    Realiza tus cambios y haz commit (git commit -m "Añadir nueva funcionalidad").
    Sube tus cambios (git push origin feature/nueva-funcionalidad).
    Abre un Pull Request.

📜 Licencia

Este proyecto está bajo la licencia . Siéntete libre de usarlo y modificarlo según tus necesidades.
🌟 ¡Dale una estrella!

Si te gusta este proyecto, no olvides darle una ⭐ en GitHub. ¡Tu apoyo significa mucho!

Creado con ❤️ por jegezabal
Instrucciones para usar el README

    Añade el README a tu repositorio:
        Crea un archivo llamado README.md en la raíz de tu repositorio (App-Dieta).
        Copia y pega el contenido de arriba.
        Sube el archivo a GitHub:
        bash

    git add README.md
    git commit -m "Añadir README"
    git push

Añade una licencia (opcional):

    Si mencionas la licencia MIT, crea un archivo LICENSE en tu repositorio con el texto de la licencia MIT. Puedes copiarlo de este enlace o usar el siguiente contenido:
    text

MIT License

Copyright (c) 2025 jegezabal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
