 E-Commerce Database Project

This project contains the Entity Relationship Diagram (ERD), data flow diagram, and SQL schema for an e-commerce platform database. 
The goal is to model a scalable, relational structure that supports product management, variations, attributes, and inventory.

# 📁 Project Structure
├── ecommerce.sql
├── ERD.png
├── DataFlow.png
└── README.md

#  Database Tables

The following tables were created:

- `brand` – Stores brand-related data
- `product_category` – Classifies products into categories
- `product` – General product details (name, brand, base price)
- `product_image` – Stores product image URLs
- `color` – Available color options
- `product_variation` – Links a product to its variations (color-based)
- `size_category` – Groups sizes into categories (e.g., clothing, shoes)
- `size_option` – Lists specific sizes (e.g., S, M, L, 42)
- `product_item` – Represents actual purchasable items with size and stock
- `attribute_category` – Groups product attributes (e.g., physical, technical)
- `attribute_type` – Defines types of attributes (text, number, etc.)
- `product_attribute` – Stores product-specific attributes like material or weight


#  Data Flow

The dataflow diagram shows how data moves between the entities in real-world scenarios. It includes:

- Admin workflow (adding products, variations, and inventory)
- Customer journey (browsing products, choosing size/color, buying items)


#  How to Use

1. Open MySQL Workbench or your preferred SQL tool.
2. Run the sql query file to create all necessary tables.
3. Use the ERD to understand table relationships and constraints.
4. Refer to the Data Flow diagram to grasp how data interacts in real use cases.


#  Notes

- All foreign key constraints are defined to maintain referential integrity.
- The schema is designed to be extensible — attributes and variations can scale easily.
- Indexes and sample data can be added based on project needs.


##  Contributors

- Bamidele Mutiat
- David Waihenya
- Sarah Wanbui


#  Questions?

Feel free to reach out via GitHub Issues or email for clarifications or improvements.
