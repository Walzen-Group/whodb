# WhoDB

### *"Making your database management disappear like magic!"*

## Description
Welcome to **WhoDB** – a powerful and user-friendly database management tool that combines the simplicity of Adminer with superior UX and performance. WhoDB is written in GoLang for optimal speed and efficiency and features interactive graphs for visualizing your entire database schema. Whether you're managing a small project or a complex enterprise system, WhoDB is designed to make your database administration tasks smoother and more intuitive.

## Features
- **Better UX:** Intuitive and easy-to-use interface.
- **Faster Performance:** Built with GoLang for exceptional speed.
- **Schema Visualization:** Interactive graphs to visualize your entire database schema.
- **Current Support:** PostgreSQL

## Quick Start

To start using WhoDB right away, you can run it using Docker:

```sh
docker run -p 8080:8080 clidey/whodb
```

Go to http://localhost:8080 and get started!

## Development Setup

If you want to run and develop WhoDB locally, follow these steps:

### Prerequisites
- GoLang (latest version recommended)
- PNPM (latest version recommended)

## Backend Setup

Navigate to the core/ directory and run the GoLang application:

```sh
cd core/
go run .
```

## Frontend Setup

Navigate to the frontend/ directory and run the React frontend:

```sh
cd frontend/
pnpm i && pnpm start
```

## Contributing

We welcome contributions from the community! Feel free to open issues or submit pull requests to help improve WhoDB.


## Contact

For any inquiries or support, please reach out to [support@clidey.com](mailto:support@clidey.com).

<div style="width:100%;border-bottom:0.5px solid white;margin:50px 0px;"></div>

*WhoDB - Making your database management disappear like magic!*