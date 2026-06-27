# Masala Mehfil

Auto-generated website for Masala Mehfil — Restaurant, solitaire business hub, Balewadi High St, beside Louis Philippe, Baner, Pune, Maharashtra 411045.

## Tech Stack

- **backend**: Spring Boot 3.x + Spring Data JPA + Spring Security
- **hosting**: AWS App Runner (backend) + Vercel (frontend)
- **payment**: Razorpay
- **database**: PostgreSQL
- **frontend**: React 19 + Tailwind CSS + Shadcn/UI

## Features

- Online Table Reservation System
- Direct Online Food Ordering with Payment Gateway (Razorpay)
- Interactive Digital Menu with High-Quality Images and Descriptions
- Mobile-First Responsive Design
- Admin Dashboard for Order and Reservation Management
- Structured Data (Schema.org) for Restaurant Details, Menu, and Reviews

## Running Locally

```bash
docker-compose up --build
```

The app will be available at http://localhost:8080

## Development

**Backend:**
```bash
cd backend && mvn spring-boot:run
```

**Frontend:**
```bash
cd frontend && npm install && npm run dev
```
