# Mesh Platform - 3D Scene Editor

A web application built with React Three Fiber that allows users to create and manage 3D scenes. Key features include dynamic model loading, interactive object transformation, and scene serialization to and from JSON format.

## Features

-   **Model Library:** Upload `.glb` models to a reusable library panel.
-   **Interactive Transformation:** Select objects in the scene to translate, rotate, and scale them with interactive gizmos.
-   **Scene Persistence:** Save the entire scene state (including library assets and object transformations) to a `.json` file and load it back into the editor.
-   **Dynamic Environments:** Change the scene's lighting and reflections by selecting from multiple HDRI environment presets.
-   **Properties Inspector:** View detailed data for any selected object and perform actions like deletion.

## Technology Stack

-   React
-   React Three Fiber / Drei
-   Zustand (State Management)
-   Leva (GUI Controls)
-   Three.js

## Local Development

To run this project on your local machine, follow these steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/koliangyu99/mesh_platform.git](https://github.com/koliangyu99/mesh_platform.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd mesh_platform
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the development server:**
    ```bash
    npm run dev
    ```
The application will be available at `http://localhost:5173` or another port specified in your terminal.



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
