# 🇨🇱 Guía Rápida: Conectar Tema a GitHub y Shopify

Este tema está basado en **Shopify Dawn (Online Store 2.0)** e incluye módulos nativos optimizados para **dropshipping local en Chile** (sin pagar aplicaciones mensuales extras).

---

## 🚀 Paso 1: Subir este tema a tu cuenta de GitHub

1. Entra a [github.com/new](https://github.com/new) y crea un nuevo repositorio:
   - **Repository name**: `tienda-dropshipping-chile` (o el nombre que prefieras).
   - Puedes dejarlo **Público** o **Privado**.
   - **NO** marques las casillas de "Add a README file" ni ".gitignore" (ya vienen incluidos).
   - Haz clic en **Create repository**.

2. En tu terminal (PowerShell o Git Bash), dentro de esta carpeta (`shopify-chile-dropshipping`), ejecuta:
   ```bash
   git add .
   git commit -m "feat: optimizaciones de alta conversion para dropshipping Chile"
   git remote set-url origin https://github.com/TU_USUARIO/tienda-dropshipping-chile.git
   git push -u origin main
   ```
   *(Reemplaza `TU_USUARIO` y `tienda-dropshipping-chile` por tus datos).*

---

## 🛍️ Paso 2: Conectar el repositorio en tu Administrador de Shopify

1. En tu panel de Shopify, ve a **Tienda online > Temas**.
2. En la sección **Biblioteca de temas**, haz clic en el botón **Agregar tema** y selecciona **Conectar desde GitHub**.
3. Si es la primera vez, haz clic en **Iniciar sesión en GitHub** y autoriza a Shopify para acceder a tu cuenta.
4. Selecciona tu repositorio recién creado (`tienda-dropshipping-chile`) y la rama **main**.
5. Haz clic en **Conectar tema**.
6. Shopify comenzará a sincronizar el tema de inmediato. Cuando termine, haz clic en **Publicar** (o en **Personalizar** para editarlo primero).

---

## 🛠️ Paso 3: Cómo editar y personalizar los módulos de Chile

Todos los módulos son **100% editables desde el editor visual de Shopify**:

1. En Shopify, haz clic en **Personalizar** (Theme Customizer).
2. Ve a cualquier **Página de producto**:
   - En la columna izquierda verás los bloques listos:
     - 🇨🇱 **Medios de Pago Chile**: Muestra Webpay Plus, Redcompra, Mercado Pago, CuentaRUT BancoEstado y MACH.
     - 🚚 **Despacho Chile (Starken/Blue)**: Badges oficiales de Blue Express, Starken y Chilexpress con texto de entrega en 24-48 hrs.
     - 📅 **Estimador de Entrega Chile**: Calcula automáticamente fechas hábiles de entrega (ej: *"Pide hoy y recibe entre el jueves 17 y lunes 21 en Santiago y Regiones"*).
     - ⚡ **Temporizador de Urgencia**: Cuenta regresiva y barra de stock restante en bodega Santiago.
   - Puedes arrastrar estos bloques arriba o abajo, cambiarles los textos o desactivarlos cuando quieras.

3. **Botón Flotante de WhatsApp**:
   - En la columna izquierda, en las secciones globales, haz clic en **WhatsApp Chile**.
   - Ingresa tu número telefónico (ej: `56912345678`).
   - Personaliza el mensaje de saludo y la posición (izquierda o derecha).

4. **Barra Flotante de Compra (Sticky Add to Cart)**:
   - Haz clic en la sección **Sticky Add to Cart**.
   - Elige el color del botón (ej. verde `#16a34a` o el color de tu marca) y el texto (ej: *"COMPRAR AHORA"*).

---

## 🔄 ¿Cómo funciona la sincronización automática?

- **Si editas el diseño en Shopify**: Cada vez que cambias un color, texto o mueves un bloque en el personalizador visual, Shopify hace un **commit automático** en tu repositorio de GitHub.
- **Si editas código en tu PC**: Cualquier cambio que hagas localmente y subas con `git push origin main` se actualizará de inmediato en tu tienda Shopify en vivo.
