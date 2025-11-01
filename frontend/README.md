<h1 align='center'>Redis Link Shortener</h1>
<p align='center'>
  <img src='https://imgur.com/jM3G1i7' alt='redis_link_shortener_gif' width='50%'></img>
</p>
<p  align='center'>
  <a href='https://url-shortener-frontend-6tel.onrender.com/' target="_blank" alt='Enlace App'>Demo</a>
</p><br>


Redis Link Shortener es una app cuya función principal es acortar urls dadas por el usuario.

## Tecnologías
- Vite
- React
- SCSS
- Redis

## Características
- Componente para acortar URLs.
- Componente para mostrar las URLs acortadas.
- Componente barra de navegación.
- Componente de página no encontrada (404).

## Instalación local
Clona el repositorio:
```bash
git clone https://github.com/Gdr18/redis-link-shortener.git
cd redis-link-shortener
```
Instala las dependencias:
```bash
npm install
```
Configura las variables de entorno creando un archivo `.env` en la raíz del proyecto con las siguientes variables:
```
VITE_BACKEND_URL=https://tu_servidor_backend.dev
```

## Comandos disponibles
Para iniciar el servidor de desarrollo:
```bash
npm run dev
```

Para hacer el build de producción:
```bash
npm run build
```
para previsualizar el build de producción:
```bash
npm run preview
```

