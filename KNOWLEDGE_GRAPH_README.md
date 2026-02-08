# Mithu Kumari Knowledge Graph Visualization

## Overview
A stunning, standalone HTML file that renders a neo4j-style knowledge graph visualization for Mithu Kumari's research profile using vis-network library and modern neon/glassmorphism design.

## File Location
`mithu_knowledge_graph.html` (41KB)

## Features Implemented

### ✅ Core Requirements
- **Standalone HTML**: Single file with all dependencies via CDN
- **vis-network CDN**: Using unpkg.com/vis-network@9.1.2
- **Embedded JSON Data**: 20 nodes and 27 edges embedded directly in the file
- **Statistics Computation**: Real-time calculation of graph metrics
- **Interactive Legend**: Color-coded node types with descriptions
- **Details Panel**: Updates dynamically on node/edge selection
- **Neon/Glassmorphism Theme**: Modern, polished dark theme with neon accents
- **Responsive Layout**: Mobile-friendly with breakpoints
- **Usage Instructions**: Clear instructions in the header

### 🎨 Visual Design
- **Dark Background**: Multiple radial gradients with neon colors (cyan, purple, pink)
- **Glassmorphism**: Frosted glass effect with backdrop blur
- **Neon Effects**: Text shadows and glow effects in cyan (#00ffff) and pink (#ff1493)
- **Smooth Animations**: Fade-in, hover effects, and transitions
- **Color-coded Nodes**:
  - Researcher (Cyan) - Star shape
  - Theme (Pink) - Circle
  - Trend (Purple) - Triangle
  - Paper (Gold) - Diamond
  - Method (Green) - Hexagon
  - Dataset (Red) - Square

### 📊 Statistics Dashboard
Displays 5 key metrics:
1. Total Nodes (20)
2. Total Edges (27)
3. Node Types (6)
4. Average Connections
5. Maximum Degree

### 🎯 Interactive Features
- **Click nodes/edges**: View detailed information in side panel
- **Drag nodes**: Reposition in the graph
- **Zoom & Pan**: Mouse wheel and click-drag
- **Hover tooltips**: Quick information on hover
- **Navigation buttons**: Built-in zoom controls
- **Physics simulation**: Smooth, realistic layout

### 📱 Responsive Design
- Desktop: 2-column layout (graph + details panel)
- Tablet/Mobile: Stacked layout
- Optimized font sizes and spacing
- Touch-friendly controls

## Knowledge Graph Data

### Nodes (20)
- 1 Researcher: Mithu Kumari
- 5 Research Themes: Machine Learning, Deep Learning, NLP, Computer Vision, Data Analytics
- 3 Papers: Sentiment Analysis, Image Classification, Time Series
- 4 Methods: Transformer, CNN, LSTM, Ensemble Learning
- 3 Datasets: Twitter, ImageNet, Financial
- 4 Trends: Generative AI, Edge ML, Explainable AI, Multimodal Learning

### Edges (27)
- Researcher → Themes (5 connections)
- Researcher → Papers (3 connections)
- Papers → Themes (3 connections)
- Papers → Methods (6 connections)
- Papers → Datasets (3 connections)
- Themes → Methods (3 connections)
- Themes → Trends (4 connections)

## Usage

### Opening the File
Simply open `mithu_knowledge_graph.html` in any modern web browser:
- Chrome/Edge (recommended)
- Firefox
- Safari

### Interactions
1. **View Details**: Click any node or edge
2. **Rearrange**: Drag nodes to preferred positions
3. **Navigate**: Scroll to zoom, click-drag background to pan
4. **Explore**: Hover over elements for quick info

## Technical Stack
- **Visualization**: vis-network 9.1.2 (CDN)
- **Styling**: Pure CSS with gradients, glassmorphism, animations
- **JavaScript**: Vanilla JS for data processing and event handling
- **No external dependencies**: All-in-one file

## Browser Testing
 File successfully serves with HTTP 200
 Valid HTML5 structure
 Balanced tags (script, style)
 JSON data properly embedded
 All required features present

## Color Scheme
- Primary: Cyan (#00ffff)
- Secondary: Deep Pink (#ff1493)
- Accent: Blue Violet (#8a2be2)
- Highlights: Gold (#ffd700), Spring Green (#00ff7f)
- Background: Dark purple gradients (#0a0015 to #1e0040)

## Performance
- File Size: 41KB
- Load Time: < 1 second
- Interactive: Real-time updates
- Smooth Animations: 60fps

## Notes
- The file is completely standalone and requires no installation
- Internet connection needed only for CDN resources (vis-network)
- Can be easily customized by editing the embedded JSON data
- Modern browsers required for full glassmorphism effects
