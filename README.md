# 📋 Proyecto Óptica Nur - Sitio Web  
**Desarrollo de una página web estática para promocionar servicios y productos ópticos en Barquisimeto, Venezuela**  

---

## 🌐 Enlace al Sitio  
*(Incluir aquí el link cuando esté publicado)*  

---

## 🛠 Instalación y Configuración  
### **📋 Instrucciones para el Equipo**  

#### **1️⃣ Clonar el repositorio**  
Ejecuta en tu terminal (Git Bash, CMD o PowerShell):  
```bash
git clone https://github.com/[tu-usuario]/Optica-nur-web.git
cd Optica-nur-web
```

#### **2️⃣ Crear tu rama de trabajo**  
Cada uno debe trabajar en su propia rama con el nombre de su página:  
```bash
git checkout -b feature/nombre-de-tu-pagina
```
**Ejemplo**:  
- `feature/contacto` (Caso de Franyel)  

#### **3️⃣ Editar los archivos asignados**  
- Modifica **solo** tu archivo HTML en `/pages` y tu CSS en `/assets/css`.  
- **No edites** `global.css` sin consultar al equipo.  

#### **4️⃣ Guardar cambios (commits)**  
```bash
git add pages/tu-pagina.html assets/css/tu-pagina.css
git commit -m "feat: añade [breve descripción de lo que hiciste]"
```

#### **5️⃣ Subir cambios al repositorio**  
```bash
git push origin feature/nombre-de-tu-pagina
```

#### **6️⃣ Crear un Pull Request (PR)**  
1. Ve a GitHub > Repositorio > Pestaña **"Pull Requests"**.  
2. Haz clic en **"New Pull Request"**.  
3. Compara tu rama (`feature/nombre-de-tu-pagina`) con `main`.  
4. Describe los cambios y asigna a un compañero para revisión.  

---

### **🚨 Reglas importantes**  
✔ **Nunca trabajes directamente en `main`.**  
✔ **Usa siempre tu rama (`feature/...`)**.  
✔ **Haz commits pequeños y descriptivos**.  
✔ **Solicita revisión antes de hacer merge**.  

---

## 🗂 Estructura de Carpetas  
```
Optica-nur-web/
├── assets/
│   ├── css/
│   │   ├── global.css           # Estilos compartidos
│   │   └── [nombre-pagina].css  # CSS específico por página
│   ├── img/
│   │   ├── icons/               # Íconos SVG
│   │   ├── productos/           # Imágenes de catálogo
│   │   └── sedes/               # Fotos de locales
│   └── js/                      # Scripts comunes
│
├── pages/
│   ├── index.html               # Página principal
│   ├── contacto.html            # Contacto
│   ├── catalogo.html            # Catálogo
│   ├── ubicacion.html           # Ubicación
│   └── faqs.html                # Preguntas frecuentes
│
├── .gitignore
└── README.md
```

---

## 🎨 Guía de Estilos  
### Paleta de Colores (Luego Cambiaran)
```css
:root {
  --color-primario: #87CEEB;      /* Azul celeste */
  --color-secundario: #FFFFFF;    /* Blanco */
  --color-texto: #333333;         /* Gris oscuro */
  --color-fondo: #F8F9FA;         /* Gris claro */
}
```

### Tipografía (Posibles cambios, aunque la Tipografía es Bonita)
- **Familia principal**: `Poppins`  
- **Tamaños**:  
  ```css
  .titulo-primipal { font-size: 2.5rem; }
  h2 { font-size: 2rem; }
  p { font-size: 1.1rem; }
  ```

### Componentes Reutilizables  
| Componente | Clase CSS | Uso |  
|------------|-----------|-----|  
| Botón | `.btn` | Acciones principales |  
| Tarjeta | `.tarjeta` | Contenedor de productos/info |  
| Sección | `.seccion` | Bloques de contenido |  

---

## 💻 Convenciones de Código  
1. **HTML**:  
   - Usar etiquetas semánticas (`<header>`, `<section>`, `<article>`)  
   - Atributo `alt` en todas las imágenes  
   ```html
   <img src="assets/img/logo.svg" alt="Óptica Nur - Logo">
   ```

2. **CSS**:  
   - Usar variables globales  
   - Prefijar clases específicas:  
   ```css
   /* Contacto */
   .contacto-formulario { ... }
   
   /* Catálogo */
   .catalogo-producto { ... }
   ```

3. **Nomenclatura**:  
   - Archivos en **minúsculas** con guiones: `preguntas-frecuentes.html`  
   - Clases en **lowercase**: `.galeria-productos`

---

## ✅ Tareas Pendientes  
- [ ] Implementar menú móvil  
- [ ] Definir paleta de colores final  
- [ ] Optimizar imágenes  
- [ ] Pruebas de accesibilidad  
- [ ] Imagenes del lugar
- [ ] Formulario de contacto
- [ ] Logo de la página
- [ ] Listas de FAQS 
- [ ] Lista de productos

---

## 👥 Asignación de Páginas  
| Página | Responsable | Estado |  
|--------|------------|--------|  
| Inicio | Javier Nieto | 🟡 En progreso |  
| Contacto | Sebastián Valera | 🟡 En progreso |  
| Catálogo | Virginia Alvarado | 🟡 En progreso |  
| Ubicación | Franyel Pacheco | 🟡 En progreso |  
| FAQs | Santiago Briceño | 🟡 En progreso |  

> ⚠️ **Importante**: Todos los cambios a `global.css` deben ser aprobados por 2 miembros del equipo.
