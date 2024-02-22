<div align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

# Empress Mobile Accounting: Your Pocket-Sized Finance Powerhouse

Empress Mobile Accounting is here to transform and simplify your financial management. Tailored for small business owners, freelancers, and anyone who requires an efficient, user-friendly accounting solution, it is your ultimate tool for accounting on the go.

[Explore the Docs](https://empress.eco/) | [Report a Bug](https://github.com/empress-eco/mobile_accounting/issues) | [Request a Feature](https://github.com/empress-eco/mobile_accounting/issues)

</div>



## About The Project

Mobile Accounting, powered by Empress, is designed to streamline the complex world of financial management. It offers an intuitive mobile interface with easy navigation, making accounting tasks less daunting and more efficient.

Key Features:
- Streamlined accounting experience on mobile devices
- User-friendly interface for easy navigation
- Seamless integration with Empressjs-Accounting on the backend

## Technical Stack and Setup Instructions

Before getting started, ensure you have `Empressjs-Accounting` set up and running. If not, follow the [guide to set up Empressjs-Accounting](https://github.com/Empress/Empressjs-accounting).

### Installation
1. Clone this repository:
```bash
git clone https://github.com/empress-eco/mobile_accounting.git
```
2. Navigate into the cloned repository and install dependencies:
```bash
cd mobile_accounting
yarn
```
3. Connect your Android device to your PC/Laptop with USB debugging enabled on your device and ADB drivers installed on your PC/Laptop. Run the application using the following commands:
```bash
ionic cordova run android
```
For live updates and instant checks on your device, use:
```bash
ionic cordova run android --livereload --consolelogs
```
If you encounter errors related to the `universalify` package, run the command below and try again:
```bash
yarn add universalify
```

### Usage

You can run Mobile Accounting in your web browser using the command `ionic serve`. For more details and usage examples, refer to our [documentation](https://empress.eco/).

## Contribution Guidelines

Contributions are warmly welcomed and highly appreciated. Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

We look forward to your valuable contributions!

## License and Acknowledgements

This project is licensed under the MIT License. All your contributions to the project will also be licensed under the MIT License.

We would like to express our profound gratitude to the Empress Community, the driving force behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are deeply grateful for their pioneering work and ongoing support.