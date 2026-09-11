<p align="center">
  <img src="https://github.com/zerodaty/zerodaty/blob/main/banner.png?raw=true" alt="Banner de Frany Velásquez" />
</p>

<h1 align="center">Frany Velásquez</h1>
<p align="center">
  <b>Odoo Engineer · DevSecOps · Data & Infraestructura</b><br/>
  <i>Construyo, aseguro y opero ERPs que no se pueden caer.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Odoo-14%20%E2%86%92%2019-714B67?style=flat-square&logo=odoo&logoColor=white" alt="Odoo 14-19"/>
  <img src="https://img.shields.io/badge/Focus-ERP%20%2B%20DevSecOps-0A7?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Experiencia-en-Localizaci%C3%B3n-Venezuela%20%C2%B7%20SENIAT-FFCC00?style=flat-square" alt="Localización VE"/>
  <img src="https://img.shields.io/badge/Ubicaci%C3%B3n-Remoto-lightgrey?style=flat-square" alt="Remoto"/>
</p>

---

### Sobre mi

Ingeniero de Sistemas. No solo escribo módulos: **me hago cargo del ciclo completo** — diseño la lógica de negocio, la implemento en Odoo, la despliego con Docker/Nginx, la monitoreo con Grafana y la defiendo con un modelo de acceso *zero-trust*.

Trabajo en paralelo con **varias empresas y varias versiones de Odoo (14 → 19)**, cada una con su propio stack, su propia base de datos y sus propias reglas fiscales. Eso me obligó a ser bueno en tres cosas a la vez: **producto, datos e infraestructura**.

Cuando algo se rompe en producción a las 11 p.m. — una réplica caída, un asiento descuadrado, un proceso extraño comiéndose el CPU del servidor — soy el que entra a ver por qué.

---

### Fortalezas

<table>
<tr>
<td width="50%" valign="top">

#### 🧩 Odoo Engineering
- Módulos custom de punta a punta: contabilidad, inventario, compras, POS, RRHH, ventas y e-commerce.
- **Localización venezolana**: retenciones de IVA / ISLR / municipales, libros y reportes SENIAT, número de control, forma libre e impresión pre-impresa.
- **Multimoneda real** (Bs ↔ divisa): anclaje de tasas, redondeo contable consistente y costeo en moneda extranjera.
- **Sector público**: presupuesto, compromisos, causación y clasificadores ONAPRE con cadenas de aprobación multinivel.
- Frontend Odoo: **OWL**, QWeb, JS y vistas heredadas sin romper el núcleo.

</td>
<td width="50%" valign="top">

#### 🔐 DevSecOps & Zero-Trust
- Hardening de instancias Odoo: servicios atados a **loopback**, acceso solo por **túnel SSH/VPN**, `list_db=False`, sin puertos de base de datos expuestos.
- Gestión de secretos con **vault cifrado (age)** y acceso exclusivo por **llaves SSH** — cero contraseñas en tránsito.
- **Respuesta a incidentes**: he detectado, erradicado y documentado una intrusión real (cryptominer entrando por un Postgres público) y cerrado el vector de origen.
- Endurecimiento de SSH/sshd, firewall, *rate limiting* y segmentación de red por cliente.
- Auditorías de permisos Odoo: ACLs, `ir.rule`, multi-compañía y separación de roles.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🐳 Infraestructura & Operación
- **Docker / Docker Compose** y **Portainer** — modelo *un contenedor por cliente*, aislado y reproducible.
- **Nginx** como reverse proxy: TLS, *headers* de seguridad, WebSocket para longpolling y *tuning* para adjuntos pesados.
- **PostgreSQL avanzado**: replicación en *streaming* con **repmgr**, standby remoto sobre VPN, *replication slots*, backups y restauraciones con `pg_restore`.
- Despliegues repetibles con scripts propios, entornos QA/staging/producción separados y migraciones de versión controladas.

</td>
<td width="50%" valign="top">

#### 📈 Observabilidad & Datos
- Stack **Grafana + Loki** (sobre Portainer) para logs centralizados, dashboards operativos y **alerting** proactivo.
- Tooling propio en CLI para administrar Grafana por contexto/cliente.
- **ETL con Pandas + NumPy**: migraciones de datos complejas, limpieza, transformación y validación antes de cargar.
- Diagnóstico de performance: detección de **N+1**, `_read_group`, operaciones en lote, `@api.depends` mal dimensionados y tormentas de recómputo.
- Visualización y reporting con Power BI / Excel.

</td>
</tr>
</table>

---

### 🧪 Cómo trabajo

- **Pruebas antes que promesas** — suites de cientos de tests unitarios (`TransactionCase`, `HttpCase`), *tours* E2E y Hoot para OWL.
- **Convenciones OCA** — código en inglés, traducciones en `i18n/`, READMEs estructurados, Conventional Commits.
- **Nada de SQL crudo para escribir** — ORM primero; SQL directo solo donde el ORM no rinde.
- **Documentación viva** — cada requerimiento, decisión técnica e incidente queda escrito para quien venga después.

---

### 🛠️ Stack

**Lenguajes & Framework**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/OWL%20%2F%20QWeb-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="OWL / QWeb"/>
  <img src="https://img.shields.io/badge/XML-000000?style=for-the-badge&logo=xml&logoColor=white" alt="XML"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
</p>

**Datos**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
</p>

**Infraestructura, Seguridad & Observabilidad**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white" alt="Portainer"/>
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Loki"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/SSH%20%2F%20Zero%20Trust-000000?style=for-the-badge&logo=openssh&logoColor=white" alt="SSH / Zero Trust"/>
  <img src="https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Conda-44A833?style=for-the-badge&logo=anaconda&logoColor=white" alt="Conda"/>
</p>

---

### 🚀 Trabajo seleccionado

> Buena parte de lo que desarrollo vive en repositorios privados de clientes. Esto es lo público:

<table border="0">
  <tr>
    <td width="50%" valign="top">
      <h4>🔧 Taller Mecánico — extensión de Fleet (Odoo 18)</h4>
      <p>Módulo completo que lleva <code>fleet</code> a un modelo de negocio de servicios automotrices: flujo integrado de presupuesto → orden de servicio → facturación, reportes dinámicos e interfaz adaptada al taller.</p>
      <p><a href="https://github.com/zerodaty/fleet_product_ODOO_v18"><img src="https://img.shields.io/badge/Ver%20repositorio-238636?style=for-the-badge&logo=github&logoColor=white" alt="Ver repositorio"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h4>💬 Integración WhatsApp &amp; API REST</h4>
      <p>Puente entre Odoo y servicios externos vía API REST, con comunicación directa al cliente por WhatsApp para notificaciones y soporte automatizado.</p>
      <p><img src="https://img.shields.io/badge/En%20desarrollo-586069?style=for-the-badge" alt="En desarrollo"/></p>
    </td>
  </tr>
</table>

---

### 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=zerodaty&show_icons=true&hide_border=true&theme=github_dark&hide_title=true" alt="Estadísticas de GitHub"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zerodaty&layout=compact&hide_border=true&theme=github_dark" alt="Lenguajes más usados"/>
</p>

---

### 📫 Hablemos

Estoy abierto a proyectos de **implementación y personalización de Odoo**, **migraciones de datos** y **hardening / operación de infraestructura ERP**.

<p align="center">
  <a href="https://www.linkedin.com/in/franyvelas/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:zerodaty@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
