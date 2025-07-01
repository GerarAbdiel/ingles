# Translate Blitz Pro

Un juego educativo interactivo para aprender inglés que combina inteligencia artificial, reconocimiento de voz y mecánicas de juego engaging para crear una experiencia de aprendizaje divertida y efectiva.

## 🚀 Características Principales

### 🎯 Juego Educativo Completo
- **3 Niveles de Dificultad**: Easy (15s), Medium (8s), Hard (3s)
- **Dos Fases por Palabra**: Traducción + Pronunciación
- **Selector de Vocabulario**: Juega con 10%, 25%, 50% o 100% del vocabulario
- **Sistema de Puntuación**: Ambas fases deben aprobar (≥60%) para contar como correcta

### 🤖 Integración con IA Avanzada
- **OpenRouter API** con modelo **Meta Llama 3.3 70B Instruct** (gratuito)
- **Validación Inteligente**: Considera sinónimos, variaciones regionales y contexto
- **Feedback Educativo**: Explicaciones detalladas de errores y correcciones
- **Análisis de Pronunciación**: Evaluación fonética y claridad

### 🎤 Reconocimiento de Voz Robusto
- **Web Speech API** para reconocimiento en tiempo real
- **Fallback con MediaRecorder** para compatibilidad total
- **Auto-stop Inteligente**: Detección automática de silencio
- **Manejo de Permisos**: Solicitud clara de acceso al micrófono

### 📊 Estadísticas y Progreso
- **Contadores en Tiempo Real**: Palabras totales, correctas, incorrectas
- **Tabla de Errores Detallada**: Análisis completo al final del juego
- **Feedback Específico**: Diferenciación entre errores de traducción y pronunciación

### 🎨 Interfaz Moderna
- **Diseño Responsivo**: Compatible con móviles y escritorio
- **Gradientes Modernos**: Tema azul-púrpura elegante
- **Animaciones Fluidas**: Transiciones suaves y feedback visual
- **UX Optimizada**: Controles intuitivos y flujo de juego claro

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Build Tool**: Vite
- **IA**: OpenRouter API con Meta Llama 3.3 70B
- **Audio**: Web Speech API, MediaRecorder API
- **Diseño**: CSS Grid, Flexbox, Gradientes Modernos

## 🚀 Instalación y Uso

### Opción 1: Uso Directo (Recomendado)
1. Abre `index.html` directamente en tu navegador
2. El juego es completamente standalone, no requiere instalación

### Opción 2: Desarrollo con Vite
```bash
# Instalar dependencias
npm install

# Ejecutar servidor de desarrollo
npm run dev

# Construir para producción
npm run build
```

## 🔧 Configuración

### 1. Obtener API Key de OpenRouter (Gratuita)
1. Ve a [OpenRouter.ai](https://openrouter.ai/)
2. Regístrate y obtén tu API key gratuita
3. El modelo Meta Llama 3.3 70B Instruct es completamente gratuito

### 2. Configurar en el Juego
1. Abre el juego en tu navegador
2. Introduce tu API key en el campo correspondiente
3. ¡Comienza a jugar y aprender!

### 3. Personalizar Vocabulario
- Edita `public/sample-vocabulary.txt`
- Formato: `palabra_en_ingles:traduccion_en_español`
- Una palabra por línea

## 🎮 Cómo Jugar

### Configuración Inicial
1. **Selecciona Dificultad**: Easy, Medium o Hard
2. **Elige Porcentaje**: Qué porción del vocabulario usar
3. **Configura API Key**: Introduce tu clave de OpenRouter
4. **Carga Vocabulario**: Usa el predeterminado o sube tu archivo

### Durante el Juego
1. **Fase de Traducción**: 
   - Se muestra una palabra en inglés
   - Escribe la traducción en español
   - Presiona "Enviar Traducción"

2. **Fase de Pronunciación**:
   - Escucha la pronunciación correcta
   - Graba tu pronunciación
   - El sistema evalúa automáticamente

### Puntuación
- **Aprobado**: Ambas fases ≥60%
- **Fallido**: Cualquier fase <60%
- **Feedback**: Explicación detallada de cada evaluación

## 📋 Características del Sistema

### Compatibilidad
- ✅ Chrome, Firefox, Safari, Edge
- ✅ Dispositivos móviles y escritorio
- ✅ Sin dependencias externas
- ✅ Funciona offline (excepto IA)

### Seguridad y Privacidad
- 🔒 API key se almacena localmente
- 🔒 No se envían datos personales
- 🔒 Grabaciones de audio son temporales

### Rendimiento
- ⚡ Carga rápida (standalone)
- ⚡ Cache de respuestas de IA
- ⚡ Timeouts y reintentos automáticos
- ⚡ Optimización de llamadas API

## 🎯 Casos de Uso

### Para Estudiantes
- Práctica de vocabulario personalizada
- Mejora de pronunciación con IA
- Seguimiento de progreso detallado
- Aprendizaje gamificado

### Para Profesores
- Herramienta de evaluación interactiva
- Vocabulario personalizable
- Estadísticas detalladas de estudiantes
- Sin necesidad de instalación

### Para Autodidactas
- Práctica independiente 24/7
- Feedback inmediato con IA
- Dificultad ajustable
- Análisis de errores detallado

## 🤝 Contribuir

1. Haz fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 🙏 Agradecimientos

- **OpenRouter** por proporcionar acceso gratuito a modelos de IA avanzados
- **Meta** por el modelo Llama 3.3 70B Instruct
- **MDN Web Docs** por la documentación excepcional de Web APIs
- **Vite** por la herramienta de build ultrarrápida

## 📞 Soporte

Si tienes problemas o preguntas:
1. Revisa la [documentación](README.md)
2. Abre un [issue](../../issues)
3. Consulta los archivos de ejemplo incluidos

---

**¡Disfruta aprendiendo inglés con Translate Blitz Pro!** 🎉
