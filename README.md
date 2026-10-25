#  Lemon Back-End Developer Capstone Project
================================================

API Paths to Test:
------------------
1. Static HTML Home Page:
   /restaurant/

2. Menu API Endpoints:
   /restaurant/menu/
   /restaurant/menu/<int:pk>
   /api/menu-items/
   /api/menu-items/<int:pk>

3. Table Booking API Endpoints (Requires Authentication Token):
   /restaurant/booking/tables/
   /api/booking/tables/
   /api/bookings/tables/

4. User Registration & Authentication Endpoints (Djoser & DRF Token):
   /auth/users/
   /auth/token/login/
   /auth/token/logout/
   /restaurant/api-token-auth/

Running Unit Tests:
-------------------
python manage.py test
