# MediConnect

## Overview

MediConnect is a comprehensive medical appointment and communication platform designed to connect patients, doctors, and administrators seamlessly. It enables patients to browse doctors, book appointments, and communicate in real-time, while providing admins and doctors with tools to manage appointments, profiles, and interactions. The project is divided into three main components: **MediConnect-UI** (patient interface), **MediConnect-Admin** (admin and doctor interface), and **MediConnect-API** (backend API).

## Project Structure

The MediConnect project is organized into three repositories, each with its own detailed README for setup and usage instructions:

- **MediConnect-API**: The backend API built with Node.js, Express.js, and MongoDB, handling authentication, appointment management, payments, and real-time communication. See the [MediConnect-API README](MediConnect-API/README.md) for details.
- **MediConnect-UI**: The patient-facing front-end interface built with React, Vite, and Tailwind CSS for browsing doctors, booking appointments, and chatting. See the [MediConnect-UI README](MediConnect-UI/README.md) for details.
- **MediConnect-Admin**: The admin and doctor interface built with React, Vite, and Tailwind CSS for managing appointments, doctors, and profiles. See the [MediConnect-Admin README](MediConnect-Admin/README.md) for details.

## Hosted Applications

- **Patient Interface**: [MediConnect-UI](https://medi-connect-ui-three.vercel.app/)
- **Admin/Doctor Interface**: [MediConnect-Admin](https://medi-connect-api-kmpz.vercel.app/)

## Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Real-time Communication**: Socket.IO
- **Authentication**: JSON Web Tokens (JWT)
- **File Uploads**: Cloudinary
- **Version Control**: Git
- **Hosting**: Vercel (frontend), GitHub (backend)

## Getting Started

To set up the MediConnect project locally, follow the installation instructions in the respective README files for each component:
1. **MediConnect-API**: Backend setup instructions are in [MediConnect-API/README.md](MediConnect-API/README.md).
2. **MediConnect-UI**: Patient interface setup instructions are in [MediConnect-UI/README.md](MediConnect-UI/README.md).
3. **MediConnect-Admin**: Admin/doctor interface setup instructions are in [MediConnect-Admin/README.md](MediConnect-Admin/README.md).

Ensure the backend API is running before starting the frontend applications, as they depend on the API for functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file in each repository for details.

## Contact

For questions or feedback, reach out to the project maintainer at [yash1302](https://github.com/yash1302/).