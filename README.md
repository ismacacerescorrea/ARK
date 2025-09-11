Plugin ARK para OJS 3.5 

Antes de cualquier de cualquier otro asunto, advierto que soy editor (licenciado en educación) y no ingeniero. Mis conocimientos son experimentales, en la práctica del oficio de editor. Todo lo que acá aparezca debe ser considerado con ese cuidado, aunque se asegura que para la versión OJS 3.5.0.1 funciona correctamente.
Lo que hice fue tomar el modelo de módulo de URN y lo modifiqué para que funcionara con el ARK. Cambié lógicas para que se adaptara a las formas específicas del NAAN; seguramente alguien con conocimientos profesionales lo podrá mejorar. Mi interés es académico y no comercial, por lo que esta modificación la hice de forma relajada y sabiendo que quienes lo necesiten dentro de la comunidad podrán hacer sus propias versiones mejoradas.

Al instalar este módulo se habilitará la opción de agregar un ARK a los números, artículos o galeradas según se elija. Permitirá agregar el NAAN personalizado de la revista (se solicita en forma general a la ARK Alliance, pero también existe el proyecto particular argentino del ARK CAYCIT, exclusivo para revistas de ese país). Un NAAN se ve como "ark:/12345/".
Permite agregar un resolvedor personalizado, por ejemplo: "https://n2t.net/".
Permite elegir cómo es que se asignará el nuevo ARK. Entre las opciones está automatizarlo o agregar de forma manual.

Personalmente maqueto XML-JATS, si te interesa me puedes contactar a mi correo contacto@gestioneditorial.cl

# Instalación

1. Diríjase al menú de módulos y presione el botón de agregar nuevos módulos.
2. Cargue el archivo comprimido .tar.gz (no le funcionará otro tipo de compresión)
3. Presione el botón de instalar.
4. Busque el módulo en la lista de módulos instalados y actívelo.
5. El módulo aparecerá con el nombre ARK en la tabla de contenidos"
