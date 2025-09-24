# 🎁 Amigo Secreto

Un juego interactivo desarrollado en **HTML, CSS y JavaScript** que permite organizar de manera sencilla un sorteo de *Amigo Secreto*.  
Podrás agregar los nombres de los participantes, eliminarlos si lo deseas y finalmente sortear de manera aleatoria un amigo secreto.  

## ✨ Funcionalidades

- **Agregar participantes**:  
  Escribe un nombre y presiona **Añadir** o la tecla **Enter** para incluirlo en la lista.  

- **Validación inteligente**:  
  - No se admiten nombres vacíos.  
  - No se permiten duplicados (la comparación no distingue mayúsculas/minúsculas).  

- **Gestión de lista**:  
  - Visualización de todos los nombres añadidos.  
  - Cada participante puede ser eliminado fácilmente con el botón **Eliminar**.  

- **Sorteo aleatorio**:  
  - Presiona el botón **Sortear amigo** para obtener un nombre elegido al azar.  
  - El resultado se muestra de manera destacada y con animación visual.  

- **Accesibilidad (a11y)**:  
  - Uso de roles ARIA y `aria-live` para que lectores de pantalla anuncien los cambios.  
  - Botones con etiquetas y títulos descriptivos.  

- **Diseño responsivo y visual atractivo**:  
  - Estilos personalizados en **CSS**.  
  - Uso de tipografías de Google Fonts.  
  - Fondos e íconos incluidos en la carpeta `assets/`.  

---

## 📂 Estructura del proyecto

```
.
├── index.html
├── style.css
├── app.js
└── assets/
    ├── amigo-secreto.png
    └── play_circle_outline.png
```

- **index.html** → Contiene la estructura principal de la aplicación.  
- **style.css** → Define el estilo visual del juego.  
- **app.js** → Contiene toda la lógica del sorteo, manejo de lista y validaciones.  
- **assets/** → Carpeta con imágenes utilizadas como fondo e íconos.  

---

## 🚀 Cómo ejecutar el proyecto

1. Descarga o clona el repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/amigo-secreto.git
   ```

2. Abre el archivo **index.html** en tu navegador favorito (no requiere servidor adicional).  

3. ¡Listo! Comienza a agregar los nombres de tus amigos y realiza el sorteo. 🎉  

---

## 🛠️ Tecnologías utilizadas

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**  

---

## 🔮 Posibles mejoras futuras

- Evitar que un participante se asigne a sí mismo (modo emparejamiento real de amigo secreto).  
- Guardar la lista de amigos en **localStorage** para que no se pierda al recargar la página.  
- Exportar los resultados del sorteo en formatos como **CSV, TXT o PDF**.  
- Añadir animaciones más avanzadas en el sorteo (por ejemplo, efecto de ruleta).  
