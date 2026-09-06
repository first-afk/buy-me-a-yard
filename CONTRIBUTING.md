# Contributing to Buy Me a Yard

First off, thank you for considering contributing to Buy Me a Yard!
Please read through these guidelines to ensure a smooth and collaborative process.

## Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct. We expect all contributors to maintain a welcoming, respectful, and inclusive environment. Harassment or unacceptable behavior will not be tolerated.

## How to Contribute

### Reporting Bugs

If you find a bug, please check the Issue Tracker to see if it has already been reported. If not, open a new issue and include:

A clear, descriptive title.

Steps to reproduce the bug.

Expected vs. actual behavior.

Information about your environment (OS, browser, Node.js version).

### Suggesting Enhancements

We welcome feature requests! When suggesting an enhancement:

Use a clear and descriptive title.

Explain why this enhancement would be useful to creators or supporters.

If possible, outline a potential technical approach.

#### Pull Requests

Ready to write some code? Great! Please follow this workflow:

  - Fork the Repository: Fork the repo and clone it locally.

  - Create a Branch: Create a branch for your feature or bug fix. Use a descriptive naming convention:

    - feature/add-new-yard-type

    - fix/paystack-webhook-validation

    - docs/update-readme

#### Commit Your Changes.

Write clear, concise commit messages. We prefer Conventional Commits:

  - feat: added mobile money payment option

  - fix: resolved RLS policy issue on transactions table

#### Write Tests. 
If you are adding new functionality, please add corresponding Jest tests.

Run the Test Suite: Ensure all existing and new tests pass by running npm run test.

Push and Open a PR: Push your branch to your fork and open a Pull Request against our main branch.

Code Review: The maintainers will review your PR. Be open to feedback and ready to make adjustments!

 ## Development Guidelines

TypeScript: 

We use TypeScript strictly. Please ensure your code is properly typed and avoids any where possible.

Styling:

Use Tailwind CSS for styling. Avoid writing custom CSS unless necessary.

Database: 

Any changes to the database schema must be discussed in an issue first, as it affects the Supabase RLS policies.

Formatting: 

We use Prettier. Please ensure your editor is set up to format on save, or run npm run format before committing.

Thank you for helping us build a better platform for African creators!
