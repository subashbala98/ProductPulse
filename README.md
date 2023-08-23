Landing Page Banner
------------------

![pic_1](https://github.com/subashbala98/ProductPulse/assets/72803159/eeb503dc-8812-44ac-9b16-85af2b14163f)


What we do (Overview of the product)
------------------------------------

![pic_2](https://github.com/subashbala98/ProductPulse/assets/72803159/5ecc175c-f2d2-43d8-8936-069f577d3f73)

Testimonials (carousel view)
----------------------------

![pic_3](https://github.com/subashbala98/ProductPulse/assets/72803159/98c41ad3-99d6-43c1-8c27-f5861c17b128)

Login/Register (In animation view)
--------------------------------

![pic_4](https://github.com/subashbala98/ProductPulse/assets/72803159/d706ac16-468d-436d-a81d-faad83792378)

To handle forgot password use cases it is displayed in Dialog.
-------------------------------------------------------------

1 . Send Otp to the email address
--------------------------------------------

![pic_5](https://github.com/subashbala98/ProductPulse/assets/72803159/d0931787-76b8-442d-af9a-893c7338c4c9)


2 . Verification (default interval is 30 seconds)
------------------------------------------------


![pic_6](https://github.com/subashbala98/ProductPulse/assets/72803159/f399afbb-913b-4e98-8d46-faabaa6baaf9)


3 . Change Password
-------------------


![pic_7](https://github.com/subashbala98/ProductPulse/assets/72803159/a96acb7c-aeba-4349-9579-a9272de88257)



Required Packages
----------------
1. Prime React and Icons

2. Tailwind
   
3. Formik

Important
---------
Handled all the form validation using Formik and Yup library just need to call an API in all submit buttons.
It is responsive on all devices.


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
