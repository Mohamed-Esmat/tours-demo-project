# Tours Demo Project

![Tours Demo](https://res.cloudinary.com/tawfeer/image/upload/v1689939886/Tours-projectpng_w7maqu.png)

> A simple frontend demo project built using Vite, showcasing how to create React components, manage state with hooks, fetch data from an API, and more.

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Figma Design](#figma-design)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

This project is a simple demonstration of building a frontend application using React and Vite. It includes components such as Tours, Tour, and Loading, allowing users to browse through a list of tours, read more about each tour, remove tours, and re-fetch the tour data.

## Demo

You can check out the live demo of the project [here](https://tours-demo-esmat.netlify.app/).

![Tours Demo](https://res.cloudinary.com/tawfeer/image/upload/v1689939886/Tours-projectpng_w7maqu.png)

## Features

- Fetches tour data from an API using `fetch` API.
- Implements loading state with a spinner using the Loading component.
- Renders a list of tours using the Tours component.
- Allows users to remove tours from the list.
- Implements a "read more" functionality for each tour to expand the description.
- Provides a "re-fetch" functionality to update the tour data.

## Installation

1. Clone the repository:

```
git clone https://github.com/Mohamed-Esmat/tours-demo-project.git
cd tours-demo
```

2. Install dependencies:

```
npm install
```

## Usage

1. Start the development server:

```
npm run dev
```

2. Open your web browser and go to `http://localhost:3000` to see the application.

## Technologies Used

- React
- Vite

## Figma Design

The design for this project can be found on Figma. You can view it [here](https://www.figma.com/file/OnLoM3AzBFaHzSc2iolJS0/Tours?node-id=0%3A1&t=wiRXOlTLN5ehekYI-1).

## Project Structure

```
|-- src
|   |-- App.jsx
|   |-- components
|   |   |-- Tours.jsx
|   |   |-- Tour.jsx
|   |   |-- Loading.jsx
|-- index.html
|-- README.md
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request or open an issue. Let's make this project even better together!
