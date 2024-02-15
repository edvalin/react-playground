# react-playground

# create vite creact app
`npm create vite@latest`

# Vite config

```
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vitejs.dev/config/
export default defineConfig({
  plugins: [react()],
  base: '/absproxy/8000',
  server: {
      host: true,
      port: 8000,
      strictPort: true
  },
})
```