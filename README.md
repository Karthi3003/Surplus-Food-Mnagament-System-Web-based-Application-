# Surplus-Food-Mnagament-System-Web-based-Application-

### Project Title: Surplus Food Management System

#### Objective:
The Surplus Food Management System aims to reduce food wastage by connecting individuals or organizations with surplus food to those in need, such as shelters, food banks, or NGOs. The system provides a streamlined process for donating food, thus contributing to hunger relief and minimizing food wastage.

#### Technology Stack:
- **Frontend**: React.js
- **Backend**: Node.js/Express.js
- **Database**: MongoDB (or other NoSQL databases)
- **APIs**: Google Maps API (for geolocation and routing), Twilio API (for SMS notifications)
- **Hosting**: Firebase (for hosting and deployment)

#### Features:
1. **User Registration and Authentication**: 
   - Users can sign up as donors (individuals, restaurants, or organizations) or receivers (NGOs, shelters).
   - Authentication using JWT to ensure secure access.

2. **Food Listing**: 
   - Donors can create listings for surplus food, providing details like food type, quantity, expiry date, and pick-up location.
   - Receivers can view available food items based on location and filter by food type or availability.

3. **Real-time Notifications**:
   - When a food listing is created, nearby registered receivers are notified via SMS or email about the availability of surplus food.
   - Donors receive notifications once the food is accepted for pick-up.

4. **Geolocation and Routing**:
   - Integration with Google Maps API to help receivers find the quickest route to the donor’s location.
   - The system prioritizes donations based on proximity to avoid food spoiling.

5. **Food Pickup and Tracking**:
   - Receivers can claim food listings and schedule a pickup time.
   - Once the food is picked up, the system marks the donation as completed, tracking successful deliveries.

6. **Donation History and Analytics**:
   - Donors and receivers can view their past donation and collection activities.
   - Basic analytics to show donors how much food they’ve contributed and the impact they’ve made in terms of reducing food wastage.

7. **Admin Dashboard**:
   - Admins can manage users, monitor transactions, and generate reports on food donation activities.
   - Anomaly detection for expired or inactive listings.

#### Key Functionalities:
- **Search and Filter**: Receivers can search for food based on type, location, and urgency.
- **Verification System**: Ensures that donated food meets health and safety regulations through reporting and verification by users.
- **User Ratings and Feedback**: Both donors and receivers can rate each other and provide feedback on the quality of food and overall experience.

#### Future Enhancements:
- **Mobile App Integration**: Expanding the platform with a mobile app for better accessibility.
- **Partnership with Delivery Services**: Collaborate with delivery companies to facilitate food transportation for donors who cannot deliver.

#### Impact:
- **Sustainability**: Reducing food wastage and contributing to sustainability goals by repurposing surplus food.
- **Social Good**: Addressing hunger and food insecurity by making surplus food accessible to those in need.

