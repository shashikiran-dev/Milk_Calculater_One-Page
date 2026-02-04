# 🥛 Milk Management System

A simple, elegant one-page web application for managing milk deliveries and tracking customer records. Built with vanilla HTML, CSS, and JavaScript with localStorage for persistent data storage.

## Features

### 👨‍💼 Vendor Dashboard
- **Add New Customers** - Register new customers with their details and milk rates
- **Track Daily Deliveries** - Log morning and evening milk deliveries
- **Real-time Statistics** - View today's morning and evening milk totals
- **Customer Management** - View all customers with their total milk consumption
- **Monthly Filtering** - Filter entries by month for detailed analysis
- **Entry Management** - Delete entries if needed

### 👤 Customer Dashboard
- **View Personal Records** - Access your milk delivery history
- **Monthly Summary** - See detailed breakdown of milk supply by session
- **Calculate Billing** - Automatic calculation of total amount based on quantity and rate
- **Session-wise Tracking** - Separate morning and evening milk tracking

## How to Use

### 1. **First Time Setup**
- Open `milk-management.html` in any web browser
- Login as Vendor (Admin):
  - **Name:** Admin
  - **Mobile:** 1234567890

### 2. **Add Customers**
- Click "Add New Customer" button
- Enter customer details:
  - Customer Name
  - Mobile Number (10 digits)
  - Rate per Liter (₹)
- Submit to add the customer

### 3. **Add Milk Entries**
- Click "Add Milk Entry" button
- Select customer from dropdown
- Choose date, session (Morning/Evening), and quantity
- Submit to record the entry

### 4. **View Reports**
- **Dashboard Stats** - See total customers and today's milk totals
- **View All Customers** - Check each customer's total milk consumption
- **Filter by Month** - Select specific months to view entries

### 5. **Customer Login**
- Select "Customer" as user type
- Enter customer name and mobile number
- View your personal milk records and monthly billing summary

## User Credentials

### Vendor (Admin)
- **Name:** Admin
- **Mobile:** 1234567890

### Customers
- Create new customers through the "Add New Customer" form
- Login with the registered name and mobile number

## Data Storage

- All data is stored in **browser's localStorage**
- Data persists across browser sessions
- Clear browser data to reset the application
- Export/Backup: Check browser DevTools → Application → Local Storage

## Technical Details

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Storage:** Browser LocalStorage API
- **Responsive Design:** Mobile-friendly interface
- **No Backend Required:** Fully client-side application

## Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Features Included

- ✅ User authentication (Vendor & Customer)
- ✅ Add/Delete milk entries
- ✅ Customer management
- ✅ Monthly filtering and statistics
- ✅ Automatic billing calculation
- ✅ Responsive UI with animations
- ✅ Real-time data updates
- ✅ Session tracking (Morning/Evening)

## Future Enhancements

- PDF export functionality
- Backend integration for multi-user support
- SMS/Email notifications
- Advanced analytics and reports
- Payment integration
- Mobile app version

## Installation & Deployment

1. **Local Use:**
   - Simply download `milk-management.html`
   - Double-click to open in browser
   - Start using immediately

2. **Deploy to Web:**
   - Upload `milk-management.html` to any web hosting service
   - No server configuration needed
   - Access via browser using the hosted URL

## Troubleshooting

### Data Not Saving?
- Check if browser allows localStorage
- Disable private/incognito mode
- Clear browser cache and reload

### Can't Login as Customer?
- Ensure customer exists (add via vendor dashboard first)
- Check exact name and mobile number match
- Mobile number should be 10 digits

### Form Not Responding?
- Refresh the browser page
- Clear localStorage and restart
- Try a different browser

## License

This project is open source and available for personal and commercial use.

## Support

For issues or suggestions, please refer to the GitHub repository:
https://github.com/shashikiran-dev/Milk_Calculater_One-Page.git

---

**Last Updated:** February 2026
**Version:** 1.0
