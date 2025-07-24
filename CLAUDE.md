# Digital Namecard Project

## Project Overview
A responsive HTML-based digital business card for Clanton Wood, Director of Marketing | Admissions at The Ocean Corporation. The namecard displays contact information with interactive elements and allows users to download contact details as a vCard (.vcf) file.

## Project Structure
```
digital-namecard/
├── index.html          # Main HTML file
├── main.css           # Stylesheet
├── assets/            # Icons and graphics
│   ├── govtech-logo-blue.svg
│   ├── icon-address.svg
│   ├── icon-email.svg
│   ├── icon-phone.svg
│   ├── icon-website.svg
│   ├── preston-namecard.png
│   └── right-arrow.svg
├── CW_IF_Logo.png     # Profile image
├── Ocean Corp Wave logo.jpeg # Company logo
├── preston.jpg        # Additional profile image
└── user.vcf          # vCard file for contact download
```

## Features
- Responsive design with mobile-first approach
- Interactive contact sections (email, phone, website, address)
- vCard download functionality
- Clean, professional styling
- Company branding integration

## Development
This is a static HTML project. No build process or dependencies required.

### To view locally:
1. Open `index.html` in a web browser
2. Or serve via local web server for testing

### To deploy:
- Upload files to any static hosting service
- Ensure all asset paths remain relative

## Contact Information Displayed
- **Name**: Clanton Wood
- **Title**: Director of Marketing | Admissions
- **Company**: The Ocean Corporation
- **Email**: clanton@oceancorp.com
- **Phone**: 713.829.7729
- **Website**: oceancorp.com
- **Address**: 10840 Rockley Rd, Houston, TX 77099

## Customization
To customize for different users:
1. Update contact information in `index.html`
2. Replace profile image (`CW_IF_Logo.png`)
3. Replace company logo (`Ocean Corp Wave logo.jpeg`)
4. Update `user.vcf` with new contact details
5. Modify colors/styling in `main.css` as needed