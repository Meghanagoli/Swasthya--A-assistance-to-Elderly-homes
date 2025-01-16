
# Swasthya - A Assistance to Elderly Homes

**Swasthya** is a project aimed at providing technological support to elderly homes. The system focuses on improving the daily lives of elderly residents by offering tools for health tracking, reminders for medications, and connecting them with caregivers and medical professionals. Through this project, we aim to ensure that elderly individuals living in care homes receive better attention, personalized services, and social interaction.

## Features

- **Health Tracking**: Monitor vital health statistics (blood pressure, heart rate, oxygen levels, etc.) and track progress.
- **Medication Reminders**: Set reminders for when to take medications to ensure timely doses.
- **Doctor & Caregiver Communication**: An interface to allow communication between doctors, caregivers, and the elderly.
- **Reports & Analytics**: Generate reports on health statistics and overall well-being for caregivers and medical staff.
- **User Authentication**: Secure login system for different roles (caregivers, elderly homes, medical staff).

## Tech Stack

- **Frontend**: React.js (for the dynamic user interface)
- **Backend**: Node.js with Express.js (for handling API requests)
- **Database**: MongoDB (for storing user and health data)
- **Machine Learning**: Used for health predictions and detecting potential health issues.

## Installation

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Meghanagoli/Swasthya--A-assistance-to-Elderly-homes.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Swasthya--A-assistance-to-Elderly-homes
   ```

3. **Install dependencies for the backend**:
   ```bash
   cd backend
   npm install
   ```

4. **Install dependencies for the frontend**:
   ```bash
   cd ../frontend
   npm install
   ```

5. **Download datasets for Machine Learning predictions**:
   Download the datasets from [this link](https://drive.google.com/drive/folders/1DddizlVTkNtr5uER_sf_9rHllG9NcYeO?usp=drive_link) and place them in the `ML` folder.

6. **Start the application**:
   - For the backend:
     ```bash
     cd backend
     npm start
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm start
     ```
   - For the Machine Learning:
     ```bash
     cd ML
     python main.py
     ```

## Usage

1. **Login/Register**: Users can register and log in as caregivers (elderly home) or medical staff to access their dashboards.
2. **Health Monitoring**: Users can track health metrics and monitor progress over time.
3. **Medication Reminders**: Set up notifications for medication schedules.
4. **Communication**: Engage with doctors and caregivers through the built-in video system.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a pull request.

