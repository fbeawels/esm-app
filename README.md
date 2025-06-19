# Unified Enterprise Management System (UEMS)

## Project Overview

The Unified Enterprise Management System (UEMS) is an integrated solution that consolidates three legacy systems into a cohesive platform:

1. **Orders Management System** - Java-based order processing and tracking
2. **Contract Management System** - Excel-based supplier and contract administration
3. **Ticket Management System** - iTop-based IT service management

## Core Components

### 1. Orders Management System
- **Purpose**: End-to-end order processing and customer management
- **Key Features**:
  - Order creation, approval, and tracking
  - Customer and product management
  - PDF invoice generation
  - Supplier coordination
- **Technologies**: Java, JSP, MariaDB, Apache Tomcat, Docker

### 2. Contract Management System
- **Purpose**: Comprehensive supplier and contract lifecycle management
- **Key Features**:
  - Supplier onboarding and qualification
  - Contract creation and approval workflows
  - RFQ management
  - Compliance tracking
- **Technologies**: Excel templates, Relational database backend

### 3. Ticket Management System
- **Purpose**: IT service management and support
- **Key Features**:
  - Incident and service request management
  - SLA tracking and escalation
  - CMDB integration
  - Multi-level assignment workflows
- **Technologies**: iTop framework, PHP, MySQL

## System Integration

### Key Integration Points
- **Supplier Data**: Synchronization between Orders and Contracts systems
- **Customer/Organization**: Unified view across Orders and Tickets systems
- **Order-Ticket Linkage**: Automatic ticket creation for order issues
- **Contract Compliance**: Real-time validation during order processing

### Integration Challenges
- Data duplication across systems
- Inconsistent data formats and standards
- Manual integration processes
- Lack of real-time synchronization

## Architecture

### Current State
- Three separate systems with limited integration
- Manual data exchange processes
- Disparate technologies and data models

### Future State (Unified Architecture)
- Event-driven microservices architecture
- Centralized master data management
- Real-time integration through an Integration Hub
- Unified user experience

## Key Business Benefits

1. **Eliminated Data Silos**
   - Single source of truth for customer, supplier, and product data
   - Consistent information across all business functions

2. **Streamlined Operations**
   - Automated workflows across order, contract, and ticket management
   - Reduced manual data entry and errors

3. **Enhanced Visibility**
   - Real-time dashboards and reporting
   - End-to-end process tracking

4. **Improved Compliance**
   - Automated contract validation
   - Audit trails for all business processes

## Getting Started

### Prerequisites
- Java 8+ (for Orders System)
- PHP 7.4+ (for Ticket System)
- MariaDB/MySQL
- Docker (for containerized deployment)

### Installation
Detailed installation instructions for each legacy component are available in their respective directories:
- [Orders System](./source/README_Orders.md)
- [Contract Management](./source/README_Excel.md)
- [Ticket System](./source/README_itop.md)

## Documentation

### System Design
- [Detailed System Design](./design/SystemDesign_detailed.md)
- [System Design Summary](./design/SystemDesign_summary.md)

### Discovery Documents
- [Orders System Analysis](./discovery/orders-system-analysis.md)
- [Contract System Analysis](./discovery/contracts-system-analysis.md)
- [Ticket System Analysis](./discovery/ticket-system-analysis.md)
- [Data Integration Points](./discovery/data-integration-points.md)


