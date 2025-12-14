# SaaS Accounts Dashboard

A visual UI for managing your SaaS account database with a clean, modern interface.

## Features

- 📊 **Dashboard Statistics**: View total accounts, active accounts, and monthly costs at a glance
- ➕ **Add New Accounts**: Easy-to-use form for adding new SaaS subscriptions
- 🎨 **Visual Account Cards**: Beautiful card-based layout displaying all account details
- 🗑️ **Delete Accounts**: Remove accounts with a single click
- 💾 **Local Storage**: All data is automatically saved in your browser's local storage
- 🔄 **Real-time Updates**: Statistics and display update instantly when adding or removing accounts
- 📱 **Responsive Design**: Works on desktop and mobile devices

## Usage

### Opening the Dashboard

Simply open `accounts-dashboard.html` in your web browser. You can:
- Double-click the file to open it in your default browser
- Right-click and select "Open with" to choose a specific browser
- Use a local web server: `python3 -m http.server 8080` and navigate to `http://localhost:8080/accounts-dashboard.html`

### Adding a New Account

1. Fill in the form fields:
   - **Service Name**: The name of the SaaS service (e.g., GitHub, AWS, Slack)
   - **Account Type**: Category of the service (Development, Marketing, Analytics, Cloud, Communication, Productivity, Other)
   - **Email**: The email address associated with the account
   - **Monthly Cost**: The monthly subscription cost in dollars
   - **Status**: Current status (Active, Trial, Inactive)
   - **Renewal Date**: The date when the subscription renews

2. Click the "Add Account" button
3. The new account will appear in the dashboard and statistics will update automatically

### Deleting an Account

Click the "🗑️ Delete Account" button on any account card. You'll be asked to confirm the deletion.

### Pre-loaded Sample Data

The dashboard comes with 5 sample SaaS accounts:
- GitHub (Development)
- AWS (Cloud)
- Google Workspace (Productivity)
- Slack (Communication)
- Figma (Development - Trial)

You can delete these and add your own accounts as needed.

## Data Persistence

All account data is stored in your browser's localStorage, which means:
- ✅ Data persists between browser sessions
- ✅ No server or database required
- ✅ Your data stays private on your computer
- ⚠️ Clearing browser data will remove saved accounts
- ⚠️ Data is specific to each browser and device

## Technical Details

- **Technology**: Pure HTML, CSS, and JavaScript (no dependencies)
- **Storage**: Browser localStorage API
- **Design**: Modern gradient design with card-based layout
- **Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## Customization

The dashboard is contained in a single HTML file, making it easy to customize:
- Modify the color scheme in the CSS `<style>` section
- Add new account types in the dropdown options
- Extend functionality by editing the JavaScript code
- Change the layout by modifying the CSS grid properties

## Screenshot

![SaaS Accounts Dashboard](https://github.com/user-attachments/assets/bb8c3b9f-a0b2-4abb-b046-e7a4870bc15e)

*The dashboard showing sample accounts with statistics, add form, and account cards*

---

**Note**: This is a client-side application. For production use with team collaboration, consider adding a backend API and database.
