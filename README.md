# Camp & Travel Surabaya

Sistem Pelayanan Terpadu untuk layanan travel dan camping di Surabaya.

## Features

- 🏠 Landing page dengan hero section
- 👥 Multi-role dashboard (Admin, Guide, Customer)
- 📝 Form management untuk biodata dan booking
- 📊 Data management untuk guides, customers, dan trips
- 📅 Schedule management untuk guides
- 📱 Responsive design dengan Tailwind CSS

## Tech Stack

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- Font Awesome Icons

## Project Structure

```
/
├── Assets/                 # Main application files
│   ├── Assets/            # Images and static assets
│   ├── *.html            # HTML pages
│   └── tailwind.config.js
├── index.html             # Entry point
├── package.json
├── vercel.json           # Vercel configuration
└── README.md
```

## Pages

### Main Pages
- `home.html` - Landing page
- `login.html` - Login page
- `register_selection.html` - Registration type selection
- `register_form.html` - Registration form

### Dashboard Pages
- `dashboard_admin.html` - Admin dashboard
- `dashboard_guide.html` - Guide dashboard
- `dashboard_customer.html` - Customer dashboard

### Management Pages
- `data_guide_form.html` - Guide data form
- `data_guide_table.html` - Guide data table
- `biodata_guide.html` - Guide biodata
- `jadwal_semua_guide.html` - All guides schedule
- `jadwal_guide_individual.html` - Individual guide schedule
- `riwayat_guide.html` - Guide history

### Customer Pages
- `biodata_customer.html` - Customer biodata (view)
- `biodata_customer_form.html` - Customer biodata form
- `paket_trip.html` - Trip packages
- `book_trip.html` - Book trip form
- `booking_trip_customer.html` - Customer bookings
- `data_customer.html` - Customer data
- `riwayat_customer.html` - Customer history

## Deployment

This project is configured for deployment on Vercel.

### Local Development
1. Clone the repository
2. Open `Assets/home.html` in your browser
3. Navigate through the application

### Vercel Deployment
1. Push to GitHub
2. Import project to Vercel
3. Deploy automatically

## Navigation Flow

```
Home → Register Selection → Register Form → Login
                        ↓
Login → Role Selection (Admin/Guide/Customer)
                        ↓
     Dashboard (Role-specific) → Feature Pages
```

## Features by Role

### Admin
- Manage guide data
- Manage customer data
- Manage trip packages
- View all bookings

### Guide
- View/edit personal biodata
- Manage schedule
- View trip history

### Customer
- View/edit personal biodata
- Browse trip packages
- Make bookings
- View booking history

## License

MIT License