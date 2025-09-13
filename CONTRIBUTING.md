# 🤝 Guía de Contribución - EurekaArchiTech

¡Gracias por tu interés en contribuir a EurekaArchiTech! Este documento te guiará a través del proceso de contribución para nuestros proyectos.

## 🌟 Formas de Contribuir

### 💻 Desarrollo de Código
- Corregir bugs reportados
- Implementar nuevas funcionalidades
- Mejorar el rendimiento del código
- Refactoring y mejoras de arquitectura

### 📚 Documentación
- Mejorar documentación existente
- Crear tutoriales y guías
- Traducir contenido
- Actualizar ejemplos de código

### 🧪 Testing y QA
- Reportar bugs
- Escribir y mejorar tests
- Validar funcionalidades
- Mejorar cobertura de tests

### 💡 Ideas y Feedback
- Proponer nuevas funcionalidades
- Compartir casos de uso
- Participar en discusiones
- Revisar Pull Requests

## 🚀 Primeros Pasos

### 1. Configuración Inicial

```bash
# Fork el repositorio en GitHub
# Clonar tu fork
git clone https://github.com/TU_USERNAME/REPO_NAME.git
cd REPO_NAME

# Agregar el repositorio original como upstream
git remote add upstream https://github.com/eureka-architech/REPO_NAME.git

# Instalar dependencias
npm install
# o
yarn install
```

### 2. Configuración del Entorno

```bash
# Copiar archivo de environment
cp .env.example .env.local

# Configurar variables necesarias
# Consultar README.md del proyecto para detalles específicos
```

### 3. Verificar que Todo Funcione

```bash
# Ejecutar tests
npm test

# Ejecutar el proyecto localmente
npm run dev

# Ejecutar linting
npm run lint
```

## 📋 Proceso de Contribución

### 1. Antes de Empezar

- [ ] Revisa los issues existentes para evitar duplicados
- [ ] Comenta en el issue que planeas trabajar
- [ ] Espera confirmación del mantenedor antes de empezar trabajo grande

### 2. Desarrollo

```bash
# Crear una nueva rama para tu feature
git checkout -b feature/nombre-descriptivo

# o para bug fixes
git checkout -b fix/descripcion-del-bug
```

### 3. Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```bash
# Ejemplos de commits válidos
git commit -m "feat: add user authentication system"
git commit -m "fix: resolve navigation bug on mobile"
git commit -m "docs: update installation instructions"
git commit -m "test: add unit tests for utils functions"
git commit -m "refactor: improve code organization"
```

**Tipos de commit:**
- `feat`: Nueva funcionalidad
- `fix`: Correción de bug
- `docs`: Cambios en documentación
- `style`: Cambios de formato (no afectan funcionalidad)
- `refactor`: Refactoring de código
- `test`: Agregar o modificar tests
- `chore`: Tareas de mantenimiento

### 4. Pull Request

1. **Actualizar tu rama:**
```bash
git fetch upstream
git rebase upstream/main
```

2. **Push a tu fork:**
```bash
git push origin feature/nombre-descriptivo
```

3. **Crear Pull Request:**
- Usar el template proporcionado
- Describir claramente los cambios
- Referenciar issues relacionados
- Incluir screenshots si aplica

## 🧪 Estándares de Código

### JavaScript/TypeScript
- Usar ESLint y Prettier (configuración incluida)
- Seguir principios de código limpio
- Escribir código auto-documentado
- Usar TypeScript estricto

### CSS/Styling
- Usar Tailwind CSS para estilos
- Seguir metodología mobile-first
- Optimizar para performance
- Mantener consistencia visual

### Testing
- Escribir tests para nuevas funcionalidades
- Mantener cobertura >80%
- Usar Jest para unit tests
- Incluir integration tests para features complejas

## 📚 Documentación

### README.md
- Mantener actualizada la información de instalación
- Documentar nuevas funcionalidades principales
- Incluir ejemplos de uso

### Comentarios en Código
- Comentar lógica compleja
- Explicar decisiones de diseño no obvias
- Documentar APIs públicas
- Usar JSDoc para funciones públicas

### Documentación Técnica
- Crear documentos para arquitectura compleja
- Mantener diagramas actualizados
- Documentar procesos de deployment

## 🔍 Revisión de Código

### Para Contribuidores
- Auto-revisar antes de hacer PR
- Responder a comentarios constructivamente
- Hacer cambios solicitados promptamente
- Mantener discusiones profesionales

### Para Reviewers
- Ser constructivo y específico
- Explicar el "por qué" en sugerencias
- Reconocer buen código
- Revisar por funcionalidad, no solo estilo

## 🐛 Reporte de Bugs

### Información Requerida
1. **Descripción clara** del problema
2. **Pasos para reproducir** el bug
3. **Comportamiento esperado**
4. **Comportamiento actual**
5. **Información del entorno** (OS, browser, versión)
6. **Screenshots** si aplica

### Template de Bug Report
Usar el template de issues proporcionado en `.github/ISSUE_TEMPLATE/bug_report.md`

## ✨ Solicitud de Features

### Antes de Solicitar
- Verificar que no existe ya
- Considerar si es realmente necesario
- Pensar en implementación general, no específica

### Información a Incluir
1. **Descripción** de la funcionalidad
2. **Justificación** del por qué es útil
3. **Casos de uso** específicos
4. **Posibles alternativas** consideradas
5. **Mockups** o wireframes si aplica

## 🏷️ Sistema de Labels

### Por Tipo
- `bug` - Problemas que necesitan ser arreglados
- `enhancement` - Nuevas funcionalidades
- `documentation` - Relacionado con documentación
- `question` - Preguntas o solicitudes de ayuda

### Por Prioridad
- `priority-critical` - Requiere atención inmediata
- `priority-high` - Alta prioridad
- `priority-medium` - Prioridad media
- `priority-low` - Baja prioridad

### Por Estado
- `needs-triage` - Requiere revisión inicial
- `needs-review` - Necesita revisión de código
- `work-in-progress` - En desarrollo activo
- `ready-for-merge` - Listo para merge

## 📞 Comunicación

### Canales de Comunicación
- **GitHub Issues**: Para reportar bugs y solicitar features
- **GitHub Discussions**: Para preguntas generales y brainstorming
- **Email**: hi@eureka-architech.com para consultas directas
- **LinkedIn**: Para comunicación profesional

### Expectativas de Respuesta
- **Issues críticos**: 24 horas
- **Pull Requests**: 48-72 horas
- **Preguntas generales**: 3-5 días hábiles
- **Feature requests**: 5-7 días hábiles

## 🎯 Reconocimiento

### Contributors
Todos los contribuidores serán reconocidos en:
- README del proyecto
- Releases notes
- Contributors page
- LinkedIn de la empresa (con consentimiento)

### Tipos de Reconocimiento
- **First-time contributors**: Bienvenida especial
- **Regular contributors**: Reconocimiento en releases
- **Major contributors**: Invitación a reuniones de roadmap
- **Core contributors**: Posibles oportunidades de colaboración

## 🔒 Seguridad

### Reporte de Vulnerabilidades
- **NO** crear issues públicos para vulnerabilidades de seguridad
- Enviar email a security@eureka-architech.com
- Incluir información detallada del problema
- Permitir tiempo razonable para la resolución antes de disclosure público

### Mejores Prácticas
- No incluir credenciales en código
- Validar todas las entradas de usuario
- Usar bibliotecas actualizadas
- Seguir principios de least privilege

## 📈 Proceso de Release

### Versionado
Seguimos [Semantic Versioning](https://semver.org/):
- `MAJOR`: Cambios incompatibles de API
- `MINOR`: Funcionalidad nueva compatible
- `PATCH`: Bug fixes compatibles

### Release Process
1. Crear release branch
2. Actualizar version y CHANGELOG
3. Testing exhaustivo
4. Merge a main
5. Tag y release en GitHub
6. Deploy automático

## 🤔 FAQ

### Q: ¿Cómo sé qué issues son buenos para empezar?
**A:** Busca labels como `good-first-issue` o `help-wanted`. Estos son ideales para nuevos contribuidores.

### Q: ¿Puedo trabajar en un issue que ya está asignado?
**A:** Es mejor comentar primero. Si no hay actividad reciente, puedes ofrecer ayuda.

### Q: ¿Qué pasa si mi PR no es aceptado?
**A:** Recibirás feedback específico. Puedes hacer cambios y volver a someter, o discutir alternativas.

### Q: ¿Hay oportunidades de trabajo remunerado?
**A:** Ocasionalmente tenemos proyectos de consultoría. Los mejores contribuidores son considerados primero.

---

## 🙏 Agradecimientos

Gracias por contribuir a EurekaArchiTech. Tu participación nos ayuda a construir mejores soluciones para la transformación digital empresarial.

Para preguntas adicionales, contacta: [hi@eureka-architech.com](mailto:hi@eureka-architech.com)

*Última actualización: Enero 2025*