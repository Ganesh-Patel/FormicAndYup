# Formik & Yup Form with Tailwind CSS

This project demonstrates how to build a fully functional and styled form using **Formik** and **Yup** in a React.js application, styled with **Tailwind CSS**. The form includes validation and features such as resetting input fields after submission, handling different input types like email, password, date of birth, etc., and responsive design.

## Features

- Form validation using **Formik** and **Yup**.
- Fields for name, email, password, confirm password, gender, and date of birth.
- Validation for email format and password matching.
- Reset form fields to their initial state upon submission.
- Responsive design using **Tailwind CSS**, optimized for mobile devices.

## Technologies Used

- **React**: Frontend JavaScript library for building user interfaces.
- **Formik**: A React library for form management and validation.
- **Yup**: A schema builder for form validation.
- **Tailwind CSS**: A utility-first CSS framework for responsive design.
- **Vite**: A fast frontend build tool.

## Installation and Setup

To run this project locally, follow these steps:

### Prerequisites

Make sure you have the following installed on your system:
- **Node.js** (v14+)
- **npm** or **yarn**

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/formik-yup-tailwind-form.git
2. Navigate to the project directory:
    ```bash
    cd formik-yup-tailwind-form
3. Install dependencies:
    ```bash
    npm install
4. Run the development server:
    ```bash
    npm run dev


## Tailwind CSS Setup

This project is styled using Tailwind CSS. If Tailwind CSS is not working properly, ensure the following setup in your project:

### Steps

1. Install Tailwind CSS and its dependencies:

    ```bash
    npm install tailwindcss@latest postcss@latest autoprefixer@latest
    ```

2. Initialize Tailwind CSS:

    ```bash
    npx tailwindcss init
    ```

3. Configure `tailwind.config.js`:

    ```js
    /** @type {import('tailwindcss').Config} */
    export default {
      content: [
        './index.html',
        './src/**/*.{js,ts,jsx,tsx}',
      ],
      theme: {
        extend: {},
      },
      plugins: [],
    };
    ```

4. Add Tailwind to your `index.css`:

    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

5. Ensure PostCSS is configured in `postcss.config.js`:

    ```js
    module.exports = {
      plugins: {
        tailwindcss: {},
        autoprefixer: {},
      },
    };
    ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.