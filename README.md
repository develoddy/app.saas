# 🚀 App SaaS - Producción

Archivos compilados de **app.lujandev.com**

## 📦 Contenido

Este repositorio contiene únicamente los archivos compilados listos para producción.

## 🌐 Despliegue

Los archivos de este repositorio se despliegan automáticamente en:
- **Producción**: https://app.lujandev.com
- **Servidor**: Digital Ocean (64.226.123.91)
- **Path**: /var/www/app_saas_mean

## 🔄 Pipeline de Deploy

1. Desarrollo en `ECOMMERCE-MEAN/app-saas/`
2. Compilación: `npm run build --configuration=production`
3. Sync a `ECOMMERCE-RECURSOS/PRO-DIST/saas_deploy/`
4. Push a GitHub (este repo)
5. Pull automático en servidor

## 🚨 ¡IMPORTANTE!

**NO editar archivos aquí directamente.** 

Todos los cambios deben hacerse en el repositorio de desarrollo:
- **Repo desarrollo**: https://github.com/develoddy/saas.git

## 📝 Última actualización

Generado automáticamente por el script de deploy.
