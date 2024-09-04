<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Return and Warranty Policy - Apple Store</title>
    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #666;
            color: #fff;
            height: 150px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header-title {
            font-size: 36px;
            font-weight: bold;
        }

        .search-container {
            display: flex;
            align-items: center;
        }

        .search-container input[type="text"] {
            padding: 15px;
            border-radius: 4px;
            border: 1px solid #666;
            font-size: 18px;
            width: 300px;
        }

        .search-container button {
            padding: 15px 20px;
            border: none;
            background-color: #fff;
            color: #666;
            border-radius: 4px;
            cursor: pointer;
            font-size: 18px;
            margin-left: 5px;
        }

        .search-container button:hover {
            background-color: #eee;
        }

        .container {
            display: flex;
            flex: 1;
        }

        nav {
            background-color: #333;
            color: #fff;
            padding: 15px;
            width: 250px;
            display: flex;
            flex-direction: column;
            overflow-y: auto;
        }

        .admin-info {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .admin-info img {
            border-radius: 50%;
            width: 50px;
            height: 50px;
            margin-right: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            display: block;
            padding: 10px;
            margin-bottom: 5px;
            border-radius: 4px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }

        .logout-link {
            margin-top: auto;
            display: block;
            color: #fff;
            text-align: center;
            padding: 10px;
            background-color: #555;
            border-radius: 4px;
            text-decoration: none;
        }

        .logout-link:hover {
            background-color: #444;
        }

        section {
            flex: 1;
            padding: 15px;
            background-color: #f4f4f4;
            overflow-y: auto;
            border-left: 1px solid #ddd;
        }

        footer {
            text-align: center;
            color: #fff;
            background-color: #5c5d5e;
            padding: 10px 0;
            margin-top: auto;
        }

        .policy-content {
            margin-bottom: 20px;
        }

        .policy-content h2 {
            margin-bottom: 10px;
        }

        ul.custom-list {
            margin: 10px 0;
        }

        ul.custom-list li {
            margin-bottom: 10px;
            font-size: 16px;
        }

        ul.custom-list li::before {
            color: #1781ea;
            font-size: 1.2em;
            margin-right: 8px;
        }

        .highlight {
            font-weight: bold;
            color: #0882fc;
        }

        .contact-info {
            margin-top: 10px;
        }

        .contact-info p {
            margin: 5px 0;
            font-size: 16px;
        }

        .contact-info a {
            color: #0080ff;
            text-decoration: underline;
        }

        hr {
            border: 0;
            border-top: 1px solid #ddd;
            margin: 20px 0;
        }

        .divider {
            border-bottom: 3px solid #797979;
            margin: 15px 0;
        }

        @media (max-width: 768px) {
            .search-container input[type="text"] {
                width: 200px;
            }

            .header-title {
                font-size: 28px;
            }

            nav {
                width: 100%;
                flex-direction: row;
                flex-wrap: wrap;
            }

            .container {
                flex-direction: column;
            }

            section {
                border-left: none;
                border-top: 1px solid #ddd;
            }

            .search-container {
                flex-direction: column;
                align-items: flex-start;
            }

            .search-container input[type="text"] {
                width: 100%;
                margin-bottom: 10px;
            }

            .search-container button {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="header-title">Apple Store</div>
        <div class="search-container">
            <input type="text" placeholder="Search...">
            <button>Search</button>
        </div>
    </header>
    <div class="container">
        <nav>
            <div class="admin-info">
                <img src="https://via.placeholder.com/50" alt="Admin Image">
                <div class="admin-name">
                    <p>Huynh Tan Dinh</p>
                    <p>Admin</p>
                </div>
            </div>
            <div class="divider"></div>
            <a href="Shipping_Policy.html">Shipping Policy</a>
            <a class="logout-link" href="#">Log Out</a>
        </nav>
        <section>
            <div class="policy-content">
                <h2>🔄 Return and Warranty Policy</h2>
                <p>&ensp;&ensp;&ensp; &#9733;
                    We offer a comprehensive return and warranty policy to ensure customer satisfaction. Products may be
                    returned or exchanged within the specified period under certain conditions. Please refer to the
                    guidelines below for more details.
                </p>
                <hr>
                <h3>🔍 Return Policy</h3>
                <ul class="custom-list">
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Eligibility:</strong> 
                        Returns are accepted within 30 days of
                        purchase with a valid receipt.
                    </p>
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Condition:</strong> 
                        Products must be in their original packaging
                        and condition.
                    </p>
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Process:</strong> 
                        Please contact customer service to initiate a
                        return.
                    </p>
                </ul>
                <hr>
                <h3>🔧 Warranty Policy</h3>
                <ul class="custom-list">
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Warranty Period:</strong> 
                        Most products come with a 1-year
                        warranty from the date of purchase.
                    </p>
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Coverage:</strong> 
                        Warranty covers manufacturing defects but not
                        accidental damage.
                    </p>
                    <p> &ensp;&ensp;&ensp; 📌 <strong>Claim Process:</strong> 
                        To make a warranty claim, please provide
                        proof of purchase and contact our support team.
                    </p>
                </ul>
                <hr>
                <h3>🚫 Non-Returnable Items</h3>
                <p>
                    &ensp;&ensp;&ensp;❗ Certain items, such as personalized products or opened software, are not eligible for return. Please check our return policy for a detailed list.
                </p>

                <hr>
                <h2>Contact Us 📞</h2>
                <div class="contact-info">
                    <p> &ensp;&ensp;&ensp;&ensp;&#128172; If you have any questions or need assistance with returns or
                        warranty claims, please contact us:</p>
                    <p> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 📧 Customer Service Email: <a
                            href="mailto:support@apple.com">support@apple.com</a>.</p>
                    <p> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 📞 Customer Service Phone: <a href="tel:+123456789">+123
                            456 789</a>.</p>
                    <p> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 🌐 Website: <a
                            href="https://www.apple.com">www.apple.com</a>.</p>
                    <p> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 🕒 Customer Service Hours: Mon - Fri, 9 AM - 6 PM.</p>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Apple Store. All rights reserved.</p>
    </footer>
</body>

</html>
