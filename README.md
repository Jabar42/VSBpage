# Masterclass Gratuita - IA en la Clínica Veterinaria

Una landing page moderna y elegante para el registro de una masterclass gratuita sobre inteligencia artificial en la práctica clínica veterinaria.

## Características

- ✅ Diseño moderno y responsive inspirado en la imagen promocional
- ✅ Formulario de registro para masterclass gratuita sobre IA veterinaria
- ✅ Página de agradecimiento con redirección automática
- ✅ Validación de formulario
- ✅ Diseño con colores turquesa y elementos llamativos
- ✅ Compatible con dispositivos móviles
- ✅ Animaciones suaves y efectos visuales

## Tecnologías Utilizadas

- HTML5
- CSS3 (con gradientes turquesa y animaciones)
- JavaScript vanilla
- Netlify Forms

## Estructura del Proyecto

```
VSBpage/
├── index.html          # Página principal con formulario de registro
├── thank-you.html      # Página de agradecimiento
├── README.md          # Documentación
└── .git/             # Repositorio Git
```

## Configuración para Netlify

El formulario está configurado para funcionar automáticamente con Netlify usando la sintaxis oficial:

- `name="contact"` - Identifica el formulario
- `netlify` - Habilita el procesamiento automático de formularios
- `data-netlify="true"` - Asegura la detección del formulario
- Campo de email con validación HTML5
- Redirección automática a `thank-you.html` después del envío

### Sintaxis utilizada:
```html
<form name="contact" netlify data-netlify="true">
  <input type="email" name="email" required />
  <button type="submit">Registrarme en la Masterclass</button>
</form>
```

## Flujo de Usuario

1. El usuario visita la página principal (`index.html`)
2. Completa el formulario de registro para la masterclass gratuita sobre IA veterinaria
3. Al enviar, es redirigido automáticamente a la página de agradecimiento (`thank-you.html`)
4. La página de agradecimiento muestra confirmación y se auto-redirige al inicio después de 10 segundos

## Detalles del Evento

- **Fecha:** 12 de Agosto
- **Hora:** 7:30 P.M. (Hora Colombia)
- **Plataforma:** Google Meet
- **Ponente:** Nicolás Pedraza - MVZ y experto en marketing
- **Tema:** IA en la Clínica Diaria: Veterinarios Más Eficientes

## Despliegue

1. Sube el código a tu repositorio de GitHub
2. Conecta el repositorio a Netlify
3. El formulario funcionará automáticamente
4. La redirección a la página de agradecimiento funcionará sin configuración adicional

## Personalización

Puedes personalizar fácilmente:
- Colores del gradiente turquesa en el CSS
- Texto del título y descripción
- Mensajes de éxito y error
- Estilos del formulario
- Contenido de la página de agradecimiento
- Tiempo de auto-redirección (actualmente 10 segundos)

## Autor

VSB Team 