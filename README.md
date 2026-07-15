#  Coffee Tulips 

E-commerce de café de especialidad desarrollado con **Next.js** (frontend) y **Express + PostgreSQL + Prisma** (backend), con integración de pagos a través de **Mercado Pago**.

## Sobre el proyecto

Coffee Tulips  es una tienda en línea para la venta de café de especialidad, molido, bebidas preparadas y accesorios. Permite a los clientes explorar el catálogo, armar su pedido, elegir entre recojo en tienda o delivery, y pagar de forma segura con Mercado Pago. Incluye además un panel de administración para gestionar productos, categorías y pedidos.

## Características

-  Catálogo de productos con filtros por categoría y tipo
-  Carrito de compras y checkout completo
-  Seguimiento de pedidos con estados (pendiente, pagado, en preparación, listo, entregado)
-  Pago en línea integrado con Mercado Pago (Checkout Pro)
-  Autenticación de usuarios con roles (cliente, dueño, administrador)
-  Panel de administración para gestionar productos, categorías y pedidos
-  Gestión de direcciones de entrega

## Stack tecnológico

**Frontend:**
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Zustand

**Backend:**
- Node.js + Express
- PostgreSQL + Prisma ORM
- JWT para autenticación
- Mercado Pago SDK

## Cómo correr el proyecto

### Backend

```bash
cd app/backend
npm install
npx prisma migrate dev
npm run db:seed
npm run dev
```

### Frontend

```bash
cd app/frontend
npm install
npm run dev
```

El backend corre en `http://localhost:3000` y el frontend en `http://localhost:3001`.


