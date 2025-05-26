🌟 Features
🔐 Authentication & User Profile
Secure user authentication using Supabase

Signup restricted to in-app only (for internal staff only)

User profile management (change name, password, and avatar)

🏕 Cabin Management
Table view of all cabins with photos, pricing, capacity, and discounts

Create new cabins with image upload

Update and delete existing cabins

📆 Booking Management
Table of bookings with status filter: Unconfirmed, Checked In, Checked Out

View booking details: dates, guests, nights, breakfast, observations

Perform check-in, check-out, or delete bookings

Confirm payment on check-in (manual confirmation)

Option to add breakfast during check-in

🧑 Guest Information
Guest profile includes name, email, national ID, nationality

Display country flags for easy visual ID

📊 Dashboard
Overview of activity over the last 7 / 30 / 90 days

List of today’s check-ins and check-outs with quick action buttons

Booking, check-in, and occupancy statistics

Daily revenue chart (split into room vs extras)

Stay duration analytics chart

⚙️ App Settings
Modify key hotel-wide settings:

Breakfast price

Min/max nights per booking

Max guests per booking

🌙 UX & Visuals
Fully responsive, modern UI built with styled-components

Persistent dark mode toggle

Toast notifications via react-hot-toast

Icons from react-icons for intuitive visuals

🛠 Tech Stack
React

React Router for routing

React Hook Form for form handling

React Query for async state & caching

Context API for global state (e.g., dark mode, user)

Supabase (PostgreSQL + Auth + Storage + Realtime)

Styled Components for scoped component styling

Hot Toast for elegant toast notifications

React Icons for rich iconography

Deployment: Vercel/Netlify (Coming Soon)
