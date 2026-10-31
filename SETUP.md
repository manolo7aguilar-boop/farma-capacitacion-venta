# SETUP — base comercial

1. **Firebase propio**: crea un proyecto Firebase NUEVO (no uses el de Farmatodo). Activa Authentication (Email/Contraseña) y Firestore.
2. Copia `.env.example` a `.env` y llena las claves `VITE_FIREBASE_*` del proyecto nuevo.
3. En Firestore → Reglas, pega `firestore.rules` y publica.
4. Agrega el dominio `manolo7aguilar-boop.github.io` en Authentication → Configuración → Dominios autorizados.
5. `npm install && npm run build` y publica `dist/` en la rama `gh-pages`.
6. El primer usuario que se registra queda como administrador del sistema.

Personalizar por farmacia: reemplazar `public/logo.svg`, colores en `src/index.css`, título en `index.html` / `src/App.tsx`.
