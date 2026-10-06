# Taller 2 - Fundamentos de CSS

## Datos del Proyecto
- **Asignatura:** Fundamentos WEB (Grupo 4303D)
- **Programa:** Ingeniería en Sistemas
- **Institución:** UNICAMACHO
- **Profesor:** Ronal Andres Tamayo
- **Desarrollador:** Brayan José Rodríguez Landázuri
- **Proyecto:** Avance Formativo I (Simulación de Desarrollo Autónomo)

## Convención CSS
- **Idioma de clases:** Inglés técnico para escalabilidad internacional.
- **Formato:** kebab-case (letras minúsculas unidas por guiones).
- **Metodología:** Inspirado en BEM para la separación semántica de componentes (`.site-header__title`).

## Paleta de color y Justificación
- **Primary (--color-primary):** `#17365d` (Azul profundo corporativo).
- **Secondary (--color-secondary):** `#2f75b5` (Azul medio complementario).
- **Background (--color-bg):** `#f7f9fc` (Gris azulado neutro de descanso visual).
- **Text (--color-text):** `#1f2937` (Gris carbón oscuro de alto contraste).

**Justificación:** Al trabajar el **Tema 1: Inteligencia artificial y automatización**, seleccioné tonos azules y neutros fríos porque representan un entorno tecnológico, analítico e industrial moderno. El contraste de color del texto principal frente al fondo blanco de las tarjetas supera el umbral de accesibilidad **WCAG 2.2 AA (relación superior a 4.5:1)**, garantizando que el sitio sea legible para personas con debilidad visual.

## Prueba de cascada (Experimento Obligatorio)
- **Resultado del selector de elemento (`h2`):** El texto adquiere color **azul** inicial.
- **Resultado de la clase (`.demo-title`):** El color cambia a **verde** debido a que los selectores de clase poseen mayor especificidad matemática que los selectores de elemento genéricos.
- **Resultado del ID (`#demo-title`):** El color se transforma a **morado / azul primario** porque un selector por ID supera en prioridad jerárquica a las clases y elementos en el algoritmo de cascada.
- **Resultado del estilo inline (`style=""`):** Prevalece el color **naranja** ya que la declaración en línea se incrusta directo en el nodo del DOM, rompiendo los estilos generales del autor.
- **Explicación:** La cascada es el algoritmo que resuelve conflictos de herencia y especificidad. Gana la regla con mayor peso en el árbol de origen; a igual especificidad, prevalece el orden de aparición secuencial posterior.
