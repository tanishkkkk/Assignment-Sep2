# Sentisum Platform Redesign

A modern React TypeScript application showcasing a reimagined customer feedback analytics platform with advanced UI/UX principles.

## Overview

This project demonstrates a complete redesign of the Sentisum customer feedback analytics platform, featuring:

- **Modern Dashboard**: Clean, intuitive interface with real-time insights
- **Advanced Analytics**: Interactive charts and visualizations using Recharts
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Accessibility**: WCAG-compliant components using Headless UI
- **Performance**: Optimized with Vite and React 18

## Features

### 🎯 Dashboard Components

- **Overview Cards**: Key metrics with trend indicators
- **Sentiment Analysis**: Interactive pie charts showing sentiment distribution
- **Topic Analysis**: Bar charts displaying feedback topics
- **Trend Visualization**: Line charts tracking sentiment over time
- **Feedback Table**: Detailed feedback entries with filtering and sorting

### 🎨 Design System

- **Color Palette**: Professional blue primary with neutral grays
- **Typography**: Inter font family for clarity and readability
- **Shadows**: Soft shadows with glow effects for depth
- **Spacing**: Consistent 8px grid system
- **Icons**: Lucide React icons for consistency

### 🛠️ Technical Stack

- **React 18** with TypeScript for type safety
- **Vite** for fast development and building
- **Tailwind CSS** for utility-first styling
- **Recharts** for data visualization
- **Lucide React** for beautiful icons
- **Headless UI** for accessible components

## Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## Project Structure

```
src/
├── components/
│   ├── Dashboard.tsx       # Main dashboard layout
│   ├── Header.tsx         # Navigation header
│   ├── Sidebar.tsx        # Navigation sidebar
│   ├── OverviewCards.tsx  # Metrics overview
│   ├── FeedbackTable.tsx  # Feedback data table
│   └── charts/
│       ├── SentimentChart.tsx  # Sentiment pie chart
│       ├── TopicsChart.tsx     # Topics bar chart
│       └── TrendChart.tsx      # Trend line chart
├── App.tsx                # Root component
└── main.tsx              # Application entry point
```

## Design Improvements

This redesign focuses on creating a "wow" factor through:

1. **Visual Hierarchy**: Clear information architecture with proper spacing
2. **Interactive Elements**: Smooth transitions and hover effects
3. **Data Clarity**: Enhanced chart readability with better colors and tooltips
4. **Modern Aesthetics**: Clean design with subtle shadows and rounded corners
5. **Responsive Layout**: Seamless experience across all device sizes

## Development

The project uses modern development practices:

- **TypeScript**: Full type safety and better developer experience
- **ESLint**: Code quality and consistency
- **Tailwind CSS**: Rapid UI development with utility classes
- **Component Architecture**: Reusable, maintainable components
  ],
  languageOptions: {
  parserOptions: {
  project: ['./tsconfig.node.json', './tsconfig.app.json'],
  tsconfigRootDir: import.meta.dirname,
  },
  // other options...
  },
  },
  ])

````

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
````
# Assignment-Sep2
