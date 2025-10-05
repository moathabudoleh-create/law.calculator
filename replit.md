# Labor Rights Calculator (حاسبة الحقوق العمالية)

## Overview
This is a Labor Rights Calculator web application based on Jordanian Labor Law. It helps workers calculate their employment benefits and entitlements including end-of-service awards, dismissal compensation, notice period compensation, annual leave compensation, overtime pay, and holiday/Friday work compensation.

## Project Type
Static HTML single-page application with embedded JavaScript and CSS

## Technology Stack
- **HTML5** - Single page application
- **Tailwind CSS** (CDN) - Styling framework
- **Day.js** (CDN) - Date manipulation library
- **Three.js** (CDN) - 3D background animation
- **Google AdSense** - Ad integration

## Project Structure
```
.
├── index.html          # Main application file (renamed from Arabic filename)
├── package.json        # Node.js package configuration
├── .gitignore         # Git ignore rules for Node.js
└── README.md          # Original project documentation
```

## Features
The calculator computes:
1. **End of Service Award** (مكافأة نهاية الخدمة)
2. **Dismissal Compensation** (بدل الفصل التعسفي)
3. **Notice Period Compensation** (بدل شهر الإشعار)
4. **Annual Leave Compensation** (بدل الإجازات السنوية)
5. **Overtime Compensation** (بدل العمل الإضافي)
6. **Holiday Work Compensation** (بدل دوام العطل)
7. **Friday Work Compensation** (بدل دوام أيام الجمع)
8. **Accrued Salaries** (الرواتب المستحقة)

## Running the Application

### Development
The application runs on port 5000 using the `serve` package:
```bash
npx serve -l 5000 --no-clipboard
```

### Deployment
Configured for Replit Autoscale deployment, which is ideal for this stateless web application.

## Important Notes
- The application is in Arabic (RTL layout)
- All calculations are based on Jordanian Labor Law
- The calculator includes a disclaimer that it's for guidance only and recommends consulting a lawyer
- Features a 3D animated background using Three.js
- Includes Google AdSense integration

## Recent Changes
- **2025-10-05**: Imported from GitHub and set up for Replit environment
  - Renamed main HTML file to `index.html` for standard web serving
  - Installed Node.js and `serve` package for static file serving
  - Configured workflow to run on port 5000
  - Set up deployment configuration for Autoscale
  - Created .gitignore for Node.js dependencies

## Contact Information
The application includes contact details for:
- المحامي معاذ ابو دوله (Lawyer Muath Abu Dola)
- WhatsApp: +962788898842
