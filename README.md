# Alpine.js E-Commerce Project

## What’s This About?

Hey there! This is a e-commerce web app built with Alpine.js. It lets you browse products, check out details in a modal, and filter/sort. All the data comes from an API, and it’s designed to look great on any device.

## What’s Included

- **Product Grid:** See a bunch of product cards with images, titles, prices, and categories.
- **Product Details Modal:** Click on a product to pop open a modal with all the juicy details – title, description, image, price, category, rating, and reviews.
- **Filtering:** Filter products by category – easy peasy.
- **Sorting:** Sort products by price (low to high or high to low).
- **Loading States:** You’ll see loading indicators when data is being fetched.
- **Persistence:** Your filters and sorting choices stick around even if you close and reopen the modal.

## File Breakdown

- **index.html:** The main HTML file.
- **styles.css:** All the styles for making things look good.
- **app.js:** Handles fetching data, filtering, sorting, and modals.
- **components/**
  - **Filter.html:** Lets you filter products by category.
  - **Header.html:** The top navigation/header.
  - **ProductCard.html:** Shows individual product cards.
  - **ProductDetail.html:** The detailed view in the modal.
  - **ProductList.html:** Lists products with search, filter, and sort options.
  - **Sort.html:** Sorts products by price.

## Getting Started

1. **Clone the Repo:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Go to the Project Directory:**

   ```bash
   cd your-repository
   ```

3. **Open `index.html`:**

   Open `index.html` in your browser or use a local server to serve the files.

## How to Use It

1. **Filtering:** Pick a category in the filter component to see products from that category.
2. **Sorting:** Use the sort component to arrange products by price.
3. **Product Details:** Click a product card to view details in a modal.
4. **Resetting:** Hit the reset button to go back to default settings without a page refresh.
5. **Persistence:** Your filter and sort choices will stick around even after you close and reopen the product details modal.

## Tech Stack

- **Alpine.js:** The lightweight framework for interactive stuff.
- **HTML/CSS:** For building and styling the app.

Feel free to play around and make it your own!
