# HealthGuard - Smart Medicine Management

## Problem Statement

Keeping track of medicine expiry dates is crucial for patient safety but can be challenging for both individuals and pharmacies. Expired medications can be ineffective or even harmful. Pharmacies need an efficient way to manage their inventory and notify customers about approaching expiry dates.

## Solution Overview

HealthGuard is a web application designed to help pharmacies and customers manage medicine expiry dates. Pharmacies can easily add medicine details, including expiry dates, to a customer's profile. The system then provides timely alerts to both the pharmacy and the customer about medicines that are expiring soon, ensuring safe and effective medication use.

## Features

-   **Pharmacy Dashboard:** Overview of medicine inventory and quick access to key actions.
-   **Medicine Upload/Manual Entry:** Pharmacies can add medicine details by uploading CSV/Excel files or entering data manually.
-   **Data Preview:** Preview uploaded medicine data before processing.
-   **Expiry Alerts:** Prominent display of medicines expiring within the next 7 days on the pharmacy dashboard.
-   **Customer Contact Information:** View customer phone numbers directly from the expiry alert to facilitate communication.
-   **Medicine Search & Filtering:** Easily search and filter the medicine inventory.
-   **Medicine Details:** View detailed information for each medicine.

## Tech Stack

-   **Frontend:** React, TypeScript, Vite
-   **Styling:** Tailwind CSS
-   **State Management:** React Hooks, Context API
-   **Date Handling:** `date-fns`
-   **File Processing:** `xlsx` (for Excel/CSV upload)
-   **Routing:** `react-router-dom`
-   **Icons:** `lucide-react`
-   **(Note: The current version uses mock data for services like authentication and medicine storage. A production version would integrate with a backend like Supabase.)**

## Setup Instructions

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository_url>
    cd project
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Set up environment variables (for production/backend integration):**
    *(Instructions for setting up Supabase or other backend details would go here in a real project. For this mock version, no specific backend setup is strictly required to run the frontend.)*
4.  **Run the development server:**
    ```bash
    npm run dev
    ```

    The application should now be running at `http://localhost:5173/` (or another available port).

5.  **Access the application:** Open your web browser and navigate to the local address provided by the `npm run dev` command.

## Usage

-   Log in as a pharmacy user (using phone `9876543210` for the mock data).
-   Explore the dashboard, add medicines via upload or manual entry, and observe expiry alerts. 