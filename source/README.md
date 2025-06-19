# Project Overview

This repository contains three main projects that focus on different aspects of business operations and IT service management. Below is a summary of each component.

## 1. Orders Manager (Java Application)

A comprehensive order management solution for retail stores, developed as a full-stack Java web application.

### Key Features:
- Manage customers, products, suppliers, and orders
- Generate PDF invoices and order itineraries
- Track order status (incoming, approved, shipped, payment debts, canceled)
- View order locations on interactive maps
- Dashboard with analytics and reporting

### Technologies:
- **Frontend**: jQuery, ChartJS, Vue.js, W3.CSS, Font Awesome
- **Backend**: Java 8, JSP, Servlets
- **Database**: MariaDB 10.4
- **Server**: Apache Tomcat 8.5
- **Tools**: Maven, LaTeX for PDF generation

### Deployment:
- Supports both development (with Docker) and production environments
- Includes Docker Compose configurations for easy setup

---

## 2. Purchasing Toolpak (Excel/Word Templates)

A collection of free Excel and Word templates designed for procurement professionals.

### Key Templates:
- **Purchase Order** - For ordering parts or services
- **Bid Evaluation** - Compare bids from multiple suppliers
- **Request for Quotation** - Solicit supplier bids
- **Supplier Profile Form** - Assess supplier capabilities
- **Contract Approval** - Manage procurement contract approvals

### Compatibility:
- Microsoft Office (Excel/Word)
- Mac OS (Pages/Numbers)
- Google Docs/Sheets
- Apache OpenOffice

### Features:
- Free to use and modify
- Cross-platform compatibility
- Simple, user-friendly interfaces
- Focus on procurement efficiency

---

## 3. iTop (IT Operations Portal)

An open-source, web-based IT service management platform with extensive features for IT operations.

### Core Features:
- **Configuration Management (CMDB)** - Fully configurable IT asset management
- **HelpDesk & Incident Management** - Streamlined ticketing system
- **Service & Contract Management** - Comprehensive service tracking
- **Change Management** - Controlled IT change processes
- **SLA Management** - Configurable service level agreements
- **Impact Analysis** - Visual impact assessment tools
- **Data Import/Export** - CSV import tools and data synchronization

### Key Benefits:
- ITIL compliant
- Highly customizable and extensible
- Web-based interface
- Active community and enterprise support
- Available in multiple languages

### Technical Requirements:
- Web server (Apache/Nginx)
- PHP 7.2+
- MySQL/MariaDB
- Modern web browser

---

## Getting Started

Each component has its own setup and installation instructions. Please refer to the respective README files for detailed information:

1. `README_Orders.md` - For the Java-based Orders Manager
2. `README_Excel.md` - For the Purchasing Toolpak templates
3. `itop/README.md` - For the iTop IT Operations Portal

## License

Each component is licensed separately:
- Orders Manager: [MIT License](https://choosealicense.com/licenses/mit/)
- Purchasing Toolpak: Check individual template licenses
- iTop: Open Source (various components may have different licenses)

## Support

For support and contributions, please refer to the respective project documentation and repositories.
