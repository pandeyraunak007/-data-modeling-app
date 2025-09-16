# Erwin Cloud DM - Professional Data Modeling Platform

A professional web-based data modeling tool inspired by Erwin Data Modeler, built with modern web technologies for creating, managing, and visualizing database schemas and entity relationships.

![Data Modeler Screenshot](https://via.placeholder.com/800x400/6366f1/ffffff?text=Erwin+Cloud+DM+Interface)

## ✨ Features

### 🎨 **Professional UI Design**
- **Erwin-style ribbon interface** with File, Home, Diagram, View, Tools, Help tabs
- **Optimized layout**: Compact header (7%), primary tabs (4%), ribbon (6%), workspace (83%)
- **Three-column workspace**: Model Explorer, Diagram Canvas, Properties Panel
- **Modern off-white color scheme** with professional gradients

### 🔧 **Advanced Toolbar System**
- **Docked Floating Toolbar**: Vertical, draggable, always-accessible core modeling actions
- **Contextual Mini-Toolbar**: Auto-appears near selections with object-specific actions
- **Four Grouped Sections**:
  - Entities & Relationships (Add Entity, Supertype/Subtype, Identifying/Non-Identifying/Many-to-Many)
  - Visual/Annotation Tools (Annotations, Drawing Objects, Styles)
  - Diagram Navigation (Zoom, Pan, Fit to Screen)
  - Alignment & Layout (Align, Distribute, Group, Auto Layout)

### 🗂️ **Model Management**
- **Model Explorer** with expandable tree structure
- **Diagrams, Entities, Relationships, Keys, Views** organization
- **Professional tree density** for maximum space utilization
- **Kebab menus (⋮)** for create, view properties, delete actions

### 🎯 **Data Modeling Features**
- **Draggable entities** with professional styling
- **ER relationship lines** with cardinality labels (1:N, 1:1, N:M)
- **Key indicators** (Primary Keys, Foreign Keys)
- **Data type display** and management
- **Logical/Physical view toggle**
- **MS Fabric database support**

### ⌨️ **Productivity Features**
- **Keyboard Shortcuts**: Ctrl+E (Add Entity), Ctrl+G (Group), Ctrl+0 (Fit to Screen)
- **Hover tooltips** with shortcut hints
- **Context-sensitive properties panel**
- **Multi-model and multi-diagram tabs**
- **Real-time entity selection and editing**

## 🚀 Quick Start

### Option 1: Local Development
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/data-modeling-app.git
cd data-modeling-app

# Start local server
python -m http.server 3000
# or
npx serve .

# Open browser
open http://localhost:3000
```

### Option 2: Live Demo
Visit the live deployment: **[Coming Soon - Vercel URL]**

## 📁 Project Structure

```
data-modeling-app/
├── index.html          # Dashboard - Landing page with stats and quick actions
├── modeler.html         # Data Modeler - Professional ER diagramming interface
├── users.html           # User Management (Coming Soon)
├── settings.html        # Settings (Coming Soon)
├── package.json         # Project configuration
├── vite.config.js       # Build configuration
└── README.md           # This file
```

## 🎮 How to Use

### 1. **Dashboard**
- View project statistics and recent models
- Quick actions for creating new models
- Access recent models and projects

### 2. **Data Modeler**
- **Add Entities**: Click the docked toolbar or use Ctrl+E
- **Create Relationships**: Select relationship type from toolbar
- **Edit Properties**: Click entities to see contextual toolbar
- **Navigate**: Use zoom, pan, and fit-to-screen tools
- **Organize**: Use Model Explorer to manage diagram structure

### 3. **Professional Workflow**
- Start with logical model design
- Toggle to physical view for database implementation
- Use alignment tools for clean diagram layouts
- Export models for documentation or implementation

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3 (Tailwind), Vanilla JavaScript
- **Icons**: Google Material Symbols
- **Build**: Vite (for production optimization)
- **Deployment**: Vercel (static site hosting)
- **Version Control**: Git + GitHub

## 🎯 Roadmap

### Phase 1: Core Modeling ✅
- [x] Professional UI layout
- [x] Docked and contextual toolbars
- [x] Entity creation and editing
- [x] Basic relationship support
- [x] Model Explorer

### Phase 2: Advanced Features 🚧
- [ ] Database reverse engineering
- [ ] SQL DDL generation
- [ ] Model validation and constraints
- [ ] Import/Export functionality
- [ ] Advanced relationship types

### Phase 3: Collaboration 📋
- [ ] User management system
- [ ] Real-time collaboration
- [ ] Version control for models
- [ ] Team workspaces
- [ ] Advanced security features

## 🤝 Contributing

This is a personal project, but feedback and suggestions are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

MIT License - feel free to use this project for learning and development.

## 🙏 Acknowledgments

- Inspired by **Erwin Data Modeler** professional interface design
- Built with modern web standards for accessibility and performance
- Created as a learning project to demonstrate advanced UI/UX patterns

---

**Built with ❤️ using Claude Code**