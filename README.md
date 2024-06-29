# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Task Requirements

1. Users should be able to add, edit, and delete book records.
2. Each book record should contain the title, author, ISBN number, and publication date.
3. Users should be able to add, edit, and delete author records.
4. Each author record should contain the author's name, birth date, and a short biography.
5. All forms used in the dashboard should be validated using Formik.
6. The dashboard should have a clean and responsive design that is easy to use and navigate.

# How To Use

1. User need to enter UserName and Password in login page. Username --> atleast 5 chars (only alphabets) // Password --> only 6 digits (only numbers) [Note : Login page is will not verify the user // Dont know is it also the requirement for this task]
2. User can find there Books and Author list in dashboard + Application Info to know more about webpage design.
3. User can add new Author and Books (Menu Button --> Add Author / Add Book button)
4. User can able to edit / add Book and author Detail [Formik Validations are done]
5. User can able to delete the exisiting data.
6. All CRUD operations are perform using Axios fetch with Mock API
