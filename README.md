# Flash-Sales-Analysis-System
# Flash Sale System

This project is a Django-based flash sale system that simulates a high-traffic e-commerce environment where users can purchase products in real time. The application demonstrates:

- **Real-Time Purchasing:** Safe and concurrent stock updates using Django transactions and F() expressions.
- **Robust API Endpoints:** Endpoints for listing products, processing purchases, and viewing API test responses.
- **Template Rendering:** A simple homepage rendered with Django templates.
- **Caching (Development):** Integrated local memory caching (with an option to switch to Redis in production).

## Features

- **Homepage:** Accessible at `/` and displays a welcome message.
- **Flash Sale Products:** Placeholder endpoint at `/flash-sale/`.
- **Purchase Endpoint:** Decrements product stock and creates an order at `/purchase/<product_id>/`.
- **API Endpoints:** 
  - API Home: `/api/` returns a welcome JSON message.
  - API Test: `/api/some-api-endpoint/` confirms API functionality.
  - List Products: `/api/products/` returns a JSON list of products.

## Technologies Used

- Django, Python
- SQLite (default for development)
- Local Memory Cache (for development; can switch to Redis)
- Git & GitHub for version control

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/flash-sale-system.git
   cd flash-sale-system
