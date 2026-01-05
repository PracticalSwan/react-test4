# React Render Lists Practice

This project demonstrates how to render lists in React using the `map()` method and reusable components.

## What I Learned

### 1. Rendering Lists with map()
- Used the JavaScript `map()` method to transform arrays of data into JSX elements
- Each list item needs a unique `key` prop (using the item's `id`)
- The `map()` method iterates over each item and returns a `<li>` element

### 2. Creating Reusable List Components
- Built a `List` component that accepts `items` and `category` as props
- The component can be reused for different types of lists (fruits, vegetables, etc.)
- Demonstrated conditional rendering using `&&` operator to show lists only when they have items

### 3. Working with Array Data
The project uses arrays of objects with the following structure:
```javascript
{id: 1, name: "apple", calories: 95}
```

### 4. Array Methods (Explored)
In the `List.jsx` component, I explored various array methods:
- **Sorting**: `sort()` for alphabetical and numeric sorting
- **Filtering**: `filter()` to create subsets based on conditions (e.g., low/high calorie items)

## Project Structure

- `App.jsx`: Defines the data arrays (fruits and vegetables) and passes them to the List component
- `List.jsx`: Reusable component that renders a list with a category heading

## Key Concepts

- **Props**: Passing data from parent to child components
- **Keys**: Unique identifiers for list items (required by React)
- **Conditional Rendering**: Only displaying lists when they contain items
- **Component Reusability**: Using the same List component for different data sets
