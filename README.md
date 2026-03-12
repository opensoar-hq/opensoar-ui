# OpenSOAR UI

React frontend for the [OpenSOAR](https://github.com/opensoar-hq/opensoar) SOAR platform.

## Stack

- React 19 + TypeScript
- Vite
- Tailwind CSS v4
- TanStack Query
- framer-motion
- Custom component library

## Development

```bash
npm install
npm run dev
```

The dev server proxies `/api` requests to `http://localhost:8000`.

## Docker

```bash
docker build -t opensoar-ui .
docker run -p 3000:80 opensoar-ui
```

## Part of OpenSOAR

This is the frontend module of the OpenSOAR platform. See the [main repo](https://github.com/opensoar-hq/opensoar) for full documentation.
