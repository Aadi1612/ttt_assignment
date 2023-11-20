Certainly! Here's a README for your project:

---

# Terribly Tiny Sales Profile Screen Renderer

This project renders a "profile screen" resembling [this design]([https://ttt-assignment-eta.vercel.app](https://www.terriblytinytales.com/profile.jpeg) with the following features:

- Profile data is hardcoded within a local JSON file, eliminating the need for a backend.
- Ensures consistent rendering across various mobile devices using Chrome Inspect's mobile view or physical devices.

## Installation and Setup

To get started with the project, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Aadi1612/ttt_assignment.git
    cd ttt_assignment
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Start the Development Server:**
    ```bash
    npm start
    ```

## Project Structure

The project's file structure is organized as follows:

- `src/components/`
    - `Navbar/`: Includes the navigation bar design.
    - `Maininfo/`: Contains the cover photo, profile photo, name, followers, and following count.
    - `Subinfo/`: Houses the bio, profile links, and other app elements.
    - `Profileinfo/`: Manages the design of followers and following count.

- `src/symbols/`: Directory holding custom symbols designed from flaticon.com.

## Components Description

- **Navbar Component:**
    - Design of the navigation bar.

- **Maininfo Component:**
    - Design and positioning of cover photo, profile photo, name, followers, and following count.

- **Subinfo Component:**
    - Includes the bio, profile links, and various app elements.

- **Profileinfo Component:**
    - Manages the design of followers, following count, and text styles.

## Libraries and Tools Used

The project utilizes the following libraries and tools:
- React: JavaScript library for building user interfaces.
- React-Scripts: Scripts and configurations for React projects.

Additionally, symbols such as hearts, views, likes, zodiac signs, etc., were designed on flaticon.com and are stored in the `src/symbols/` directory.

---

## Deployment

The solution is hosted on [Vercel](https://ttt-assignment-eta.vercel.app/)

For further details and instructions, refer to the [GitHub repository](https://github.com/Aadi1612/ttt_assignment).
