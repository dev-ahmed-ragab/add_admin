# Restaurant Permissions App

This project is a Next.js application designed for restaurant owners to manage staff permissions. It allows owners to invite staff members, assign permissions, and handle password resets.

## Features

- Invite staff members via email with a 24-hour expiration link.
- Assign permissions to staff members (Super Admin or Branch Admin).
- View and manage the list of staff members and their permissions.
- Password reset functionality for invited staff members.

## Getting Started

### Prerequisites

- Node.js (version 14 or later)
- npm or yarn

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd restaurant-permissions-app
   ```

3. Install the dependencies:

   ```
   npm install
   ```

   or

   ```
   yarn install
   ```

### Running the Application

To start the development server, run:

```
npm run dev
```

or

```
yarn dev
```

The application will be available at `http://localhost:3000`.

### Tailwind CSS Setup

This project uses Tailwind CSS for styling. The global styles are defined in `src/styles/globals.css`. You can customize the Tailwind configuration in `tailwind.config.js`.

### API Endpoints

- **POST /api/invite**: Sends an email invitation to a staff member.
- **POST /api/reset-password**: Allows a staff member to reset their password using the invitation link.

### Components

- **InviteForm**: A form for inviting new staff members.
- **PermissionList**: Displays the list of permissions available for staff members.
- **StaffList**: Displays the list of staff members and their assigned permissions.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.