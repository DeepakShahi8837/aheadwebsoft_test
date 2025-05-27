# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

✅ Search is implemented on the frontend only by filtering the fetched data in the browser.

❌ City tabs (e.g., Dubai, Abu Dhabi) are static and do not reflect accurate results from the backend.

⚠️ Latitude and longitude values in the API are inconsistent or inaccurate, so location-based filtering is not reliable.


The API lacks query parameters for filtering by city, type, or location so i implement using frontend filter method.

City tab filtering is static — not dynamically backed by the API.

Lat/long values in the response are not sufficient to implement accurate geolocation-based filters.

Search is frontend-only, applied on the full dataset retrieved from the backend.
