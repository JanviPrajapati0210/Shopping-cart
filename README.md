📌 E-Commerce Order Processor – Python (CLI)

- A menu-driven Python CLI application for processing e-commerce orders.
- Users can browse a catalog, manage a shopping cart, generate bill summaries, and export invoices with GST and discount applied.

🚀 Features (Bullet-Point Format)

- View available products with prices
- Add items to shopping cart
- View all selected items with subtotal
- Update item quantity in the cart
- Remove items from the cart
- Automatic billing calculation:
  Subtotal:
    10% discount if subtotal > ₹1000
    GST @ 18%
    Generate full bill summary
- Save invoice as a UTF-8 encoded text file (.txt) with correct ₹ symbol.
- Fully menu-driven interface until user chooses Exit.
- Error handling for invalid selections and inputs.

💰 Billing Rules:

Category         	Calculation
Subtotal	       Sum of (price × quantity)
Discount	       10% if subtotal > ₹1000
GST            	 18% applied after discount
Final Amount	   subtotal – discount + GST


🛠 Tech Stack

Language: Python
Interface: CLI (Command Line Interface)
File Format: UTF-8 encoded .txt invoice
