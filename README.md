# Project Documentation

## Overview

This repository contains two SQL-based projects:

1. **Exam_DB**: A database schema focused on managing information related to children, addresses, letters, gift categories, and users (Santa and elves) with access rights.

2. **Space Colony Management System (SCMS)**: A database management system designed to facilitate efficient resource allocation and task management within a space colony, utilizing AI and blockchain technologies.

## Project Descriptions

### 1. Exam_DB
This project is structured to manage various aspects of Santa's operations, including child records, gift statuses, addresses, and user permissions. Key components are:

- **Children**: Stores details of each child.
- **Addresses**: Stores location information for children.
- **Letters**: Tracks letters sent by children to Santa.
- **Gift Categories** and **Gift Statuses**: Manages the classification and state of gifts.
- **Users**: Stores information about Santa's helpers (elves).
- **Access Rights**: Manages user permissions for database elements.

#### Key SQL Queries:
- Retrieve gift counts by country and status.
- List children who have sent more letters than the number of gifts received.
- Optimize queries with indexes for large datasets.

### 2. Space Colony Management System (SCMS)
The SCMS is a project for managing various departments and resource allocations within a space colony. The system supports role-based access for colony managers, engineers, security, researchers, and chefs, ensuring efficient operation.

#### Key Functionalities:
- **Colony Management**: Priority setting, resource distribution, and safety monitoring.
- **Life Support System**: Maintenance tracking and task assignment.
- **Security and Safety**: Task scheduling and monitoring for security staff.
- **Research and Development**: Managing laboratory resources and projects.
- **Food and Supplies**: Inventory and menu planning based on available resources.

#### Key SQL Queries:
- Monitor overdue tasks.
- Track resource usage and availability.
- Report on safety equipment conditions.

## Database Details

### Exam_DB
- **Host**: `ep-sparkling-thunder-15701210.eu-central-1.aws.neon.tech`
- **Database**: `exam_db`

### Space Colony Management System
- **Host**: `ep-polished-poetry-56003604.eu-central-1.aws.neon.tech`
- **Database**: `Space_Colony_Management_System`

## Credits
Both projects were completed by Andrei Lavrov, Group 212, Third-year student.

## License
This repository does not specify a license. Please contact the author for usage permissions.
