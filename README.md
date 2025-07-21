# MobileShoppe

MobileShoppe is a simple e-commerce web application for mobile phones, built with PHP and MySQL. It allows users to browse products, add them to a cart or wishlist, and manage their shopping experience. This project is ideal for learning the basics of PHP, MySQL, and web development.

## Features

- Browse a catalog of mobile phones
- Add products to cart and wishlist
- Move items between cart and wishlist
- Remove items from cart or wishlist
- View product details
- Blog/news section
- Responsive design

## Project Structure

```
MobileShoppe/
  ├── assets/                # Images and static assets
  ├── database/              # PHP classes for DB, Cart, Product, and SQL dump
  ├── Template/              # PHP templates for different sections
  ├── HTML Template/         # HTML/CSS/JS for UI and styling
  ├── cart.php               # Cart page
  ├── index.php              # Home page
  ├── product.php            # Product details page
  ├── functions.php          # Helper functions
  ├── header.php/footer.php  # Common header and footer
  ├── style.css              # Main stylesheet
  └── README.md              # Project documentation
```

---

## Getting Started

### Prerequisites

- PHP 7.x or higher
- MySQL or MariaDB
- Web server (e.g., Apache, XAMPP, WAMP)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AmineKhalfaouie/MobileShoppe.git
   ```

2. **Set up the database:**
   - Import the `shopee.sql` file located in `MobileShoppe/database/` into your MySQL server.
   - Update database credentials in `MobileShoppe/database/DBController.php` if needed.

3. **Configure your web server:**
   - Set the document root to the `MobileShoppe` directory.
   - Make sure PHP and MySQL are running.

4. **Access the application:**
   - Open your browser and go to `http://localhost/MobileShoppe/index.php`

## Usage

- Browse products on the home page.
- Add products to your cart or wishlist.
- Move items between cart and wishlist.
- Remove items as needed.
- Explore the blog section for news and updates.

## Screenshots

### Home Page
<img width="1365" height="635" alt="image" src="https://github.com/user-attachments/assets/557fd5c0-6b45-4529-b3f5-e0998c6f08a4" />


### Shopping Cart & Wishlist
<img width="1365" height="472" alt="image" src="https://github.com/user-attachments/assets/abe8fd94-5dfb-4a6b-a593-4c0a2a2462fc" />
<img width="1364" height="411" alt="image" src="https://github.com/user-attachments/assets/1cf2150d-ff90-4324-a8b9-5b60e7f7da10" />


### Product Details
<img width="1365" height="632" alt="image" src="https://github.com/user-attachments/assets/bceea742-2cb7-4fe0-95cf-9f0c6c8868ae" />


## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- Bootstrap for responsive design
- FontAwesome for icons

---

**Note:** Replace `AmineKhalfaouie` in the clone URL with your actual GitHub username. Add a `LICENSE` file if you want to specify a license. 
