Rental Car E-Commerce Marketplace Technical Foundation


 ****** MORENT ******

Welcome to the Website!
This project was created as part of the Hackathon Assignment 2 and showcases a fully functional and responsive car rental platform.


****** Technical Documentation ******

____Overview____
The Rental Car E-Commerce Marketplace allows users to search, book, and pay for car rentals. Built with Next.js, Sanity CMS, and third-party APIs, the platform ensures fast performance, dynamic content management, and secure transactions.

=====Technology Stack=====
   
Frontend: Next.js, Tailwind CSS
Backend: Next.js API Routes, Sanity CMS
Database: PostgreSQL (via Prisma ORM)
Third-Party APIs:
Stripe: Payment processing
Shippo: Shipment tracking

_____Key Features_____
User Features:
Search and filter cars by type, location, and price
Real-time booking system with payment integration
Shipment tracking for car deliveries

Admin Features:
Add/update car listings via Sanity CMS
Manage bookings and monitor performance

=====API Endpoints=====

Endpoint	              Method       Description
/api/auth/register    	POST         Register a new user
/api/cars	GET         	Fetch        all available cars
/api/bookings	          POST	       Create a new booking
/api/payments	          POST	       Process a payment

=====Deployment=====

Frontend Hosting: Vercel
CMS Hosting: Sanity Studio
Database: Hosted on Supabase

=====Security=====

HTTPS for secure communication
auth for user authentication
Password hashing using bcrypt
                  This document provides a concise summary of the platform's technical foundation. For further details, refer to the full project documentation.











