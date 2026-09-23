# 🏭 Control SorboConEstilo

**Sistema Integral de Gestión de Producción, Ventas e Inventario*

Un software de escritorio diseñado para administrar el flujo de trabajo completo de un taller de impresión y personalización. Optimiza la comunicación entre las áreas de ventas, piso de producción y finanzas mediante herramientas visuales, generación de reportes nativos y bases de datos locales rápidas.


## 🚀 Características Principales (Módulos)

### 📊 Dashboard General
- Panel de control principal con métricas (KPIs) de la semana en curso.
- Conteo en tiempo real de pedidos pendientes, terminados y entregados.
- Lista interactiva de los trabajos programados para los próximos días.

### 📝 Ventas y Recepción de Pedidos
- Formulario de entrada rápido con autocompletado de clientes y categorías de producto (PET, Cartón, Contenedores, etc.).
- Selector visual de colores de tinta (Hexadecimal) integrado para facilitar el trabajo del taller.
- Integración con calendario interactivo (Syncfusion) que reacciona a clics para consultar y editar pedidos sobre la marcha.

### ⚙️ Agenda y Control de Producción
- Visualización de carga de trabajo mediante calendario mensual con sistema de colores semafórico:
  - 🩶 **Gris:** Programado / En espera.
  - 🟩 **Verde:** Terminado en taller (esperando recolección).
  - 🟦 **Azul:** Entregado al cliente.
- Generación y descarga directa de **Reportes PDF agrupados por día** para imprimir y entregar al jefe de taller.

### 💰 Finanzas y Cuentas por Cobrar (CxC)
- Interfaz *Maestro-Detalle* para visualizar la deuda global por cliente y el desglose individual de cada pedido adeudado.
- Sistema de cobro para registrar abonos parciales o liquidaciones totales.
- Generación de reportes semanales membretados en PDF (con QuestPDF), listos para auditorías de ingresos.

---

## 💻 Tecnologías Utilizadas

El sistema fue construido con una arquitectura sólida y moderna para aplicaciones de escritorio:

- **Lenguaje:** C# (.NET)
- **Interfaz Gráfica:** WPF (Windows Presentation Foundation)
- **Base de Datos:** SQLite (Embebida y ligera)
- **ORM:** Dapper (Consultas de alto rendimiento)
- **Reportes:** QuestPDF (Generación fluida de documentos y tablas complejas)
- **Componentes Extra:** Syncfusion (SfScheduler para la agenda interactiva)

---

## 📥 Instrucciones de Instalación

1. Ve a la pestaña de **[Releases](../../releases)** a la derecha de este repositorio.
2. Descarga la versión más reciente: `Instalador_Control_SorboConEstilo_v1.2.exe`.
3. Ejecuta el archivo descargado. 
   * **Aviso de seguridad (SmartScreen):** Al ser un software desarrollado de forma independiente (sin firma de certificado de pago), Windows puede mostrar una pantalla azul de advertencia. Solo debes hacer clic en **"Más información"** y luego en **"Ejecutar de todas formas"**.
4. Sigue las instrucciones del asistente. El instalador creará los accesos directos, desplegará la base de datos virgen y configurará automáticamente la exclusión de carpetas en Windows Defender para asegurar su rendimiento.

---



**Desarrollado por:** Marcos Daniel García Rodríguez

**MDR SOLUTIONS - TODOS LOS DERECHOS RESERVADOS 2026**
