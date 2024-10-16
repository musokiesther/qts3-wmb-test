# QuickStatements 3.0 - Home Page Documentation

## Introduction to QuickStatements 3.0

Welcome to the QuickStatements 3.0 homepage! This platform is designed for seamless access to batch processing functionalities and user interactions. Here’s a comprehensive guide to the essential features available on the homepage.

---

### Key Features

**1. New Batch Button**
- **Overview**: Initiates the process to create a new batch of statements.
- **Position**: Found in the main content section.
- **Appearance**: Styled with a vibrant blue color scheme (`background-color: blue; color: white`).
- **Function**: Directs users to the "New batch" creation form upon clicking.

**2. Batch Search Form**
- **Overview**: Enables users to find specific batches using the batch ID.
- **Input Fields**:
  - **Batch ID** (required): Numeric field for entering the batch ID.
- **Function**: Submitting the form with the "See batch details" button retrieves the relevant batch information.

**3. User Batch Search Form**
- **Overview**: Allows searching for batches created by a particular user via username.
- **Input Fields**:
  - **Username** (required): Text field for entering the desired username.
- **Function**: Clicking the "See batches by user" button submits the form and displays batches related to that user.

---

### Navigation Options

The navigation menu includes links to essential features:

- **QuickStatements 3.0**: Returns to the homepage.
- **New Batch**: Direct access to the batch creation page.
- **Last Batches**: Placeholder for accessing recently created batches (no current link).
- **GitHub Repository**: Link to the [QuickStatements 3.0 GitHub repository](https://github.com/WikiMovimentoBrasil/quickstatements3) for codebase access.

**For Authenticated Users:**
- **User**: Displays the logged-in username.
- **Your Last Batches**: Links to the most recent batches created by the user.

**For Anonymous Users:**
- **Login**: A link for user login access.

---

### Creating a Batch

The "New batch" page enables users to compile batches of statements. Here’s the procedure:

**Input Fields:**

1. **Command Format**:
   - Choose between:
     - `V1`: Command-line format.
     - `CSV`: CSV file format.

2. **Batch Name**:
   - Optional field for entering a custom name.

3. **Commands**:
   - Large text area for entering commands or data.
   - Supports both pasting and manual input.

**Submit Button**:
- The "Execute" button processes the batch based on the user’s input.

**Error Notification**:
- Any input errors will prompt a red error message at the top of the form for user awareness.

---

### Technical Details

**CSS and HTMX Integration**
- **CSS**: Utilizes the Pico CSS framework for a clean, responsive design, supplemented by custom styles for buttons and other elements.
- **HTMX**: Implements HTMX for dynamic features like form submissions and content updates without full-page reloads.

---

This summary encapsulates the features of the QuickStatements 3.0 homepage, aimed at enhancing batch data processing for users efficiently.
