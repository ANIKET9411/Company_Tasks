# Real Estate Card Component

This project involves creating a reusable and dynamic card component for a real estate application using React. The card displays property details, such as price, location, number of beds and baths, and includes a favorite feature that allows users to mark properties they like.

## Overview

The Real Estate Card Component is designed to provide an interactive and visually appealing way to display property listings. Each card shows essential details about a property, including images, price, size, and location. Users can mark properties as favorites, which are stored in the application's state, enabling a seamless user experience.

## Features

- **Property Details**: Displays property image, price, location, number of beds, baths, and size.
- **Favorite Functionality**: Allows users to mark and unmark properties as favorites.
- **Responsive Design**: Ensures the card layout is adaptable to various screen sizes.
- **Icons Integration**: Utilizes Font Awesome icons for visual enhancement.

## Components Overview

### Card Component

![image](https://github.com/user-attachments/assets/bf319853-04e9-4d79-a6bf-1fbcf1a2ef1c)


- Displays the property image at the top.
- Shows the price, marked with a Rupee symbol.
- Includes buttons to display the number of beds, baths, and the property size.
- Features a heart icon to mark the property as a favorite.

### Favorite Feature

![image](https://github.com/user-attachments/assets/ce8e1f42-f97e-4461-97ec-f645fb0e24a2)


- The heart icon changes color based on whether the property is marked as a favorite or not.
- Clicking the heart icon updates the favorite status in the application's state.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/real-estate-card-component.git
    ```
2. Navigate to the project directory:
    ```bash
    cd REAL_ESTATE
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Run the project:
    ```bash
    npm start
    ```

## Packages Used

- **React**: JavaScript library for building user interfaces.
- **React Icons**: Provides popular icons to use within your React projects.
- **TailwindCSS**: Utility-first CSS framework for styling the components.

## Learning from the Project

This project enhanced my understanding of:
- State management in React using the `useContext` hook.
- Creating dynamic and responsive UI components with TailwindCSS.
- Implementing and managing user interaction features like favorites.

## Future Improvements

- **Local Storage**: Persist favorite properties in local storage so that the favorite status is retained on page refresh.
- **Search Functionality**: Add a search bar to filter properties by location or price range.
- **Animations**: Incorporate smooth transitions for adding/removing properties from favorites.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

