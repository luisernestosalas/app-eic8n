# Documentación Técnica - CRM App

## Información General

**Aplicación:** Sistema CRM para gestión de clientes y notas  
**Stack Tecnológico:** HTML + JavaScript (Vanilla)  
**Repositorio:** https://github.com/luisernestosalas/app-eic8n  
**URL de Producción:** https://app-eic8n-ib2l9eiwv-luisernestosalas-2775s-projects.vercel.app  
**Plataforma de Deploy:** Vercel  

## Arquitectura del Proyecto

### Stack Tecnológico
- **Frontend:** HTML5, CSS3, JavaScript Vanilla
- **Almacenamiento:** LocalStorage (cliente)
- **Deploy:** Vercel
- **Control de Versiones:** Git/GitHub

### Estructura Esperada del Proyecto
```
/
├── index.html          # Página principal
├── styles/
│   └── main.css       # Estilos principales
├── scripts/
│   ├── app.js         # Lógica principal
│   ├── clients.js     # Gestión de clientes
│   └── notes.js       # Gestión de notas
└── assets/            # Recursos estáticos
```

## Funcionalidades Principales

### Gestión de Clientes
- Crear, leer, actualizar y eliminar clientes (CRUD)
- Almacenamiento local de datos de clientes
- Interfaz para listado y búsqueda de clientes

### Gestión de Notas
- Asociación de notas a clientes específicos
-