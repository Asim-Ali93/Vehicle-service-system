# AutoCare Pro — React Components

A responsive React + Vite implementation based on the uploaded AutoCare Pro screenshots.

## Included components
- `Navbar` — brand and Book Now navigation
- `Hero` — headline, calls to action and service statistics
- `VehicleHealth` — vehicle health report card
- `Services` — six selectable service cards with prices
- `BookingSteps` — four-step booking explanation
- `BookingForm` — responsive booking form, validation and selected-service summary
- `Footer` — contact and brand footer

## Run locally
1. Install Node.js (LTS).
2. Extract this ZIP and open the `autocare-pro` folder in VS Code.
3. Open the terminal in that folder and run:

```bash
npm install
npm run dev
```

4. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Notes
- Select a service card to preselect it in the booking form.
- The form validates required fields and a 10-digit mobile number.
- Booking submission currently displays a confirmation message in the browser. It is a front-end demo; connect an API/database to store real bookings.
- Contact details in the footer are demo placeholders and should be replaced with your real business details.
