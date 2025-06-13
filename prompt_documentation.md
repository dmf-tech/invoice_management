# InvoiceFlow Development Prompts

### Project Initialization
```markdown
I want you to create a responsive invoice management website using html and tailwind css. 

These are the necessary components needed:
1. Navigation bar with text-based logo, 5 button menus( Dashboard, Invoices, Clients, Reports, Settings), a "New invoice" button, and a humburger menu for smaller screens.
2. A Dashboard summary cotanining the 3 summary cards of key metrics with 2 quick action buttons (View all invoices, Create new invoice)
3. Outstanding invoices list/table section that has invoice entry and information. This also include a filter and sorting functions
4. Footer with copy right information, quick links, and placeholder for support/contact info.

I want you to make the code structured and easy to maintain. Make it professional, elegant, and production ready. I want it robust and clean code. Generate all this code on a single html file. You should include the Tailwind CSS via CDN in the <head> section of that file. The design (nav bar, dashboard, invoice list, footer) should be fully present in that single file.
```

### Navigation Bar
```markdown
In the navigation bar, place all menu links and buttons on the right side. Ensure the layout is responsive and visually aligned. Add simple JavaScript functions to simulate basic button interactions so that I can verify that the buttons appear functional. Keep everything HTML, Tailwind CSS (via CDN), and JavaScript within a single HTML file, as the entire website must be contained in one document.
```

### Navigation Bar Implementation
```markdown
Now, improve the dashboard and the outstanding invoices section. Populate the invoice table with at least 5 sample invoices that align with the dashboard's key metrics. Ensure the data is consistent. Add basic JavaScript for Sort and Filter controls, such as sorting the table or filtering entries. Also, make sure the "View All Invoices" and "Create New Invoice" buttons are working as intended. Again please keep all HTML, CSS (Tailwind CDN), and JavaScript in a single HTML file.
```

### Footer Improvements
```markdown
Improve the footer to make it look clean, professional, and consistent with the product name "InvoiceFlow" used in the navbar. The footer should be compact, not overly spread out, since it only includes quick links and support/contact information. Ensure the text is clearly readable with appropriate spacing, font size, and color contrast. The layout should be fully responsive and look well-aligned on both desktop and small screens, with the content stacking vertically on smaller devices if needed. Keep everything within a single HTML file.
```

### Hamburger Menu and Footer Responsiveness
```markdown
Please improve the hamburger menu on small screens. Add appropriate icons to indicate the menu clearly. Ensure the text remains readable and consistent with the rest of the navigation.

For the footer, it's already great on larger screens, but on small screens it becomes too long. Please adjust the layout so it's more compact on smaller devices, without affecting the appearance on larger screens. Keep the quick links and support section readable and well-aligned.
```

### Footer Layout and Responsiveness
```markdown
On small screens, update the footer layout so that the Quick Links and Support sections are displayed side by side, and each section has its content arranged in a 2x2 grid layout. This means the links should appear in two columns per section (e.g., About/Terms and Privacy/Docs for Quick Links). Keep the layout compact and easy to read. The appearance on larger screens should remain unchanged.
```

### Invoice Table Structure
```markdown
For the invoice table, improve the visual design to make it more appealing while keeping it clear and easy to read. Ensure the columns and rows are well-defined, spacing is consistent, and all text remains readable. Keep the enhancements minimal the goal is a cleaner and more polished look without changing the structure or functionality.
```

### Filter and Sort Implementation
```markdown
Everything is already working as intended, including the filter and sort buttons. Please just enhance the UI slightly to improve usability and appearance. Focus on simple UI/UX improvements to make the layout cleaner and more user-friendly.
```