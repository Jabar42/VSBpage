# VSB Landing Page

Una landing page moderna y elegante para el registro de una masterclass gratuita con formulario compatible con Netlify.

## Características

- ✅ Diseño moderno y responsive
- ✅ Formulario de registro para masterclass gratuita
- ✅ Página de agradecimiento con redirección automática
- ✅ Validación de formulario
- ✅ Mensajes de éxito y error
- ✅ Diseño centrado con gradiente de fondo
- ✅ Compatible con dispositivos móviles
- ✅ Animaciones suaves y efectos visuales

## Tecnologías Utilizadas

- HTML5
- CSS3 (con gradientes y animaciones)
- JavaScript vanilla
- Netlify Forms

## Estructura del Proyecto

```
VSBpage/
├── index.html          # Página principal con formulario
├── thank-you.html      # Página de agradecimiento
├── README.md          # Documentación
└── .git/             # Repositorio Git
```

## Configuración para Netlify

El formulario está configurado para funcionar automáticamente con Netlify usando la sintaxis oficial:

- `name="contact"` - Identifica el formulario
- `netlify` - Habilita el procesamiento automático de formularios
- Campo de email con validación HTML5
- Redirección automática a `thank-you.html` después del envío

### Sintaxis utilizada:
```html
<form name="contact" netlify>
  <input type="email" name="email" required />
  <button type="submit">Suscribirse</button>
</form>
```

## Flujo de Usuario

1. El usuario visita la página principal (`index.html`)
2. Completa el formulario de registro para la masterclass gratuita
3. Al enviar, es redirigido automáticamente a la página de agradecimiento (`thank-you.html`)
4. La página de agradecimiento muestra confirmación y se auto-redirige al inicio después de 10 segundos

## Despliegue

1. Sube el código a tu repositorio de GitHub
2. Conecta el repositorio a Netlify
3. El formulario funcionará automáticamente
4. La redirección a la página de agradecimiento funcionará sin configuración adicional

## Personalización

Puedes personalizar fácilmente:
- Colores del gradiente en el CSS
- Texto del título y descripción
- Mensajes de éxito y error
- Estilos del formulario
- Contenido de la página de agradecimiento
- Tiempo de auto-redirección (actualmente 10 segundos)

## Autor

VSB Team 