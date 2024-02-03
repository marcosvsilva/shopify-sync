#£ Shopify

### Overview

This console application serves as a synchronization bridge between your ERP system and the Shopify API. It enables seamless data exchange, ensuring that your product information, inventory, and orders stay up-to-date across both platforms. Built with Node.js, this web service adheres to the MIT License, allowing for flexibility and easy integration into your existing technology stack.

### Features

- **Product Sync:** Automate the synchronization of product details between your ERP system and Shopify. This includes product name, description, price, and other relevant information.

- **Inventory Management:** Keep inventory levels in sync, ensuring accurate stock information on both your ERP and Shopify.

- **Order Sync:** Streamline order processing by synchronizing orders between Shopify and your ERP, reducing manual data entry and minimizing errors.

### Requirements

- Node.js: Ensure you have Node.js installed on your server. You can download it from [nodejs.org](https://nodejs.org/).

- Shopify API Credentials: Obtain your Shopify API credentials (API key, secret, and store URL) to authenticate the application.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-repo/shopify-erp-sync.git
    ```

2. Install dependencies:

    ```bash
    cd shopify-erp-sync
    npm install
    ```

3. Configure the application:

    Open the `config.js` file and input your Shopify API credentials and any other configuration parameters required.

### Usage

1. Run the application:

    ```bash
    npm start
    ```

2. The console app will initiate synchronization based on the configured intervals. You can also trigger manual syncs as needed.

### Configuration

Adjust the `config.js` file to customize synchronization intervals, logging preferences, and any additional settings required for your specific setup.

### License

This web service is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs.

### Support and Contribution

For support or to contribute to the development of this application, please open an issue or submit a pull request on the [GitHub repository](https://github.com/marcosvsilva/shopify-sync).

---

Feel free to customize this README.md template according to your specific implementation details and requirements.
