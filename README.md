# Lumane Sagoal – Tokenized Photography

**Portfolio web de fotografías tokenizadas** desarrollado como proyecto universitario. Esta página permite mostrar obras de **Lumane Sagoal** como NFTs, conectándose directamente con **OpenSea** y ofreciendo integración con **MetaMask** para la conexión de wallets.

---

## 🔹 Descripción del proyecto

Este portfolio tiene como objetivo **combinar fotografía y tecnología blockchain**. Permite:

- Visualizar fotografías tokenizadas directamente desde OpenSea.  
- Conectar la wallet de MetaMask para interacción con la blockchain (solo lectura en este caso).  
- Mostrar la galería de forma **responsive**, adaptándose a distintos dispositivos (desktop, tablet, móvil).  
- Usar un diseño moderno y limpio con **Tailwind CSS**.

---

## 🔹 Tecnologías utilizadas

- **HTML5**  
- **Tailwind CSS** (vía CDN)  
- **JavaScript**  
- **OpenSea API** para traer las imágenes de los NFTs  
- **MetaMask** para conexión de wallet  

---

## 🔹 Cómo usarlo

### 1️⃣ Subir el proyecto a GitHub Pages

1. Crear un repositorio en GitHub (por ejemplo `lumane-portfolio`).  
2. Subir el archivo `index.html` (y cualquier otro archivo adicional si se agregara).  
3. Activar **GitHub Pages** en `Settings → Pages → Source: main branch / root`.  
4. Esperar unos minutos; la URL final será algo como:  

---

### 2️⃣ Cargar NFTs en la galería

1. Abrir el portfolio en el navegador.  
2. Ir a la sección **Ajustes**.  
3. Ingresar:  
- **Contract Address**: dirección del contrato de tu colección en OpenSea (opcional).  
- **Collection Slug**: nombre único de la colección en OpenSea (opcional).  
4. Presionar **Cargar desde OpenSea**.  
5. La galería mostrará automáticamente los NFTs disponibles.  

> ⚠️ Nota: Si no se ingresan datos, la galería aparecerá vacía hasta que se carguen tokens.

---

### 3️⃣ Conectar MetaMask

1. Presionar el botón **Conectar Wallet**.  
2. Aceptar la conexión desde la extensión de MetaMask.  
3. El botón mostrará la dirección conectada.  

> Esto permite futuras funcionalidades de interacción blockchain si se quisiera extender el proyecto.

---

## 🔹 Estructura de archivos

lumane-portfolio/
└── index.html # Archivo principal con HTML, JS y Tailwind CSS

> En este modo real conectado a OpenSea, no hace falta subir imágenes locales, ya que se cargan automáticamente desde la API de OpenSea.

---

## 🔹 Créditos

- Proyecto universitario.  
- Fotografía: **Lumane Sagoal**.  
- Desarrollo y diseño: HTML + Tailwind + JS.  

---

## 🔹 Referencias

- [OpenSea Developer Documentation](https://docs.opensea.io/)  
- [MetaMask](https://metamask.io/)  
- [Tailwind CSS](https://tailwindcss.com/)
