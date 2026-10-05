# Day 8 — JavaScript Product Category Filter

## What I Learned

- JavaScript adds behavior and logic to a webpage.
- HTML provides structure and content.
- CSS controls appearance and layout.
- JavaScript can select HTML elements and change their behavior or appearance.
- `data-category` can store category information on an HTML element.
- `document.querySelectorAll()` selects multiple matching elements.
- `forEach()` processes each selected element one by one.
- `if` conditions allow JavaScript to make decisions.
- `style.display` can show or hide elements.

## What I Built

I added a product category filter to my SCNC B2B clothing website.

The filter includes:

- All
- Casual
- Formal

Products are assigned categories using `data-category`.

JavaScript checks each product's category and displays only the products matching the selected category.

## JavaScript Logic

```javascript
function filterProducts(category) {
  const products = document.querySelectorAll('.product');

  products.forEach(product => {
    if (category === 'All' || product.dataset.category === category) {
      product.style.display = 'block';
    } else {
      product.style.display = 'none';
    }
  });
}
```

## What I Practiced

- DOM element selection
- `querySelectorAll()`
- `forEach()`
- `if` conditions
- `dataset`
- `style.display`
- Connecting HTML buttons to JavaScript functions

## Testing

I tested all three filters:

- **All** → shows all products
- **Casual** → shows T-Shirt and Jeans
- **Formal** → shows Formal Shirts and Formal Pants

## Learning Outcome

I can now create a basic interactive webpage feature using JavaScript and connect JavaScript logic to existing HTML elements.

## Skill Status

JavaScript basics — Applied  
DOM selection — Practiced  
Conditions — Applied  
Loops with `forEach()` — Applied  
Product filtering — Built and Tested