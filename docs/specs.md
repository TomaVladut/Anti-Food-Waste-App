# Objective
Develop a web app to reduce food waste through community sharing.

## Features and Functionalities
1. **User Fridge List**: 
   - Users can organize a list of products in their fridge.
   - Notifications are sent when products approach expiry.

2. **Sharing Products**:
   - Users can mark products from lists as "available to share."
   - Other users can claim shared products.

3. **Groups and Friends**:
   - Users can define groups of friends with labels based on food preferences.
   - Friends can access the shared product list.

4. **Social Media Sharing**:
   - Users can share their available product list on social media platforms.

## Technical Details
### Frontend
- Framework: React.js

### Backend
- Framework: Node.js
- REST API: Express.js
- Data Persistence: Sequelize ORM (for relational database)

### Database
- Relational Database: MySQL
- Key Tables:
  - Users
  - Products
  - Groups
  - Claims

### Deployment
- Server: AWS or Azure (free tier for students).