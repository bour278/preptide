# Interview Prep Notes

A comprehensive collection of interview preparation materials for quantitative trading, software engineering, and data science roles. Built with Next.js and Fumadocs for fast, searchable documentation.

## Overview



https://github.com/user-attachments/assets/c332c994-13bc-4544-b8b0-d4a8febca36f



## Contents

### Trading Prep
Mathematical foundations for quantitative trading interviews:
- Probability Theory and Random Variables
- Conditional Probability and Bayes' Theorem
- Expected Values and Moments
- Combinatorics
- Limit Theorems and Concentration Inequalities
- Stochastic Calculus Fundamentals

### Software Engineering Prep
Core computer science concepts with Python implementations:
- Divide and Conquer (Master Theorem, Strassen's Algorithm)
- Dynamic Programming (Knapsack, LCS, Edit Distance)
- Graph Algorithms (BFS, DFS, Dijkstra, Kruskal, Tarjan)
- FFT and Numerical Algorithms
- Data Structures (15+ implementations)
- Sorting Algorithms (Comparison and Non-comparison based)
- Pattern Matching (KMP, Rabin-Karp, Z-Algorithm)
- Programming Techniques (Sliding Window, Two Pointers, Backtracking)
- Networking Basics
- Software Design (OOP, SOLID, Design Patterns)

### Data Science Prep
Machine learning and statistics with mathematical rigor:
- Statistics and Probability (MLE, MAP, Information Theory, Hypothesis Testing)
- Optimization (Gradient Descent variants, ADMM, Convex Optimization)
- Linear Models (OLS, Ridge, Lasso, Bayesian Linear Regression)
- Machine Learning Algorithms (K-Means, PCA, SVM, Random Forest, XGBoost)
- Neural Networks (Backpropagation, CNNs, RNNs, Transformers)

## Installation

### Prerequisites
- Node.js 18.x or higher
- npm or pnpm package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/interview-prep-notes.git
cd interview-prep-notes
```

2. Navigate to the documentation directory:
```bash
cd interview-prep
```

3. Install dependencies:
```bash
npm install
```

Or if using pnpm:
```bash
pnpm install
```

## Usage

### Development Server

Start the development server with hot-reload:

```bash
npm run dev
```

Or with pnpm:
```bash
pnpm dev
```

The documentation will be available at `http://localhost:3000`.

### Build for Production

Create an optimized production build:

```bash
npm run build
npm start
```

Or with pnpm:
```bash
pnpm build
pnpm start
```

## Dependencies

### Core
- **Next.js 16.0.1** - React framework with Turbopack for fast builds
- **React 19** - UI library
- **Fumadocs** - Documentation framework with built-in search

### Documentation
- **Fumadocs MDX** - MDX processing for documentation
- **Fumadocs UI** - Pre-built UI components for documentation
- **Fumadocs Core** - Core documentation utilities

### Styling
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible UI primitives

### Mathematics
- **KaTeX** - Fast math typesetting for LaTeX equations
- **Rehype** - HTML processing for mathematical notation

## Project Structure

```
interview-prep/
├── content/
│   └── docs/
│       ├── trading-prep/      # Quantitative trading materials
│       ├── swe-prep/          # Software engineering materials
│       └── data-science/      # Data science materials
├── app/                       # Next.js application
├── components/                # React components
└── public/                    # Static assets
```

## Features

- Full-text search across all documentation
- LaTeX equation rendering with KaTeX
- Syntax highlighting for code snippets
- Responsive design for mobile and desktop
- Dark mode support
- Fast page navigation with Turbopack

## Contributing

Feel free to open issues or submit pull requests for improvements, corrections, or additional topics.

