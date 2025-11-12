

**📘 Overview**

The WordPress Inventory Management System is a simple web-based project built entirely with WordPress and free plugins.
It provides a complete CRUD (Create, Read, Update, Delete) functionality to manage inventory items from the frontend — with separate pages for each operation.

This project is suitable for internship submissions, college projects, or beginners learning WordPress form and data management using free tools.

**🧩 Features**

✅ Add Inventory Items – Add new items through a frontend form
👀 View Inventory Items – Display all stored inventory data in a table format
✏️ Update Inventory Items – Edit or update existing item details
❌ Delete Inventory Items – Remove any item from the list
💾 Fully Database-Driven – Data stored automatically in WordPress database
🌐 100% Free Setup – No premium plugins or paid hosting required

**⚙️ Tools & Technologies**
Tool	Description
WordPress	CMS platform used for the project
Forminator Plugin	Used for building forms and CRUD operations
InfinityFree Hosting	Free web hosting platform
Softaculous Installer	Used to install WordPress easily
MySQL (via WordPress)	Database for storing inventory data
🏗️ Setup Instructions
1️⃣ Install WordPress (Free Hosting)

Go to https://www.infinityfree.net/

Create an account and subdomain (e.g. inventory.epizy.com)

Go to Softaculous App Installer → WordPress → Install

Login to your WordPress Dashboard (yourdomain/wp-admin)

**2️⃣ Install Required Plugin**

In Dashboard → Plugins → Add New

Search for “Forminator”

Click Install Now → Activate

3️⃣ Create CRUD Pages
🟢 Add Inventory Page

Go to Forminator → Forms → Create New Form

Add fields:

Item Name (Text)

Quantity (Number)

Price (Number)

Category (Text)

Save and Publish

Copy the form’s shortcode, e.g.:

[forminator_form id="12"]


Create a new WordPress Page named Add Inventory

Paste the shortcode → Publish the page.

👀 View Inventory Page

Create a new page named View Inventory

Add shortcode:

[forminator_entries form_id="12"]


This displays a table of all submitted inventory items.

You can add “Edit” and “Delete” buttons using Forminator’s entry actions.

✏️ Update Inventory Page

Duplicate the Add Inventory form.

Enable “Prefill Data” and allow editing existing submissions.

Create a page named Update Inventory and paste the form shortcode.

Link “Update” buttons from the View page to this page:

yoursite.com/update-inventory/?id=entryID

❌ Delete Function

Enable Delete action in Forminator’s entry settings.

When “Delete” is clicked, the item will be removed from the database and table.

🧾 Project Structure
WordPress Inventory Management/
│
├── wp-content/
│   ├── plugins/
│   │   └── formninator/
│   └── themes/
│
├── Pages/
│   ├── Add Inventory
│   ├── View Inventory
│   ├── Update Inventory
│
└── README.md

💡 How It Works

The Add Inventory page collects data via a Forminator form.

Each entry is stored in the WordPress database.

The View Inventory page displays all entries in a table.

Each row includes Update and Delete buttons.

The Update Inventory page allows editing of selected records.

The Delete button permanently removes the record.
**
📸 Demo Flow**

User visits Add Inventory page and submits an item.

The item appears in the View Inventory list.

Clicking Update opens the edit form pre-filled with item details.

Clicking Delete removes the item instantly.

**🧑‍💻 Developer**

Name: kanya
Role: WordPress Developer (Internship Project)
Tools Used: WordPress, Forminator Plugin, InfinityFree Hosting

**🏁 Conclusion**

This WordPress CRUD project demonstrates how to build a functional inventory management system using only free plugins and WordPress’s built-in capabilities.
It’s easy to set up, beginner-friendly, and ideal for showcasing practical knowledge of WordPress database and form handling.
