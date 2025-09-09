# MSTC Interview Platform

A modern, secure interview management platform built with vanilla HTML/CSS/JavaScript and Supabase.

## 🚀 Features

- **Dynamic Interview Creation**: Create custom interviews with unlimited questions
- **Secure Admin Authentication**: Email whitelist-based admin access
- **Response Management**: View and analyze submitted interview responses
- **Public Interview Access**: Share interview links for candidate participation
- **Mobile Responsive**: Works seamlessly across all devices

## 📁 Project Structure

```
mstc-interview/
├── index.html          # Landing page with navigation
├── admin.html          # Admin portal for creating interviews
├── interview.html      # Public interview taking interface
├── responses.html      # Admin interface for viewing responses
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## ⚙️ Setup Instructions

### 1. Clone and Configure

```bash
# Clone the repository
git clone <your-repo-url>
cd mstc-interview

```

## 🔐 Security Features

### Admin Access Control

- Email whitelist system prevents unauthorized admin access
- Supabase authentication with secure password requirements
- Profile-based role management in database

## 🎯 Usage

### For Administrators

1. Navigate to `/admin.html`
2. Sign in with whitelisted admin email
3. Create interviews with custom questions
4. Share generated interview links with candidates
5. View responses at `/responses.html`

### For Candidates

1. Visit the shared interview link or browse from `/index.html`
2. Fill out personal information (optional)
3. Answer interview questions
4. Submit responses

## 🛠️ Development

### Adding New Admin Emails

```javascript
ADMIN_EMAILS: ["admin1@domain.com", "admin2@domain.com"];
```

### Customizing Styling

Each HTML file contains embedded CSS that can be customized:

- Modify color schemes in CSS variables
- Adjust responsive breakpoints
- Update typography and spacing

### Adding Features

The modular structure makes it easy to add new features:

- Add new database tables in Supabase
- Create new HTML pages for additional functionality
- Extend the config system for new settings


## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
