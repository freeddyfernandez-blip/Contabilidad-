# TaxPY — Guía de Instalación en Teléfono

## ¿Qué es TaxPY?
Aplicación tributaria paraguaya que funciona como una app nativa instalada en tu teléfono.
No requiere App Store ni Play Store — se instala directamente desde el navegador.

---

## INSTALACIÓN EN ANDROID

1. Abrí **Chrome** en tu teléfono Android
2. Navegá al link de la app (ej: https://tu-dominio.com/taxpy/)
3. Chrome mostrará automáticamente un banner "Agregar a pantalla de inicio"
4. También podés tocar el menú (⋮) → "Agregar a pantalla de inicio"
5. Confirmá con "Agregar"
6. ¡Listo! El ícono de TaxPY aparece en tu pantalla como cualquier app

---

## INSTALACIÓN EN iPHONE (iOS)

1. Abrí **Safari** (debe ser Safari, no Chrome)
2. Navegá al link de la app
3. Tocá el botón de compartir (□↑) en la barra inferior
4. Deslizá hacia abajo y tocá "Agregar a pantalla de inicio"
5. Poné el nombre "TaxPY" y tocá "Agregar"
6. El ícono aparece en tu pantalla de inicio

---

## CÓMO HOSPEDAR LA APP (opciones gratuitas)

### Opción A — GitHub Pages (RECOMENDADO, gratis)
1. Crear cuenta en github.com
2. Crear repositorio nuevo (ej: "taxpy-app")
3. Subir todos los archivos de esta carpeta
4. Ir a Settings → Pages → Branch: main → Save
5. Tu app estará en: https://TU-USUARIO.github.io/taxpy-app/

### Opción B — Netlify (gratis, drag & drop)
1. Ir a netlify.com
2. Arrastrar esta carpeta al área de deploy
3. Netlify te da un link automáticamente

### Opción C — Vercel (gratis)
1. Ir a vercel.com
2. Importar desde GitHub o subir archivos

---

## CONFIGURACIÓN INICIAL EN LA APP

1. Abrí TaxPY después de instalar
2. Ve a la pestaña "Perfil" (ícono 👤)
3. Completá:
   - **Razón Social**: tu nombre o empresa
   - **RUC**: tu RUC paraguayo
   - **API Key OpenAI**: para activar el OCR real
     (obtené en: platform.openai.com/api-keys)
4. ¡Listo! Empezá a subir facturas

---

## USO SIN API KEY (Modo Demo)

La app funciona en modo demo sin API key:
- Genera datos de ejemplo al subir fotos
- Todas las funciones tributarias están activas
- Para OCR real, configurar API key de OpenAI

---

## ESTRUCTURA DE ARCHIVOS

```
taxpy-app/
├── index.html      ← La aplicación completa
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service Worker (offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## FUNCIONALIDADES

✅ Dashboard tributario en tiempo real
✅ Cámara / galería para subir facturas  
✅ OCR automático con IA (GPT-4o Vision)
✅ Detección de IVA 10% e IVA 5%
✅ Cálculo automático de crédito fiscal
✅ Arrastre de saldo mes a mes
✅ Historial de liquidaciones mensuales
✅ Exportar datos CSV
✅ Funciona offline (datos en el teléfono)
✅ Instalable como app nativa

---

Paraguay 🇵🇾 — Optimizado para comprobantes SET
