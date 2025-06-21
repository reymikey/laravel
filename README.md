<p align="center">
    <h1 align="center">POS System Using Laravel</h1>
</p>

The project was created while recording video "[Create POS System Using Laravel](https://www.youtube.com/watch?v=Y_NRk0lOOJc&list=PL2hV0q47BY-G9f5xG9Vq-wGjSyy1BekOv)"

## Installation

### Requirements

For system requirements you [Check Laravel Requirement](https://laravel.com/docs/10.x/deployment#server-requirements)

### Clone the repository from github.

    git clone https://github.com/angkosal/laravel-pos.git [YourDirectoryName]

The command installs the project in a directory named `YourDirectoryName`. You can choose a different
directory name if you want.

### Install dependencies

Laravel utilizes [Composer](https://getcomposer.org/) to manage its dependencies. So, before using Laravel, make sure you have Composer installed on your machine.

    cd YourDirectoryName
    composer install

### Config file

Rename or copy `.env.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file.

### Database

1. Migrate database table `php artisan migrate`
1. `php artisan db:seed`, this will initialize settings and create and admin user for you [email: admin@gmail.com - password: admin123]

### Install Node Dependencies

1. `npm install` to install node dependencies
1. `npm run dev` for development or `npm run build` for production

### Create storage link

`php artisan storage:link`

### Run Server

1. `php artisan serve` or Laravel Homestead
1. Visit `localhost:8000` in your browser. Email: `admin@gmail.com`, Password: `admin123`.
 <!-- 1. Online demo: [pos.khmernokor.com](https://pos.khmernokor.com/) -->

### Screenshots

#### Product list

![Product list](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/products_list.png)

#### Create order

![Create order](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/pos.png)

#### Order list

![Order list](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/order_list.png)

#### Customer list

![Customer list](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/customer_list.png)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/angkosal)


# 🌟 Or Khmernokor POS :)

[Khmernokor POS](https://pos.khmernokor.com) is a modern and efficient Point of Sale system tailored for restaurants, cafés, and retail businesses. Built with a focus on usability, speed, and flexibility, it provides an all-in-one solution for front-of-house and back-of-house operations.

---

## 🖥️ POS Screen
![POS Screen](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/pos.png)

The POS interface is clean, responsive, and optimized for quick ordering. Cashiers and servers can easily select items, apply discounts, manage tables, and process various payment methods efficiently.

---

## 🖨️ Kitchen Printer
![Kitchen Printer](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/kitchen-printer.jpg)

Orders placed via the POS are instantly sent to the kitchen printer. This ensures accurate, printed tickets that help kitchen staff prepare dishes quickly and with minimal error.

---

## 🍽️ Kitchen Display System (KDS)
![Kitchen Display](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/kitchen-display.png)

Replace traditional printed tickets with a digital kitchen display. Staff can view and manage incoming orders in real time, mark items as complete, and streamline food preparation.

---

## 🧾 Receipt Preview
![Receipt Preview](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/receipt-preview.png)

Preview and print receipts with detailed breakdowns of items, quantities, discounts, taxes, and total amounts—customizable to suit your business branding.

---

## 🖨️ Cashier Printer
![Cashier Printer](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/cashier-printer.jpg)

Print high-quality receipts at the cashier station for customers upon checkout. Reliable and fast printing supports smooth and professional transactions.

---

## 📱 QR Menu for Customers ordering
<!-- ![QR Menu](https://raw.githubusercontent.com/angkosal/laravel-pos/master/screenshots/khmernokor-pos/qr-menu.png) -->

Let customers scan a QR code to view the digital menu on their phones. This contactless feature enhances the dining experience while reducing the need for physical menus.

---

Khmernokor POS is your complete solution for managing restaurant operations—from order taking and kitchen coordination to payment and reporting.

🔗 [Explore more at pos.khmernokor.com](https://pos.khmernokor.com)
