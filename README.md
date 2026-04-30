# 📊 CS Team Tracker

**Internal POC - Customer Support Team Activity Tracker**

---

## 🎯 Overview

Sistema completo de tracking de actividades semanales para el equipo de Customer Support. Incluye:
- **Página Principal**: Landing page profesional con acceso rápido
- **Web Interface**: Dashboard interactivo conectado a Excel
- **Excel**: Base de datos con hojas para planificación y seguimiento
- **100% GitHub**: Todo alojado en GitHub, sin servidores externos

---

## 🚀 Quick Start

### Para Coordinadores

1. **Abre la página principal:**
   ```
   https://tu-username.github.io/cs-team-tracker/
   ```

2. **Accede al Dashboard:**
   - Click en "Open Dashboard"
   - Click en "Refresh Data"
   - Ve los datos en tiempo real

3. **Actualiza tareas:**
   - Click en "Download File"
   - Edita Excel localmente
   - Sube archivo a GitHub
   - Click Refresh en dashboard

### Para Agentes (Elías, Gabriela, Jacqueline)

1. **Descarga Excel:**
   - Desde la página principal
   - O directamente del repositorio GitHub

2. **Registra tu actividad diaria:**
   - Abre tu hoja personal
   - Llena: fecha, tarea, tipo, horas, estado

3. **Sube cambios:**
   - Guarda Excel
   - Sube a GitHub
   - Coordinador verá actualización

---

## 📋 Structure

### Archivos en GitHub

```
cs-team-tracker/
├── index.html                           (Página principal)
├── CS_Team_Tracker_Connected.html       (Dashboard web)
├── CS_Team_Weekly_Tracker.xlsx          (Base de datos Excel)
├── README.md                            (Esta documentación)
└── .gitignore                           (Configuración Git)
```

### Excel Sheets

- **Weekly Plan**: Coordinador planifica todas las tareas
- **Elías Zapata**: Actividad diaria de Elías
- **Gabriela Cader**: Actividad diaria de Gabriela
- **Jacqueline Estrada**: Actividad diaria de Jacqueline
- **Dashboard**: Métricas automáticas (formulas)
- **Instructions**: Guía de uso

---

## 🎨 Features

### Web Interface
✅ **Kanban Board** - Tareas organizadas por día (Lun-Vie)
✅ **Real-time Dashboard** - Métricas automáticas
✅ **Team Progress** - Estadísticas por agente
✅ **Refresh Button** - Actualiza datos con 1 click
✅ **Responsive Design** - Funciona en móvil, tablet, PC

### Excel
✅ **Dropdowns** - Validación de datos consistente
✅ **Auto Metrics** - Fórmulas para cálculos automáticos
✅ **Multiple Sheets** - Hojas separadas por agente
✅ **Instructions** - Guía integrada

---

## 🔄 How It Works

```
1. Editas Excel en GitHub
         ↓
2. Click "Refresh Data" en el dashboard
         ↓
3. HTML lee Excel desde GitHub (XLSX.js)
         ↓
4. Procesa y renderiza datos
         ↓
5. Dashboard se actualiza automáticamente
```

---

## 📊 Weekly Workflow

### Friday EOD (Coordinator - 15 min)
1. Open Excel in GitHub
2. Fill "Weekly Plan" sheet with all tasks for next week
3. Save and commit changes

### Monday-Friday (Agents - 2 min/day)
1. Open Excel (download or online)
2. Fill your personal sheet with daily activity
3. Save and upload changes to GitHub

### Daily (Coordinator - 1 min)
1. Open web dashboard
2. Click "Refresh Data"
3. Monitor progress in real-time

### Thursday 5 PM (Coordinator - 10 min)
1. Screenshot dashboard metrics
2. Create weekly report
3. Share with team in Teams

---

## 💻 Technical Details

### Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Data**: XLSX.js library for Excel reading
- **Hosting**: GitHub Pages (free)
- **Database**: Excel file in GitHub
- **Version Control**: Git/GitHub

### Data Flow
```
GitHub Repository
    ├── Excel file
    └── HTML file
        ↓
    GitHub Pages
        ↓
    Browser downloads Excel
        ↓
    XLSX.js processes data
        ↓
    JavaScript renders dashboard
        ↓
    User sees real-time dashboard
```

---

## 🔐 Security & Privacy

- **Excel**: GitHub repository (private or public, your choice)
- **Web Interface**: GitHub Pages (no server, no logs)
- **Data**: Never leaves GitHub
- **Backup**: GitHub handles automatic versioning
- **Access Control**: GitHub permissions apply

---

## 📱 Browser Support

✅ Chrome/Chromium
✅ Microsoft Edge
✅ Firefox
✅ Safari

---

## 🎯 Task Types

- Ticket Support
- Meetings
- Incidents
- Migration
- Academy
- QA
- Product
- FAQ
- Demos
- Team Support

---

## 📈 Metrics Tracked

- Total tasks planned
- Tasks completed
- Tasks in progress
- Completion rate (%)
- Total hours planned
- Hours logged
- Priority breakdown (High/Medium/Low)
- Tasks by agent
- Completion rate by agent

---

## 🔄 Update Frequency

- **Weekly Plan**: Updated Friday EOD
- **Agent Activity**: Updated daily (Mon-Fri)
- **Dashboard**: Real-time (click refresh)
- **Excel**: Whenever needed

---

## ⚙️ How to Update

### Option 1: Edit Locally
```
1. Download Excel from GitHub
2. Edit in Excel application
3. Save changes
4. Upload updated file to GitHub
5. Click "Refresh Data" in dashboard
```

### Option 2: Edit in GitHub
```
1. Open CS_Team_Weekly_Tracker.xlsx in GitHub
2. Click edit button
3. Make changes online
4. Commit
5. Click "Refresh Data" in dashboard
```

---

## 📞 Support

For issues:
1. Check the "Instructions" sheet in Excel
2. Review this README
3. Check GitHub issues/discussions

---

## 🎉 Status

✅ **Version 1.0**
✅ **Production Ready**
✅ **All Features Working**
✅ **100% GitHub Hosted**

---

## 📝 Version History

- **v1.0** (April 30, 2026) - Initial release
  - Landing page
  - Web dashboard
  - Excel integration
  - Real-time sync

---

**Last Updated**: April 30, 2026
**Status**: Production Ready ✅
**Hosted on**: GitHub Pages
