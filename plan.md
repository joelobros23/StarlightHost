# Project Plan: StarlightHost

**Description:** A simplified web hosting platform built with Ruby on Rails, focusing on ease of use and essential features.


## Development Goals

- [ ] Configure Tailwind CSS by running `rails tailwindcss:install` and update the `app/javascript/application.js` file.
- [ ] Add model validations to the User model to require a username and email.
- [ ] Add model validations to the Domain model to ensure the name, plan and status are present. Also add a unique index on the domain name.
- [ ] Customize the Domain model to include enum for plan (e.g., 'basic', 'standard', 'premium') and status (e.g., 'pending', 'active', 'suspended').
- [ ] Modify the domains controller to ensure that only the owner can view, edit, or delete a domain.
- [ ] Implement an admin panel (using a separate controller and views) to manage all domains and users. Restrict access to admin panel using role-based authentication (e.g., using a boolean `admin` attribute on the User model managed via Devise).
- [ ] Customize the Devise views (e.g., registration and login forms) to use Tailwind CSS for styling.
- [ ] Add a dashboard view that displays the current user's domains, plans, and associated statuses.
- [ ] Implement a simple payment gateway integration (e.g., Stripe) for upgrading or renewing plans.
- [ ] Include a maintenance mode feature that allows the admin to disable access to the site.
