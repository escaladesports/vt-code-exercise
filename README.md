# VT Web Team - Coding Exercise - Instructions

Congratulations for being invited to complete this step! 🎉

During this process we will be providing an exercise for you to complete.

The expectation is that this can be completed within 4 days.

Questions are encouraged and expected, please submit to this address: `vtweb@victorytailgate.com`

---

## Exercise - Product/Inventory Management 📦

The web team received the request to build a product/inventory system. The goal is to allow users to create/edit/delete `categories`, and `products`.

A sample of the data was provided and can be found in the `src/data` folder. There you will find the following files:

`categories.json` - contains a list of all the product categories currently available.

`products.json` - contains a list of all the products categories currently available. There is a property in products that reference the data in the categories data set.

*The following can be found in: `src/data/products.json`

```js
{
    "categoryId": 2  // references the id of the category from the categories object
}
```

---

## Coding Exercise Tasks 📝

The exercise consists of 2 main tasks, which are described below. Each task contains a list of _main requirements_ and a list of _bonus points_. You should focus on first completing the _main requirements_ for each task, and then working on _bonus points_ if you choose.

### Setting Things Up 🔧

1. Create a new repository for your project.
2. Start a new React Project (feel free to use create app if you choose to set up the project).
3. If you choose, you can add Bootstrap, Material UI or any similar CSS framework to your project to speed up the UI developement.
4. Use the files found in `src/data` as your data source aka your tables. You may not modify the structure or file.

### Task 1 - Display Products and Categories

Allow users to view the following lists/tables:

1. A list of `products`
2. A list of `categories`

The data can be displayed either as a table or a list, it's up to you and what you think will be best.

**Main requirements:**

- Each list/table must display the following information:

    1. Products:

        - id
        - name
        - categoryId
        - category name
        - cost
        - price
        - quantity

    2. Categories:

        - id
        - name
        - total quantity of products for this category

- Users must be able to filter `products`.

**Bonus Points:**

- Add pagination to display the data.

### Task 2 - Add/Edit/Remove Products and Categories

Users must be able to add/edit/delete products and categories. You can choose how you would like to display this information.

**Main requirements:**

- Ability to add, update and delete `products` and `categories` separately.

**Bonus Points:**

- Store information in browser db

---

### Submiting the exercise 📬

1. Push the final version of your project.
2. Send us a link to your repo!

---

Questions are encouraged and expected, please submit to this address: `vtweb@victorytailgate.com`

_Congratulations!_ We look forward to reviewing your exercise and will reach out to you once we are done.
