# Crypto Tax Calculator Australia

This project is a React-based application designed to help users calculate their capital gains tax on cryptocurrency investments in Australia. The calculator takes into account the purchase price, sale price, expenses, investment type, and annual income to determine the tax payable on capital gains.

## Overview

The Crypto Tax Calculator provides a user-friendly interface for calculating potential tax liabilities from cryptocurrency transactions. The calculator factors in long-term and short-term investment gains and applies the appropriate tax rate based on the user's annual income bracket.

## Features

- **Purchase and Sale Price Input**: Users can input the purchase and sale price of their cryptocurrency.
- **Expense Calculation**: Deducts user-input expenses from the capital gains.
- **Investment Type Selection**: Supports both short-term and long-term investment types, applying a 50% discount on gains for long-term investments.
- **Annual Income Bracket Selection**: Allows users to select their income bracket, with the calculator automatically applying the correct tax rate.
- **Dynamic Tax Calculation**: Displays the calculated capital gains, applicable discounts, net capital gains, and the tax amount payable.

## Components Overview

### Main_clac Component

![image](https://github.com/user-attachments/assets/9d5357fe-2c2d-4e43-8324-c5c25f39c59a)


- **Inputs**: Users can enter the purchase price, sale price, and expenses associated with their cryptocurrency investment.
- **Investment Type Buttons**: Options for selecting whether the investment is short-term or long-term, with visual indicators for the selected option.
- **Annual Income Dropdown**: A dropdown to select the user's annual income, which determines the tax rate applied to capital gains.
- **Dynamic Calculations**: Displays the tax rate, capital gains, long-term discount, net capital gains, and the tax payable in real-time as the user inputs data.

### Tax Rate Display

![image](https://github.com/user-attachments/assets/0ad0d775-d381-44e5-8e38-2f7195d83c1d)


- **Tax Rate Information**: Shows the applicable tax rate based on the selected annual income bracket.
- **Capital Gains Calculation**: Displays the calculated capital gains and any applicable long-term discount.
- **Tax Amount**: Displays the final tax amount that the user needs to pay based on the net capital gains.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/crypto-tax-calculator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd CRYPTO_TAX_CALCULATOR
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
- **TailwindCSS**: Utility-first CSS framework for styling the components.

## Learning from the Project

This project helped me gain experience in:
- Using React hooks like `useState` and `useEffect` to manage component state and side effects.
- Building interactive forms and handling user input in a React application.
- Applying tax rules dynamically based on user input and presenting calculated results in a clear and concise manner.
- Enhancing UI/UX using TailwindCSS for responsive and attractive design.

## Future Improvements

- **Additional Tax Brackets**: Expand the application to support other countries and tax systems.
- **Historical Data**: Include a feature for users to save and compare their tax calculations over time.
- **Advanced Options**: Add advanced settings for users to input more detailed financial data, such as multiple transactions, varying tax rates, and currency conversion.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Hosted Link
https://company-tasks.vercel.app/#
