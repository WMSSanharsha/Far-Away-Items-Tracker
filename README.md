# Far Away Packing List App

This project is a simple and interactive packing list application built with React. It allows users to add items to their packing list, manage the packed status, delete individual items, and clear the entire list. The app also provides a summary of the total items and the percentage of packed items.

- Live Preview - https://far-away-item-tracker.netlify.app/


## Features

- **Add Items**: Users can add items to the packing list with a description and quantity.
- **Mark as Packed/Unpacked**: Each item can be marked as packed or unpacked, and the status is reflected in the list.
- **Delete Items**: Individual items can be removed from the list.
- **Sort Items**: Items can be sorted by:
  - Input order
  - Description
  - Packed status
- **Clear List**: Users can clear all the items in the list with a confirmation prompt.
- **Packing Stats**: The app displays a summary of how many items are packed and the percentage of items packed.

## Components

### `App`
The main component that holds the state of the items and manages the flow of the app. It uses several child components to build the UI:
- `Logo`
- `Form`
- `PackingList`
- `Stats`

### `Logo`
A simple component displaying the app logo and name: "🌴Far Away 💼".

### `Form`
A form that allows users to add items to the packing list. It takes a description and quantity as input, and submits the item to be added to the list.

### `PackingList`
This component displays the list of added items. Users can delete items, toggle their packed status, and sort the list by different criteria.

### `Item`
Each item in the packing list is rendered as a separate `Item` component with options to mark it as packed/unpacked or delete it.

### `Stats`
Displays the total number of items and the percentage of items that have been packed. If all items are packed, a message indicating readiness to go is displayed.

## Usage

1. **Add an item**: Fill out the form with the item description and quantity, and click "Add".
2. **Mark an item as packed**: Click the checkbox next to an item to mark it as packed or unpacked.
3. **Sort the list**: Use the dropdown to sort the items by input order, description, or packed status.
4. **Clear the list**: Click "Clear List" to remove all items from the packing list.

![Screenshot 2024-09-29 192457](https://github.com/user-attachments/assets/5299c6ac-ef8e-4373-a046-cf4f64609233)
![Screenshot 2024-09-29 192223](https://github.com/user-attachments/assets/21bdb3f5-7ef8-44c1-83cb-7cbb887b1665)
![Screenshot 2024-09-29 192202](https://github.com/user-attachments/assets/394ea79c-694c-40cf-aa9a-5508e1b527b8)
![Screenshot 2024-09-29 120749](https://github.com/user-attachments/assets/78eabec2-1d0c-476f-bb61-fdda0aeb74cb)
![Screenshot 2024-09-29 115014](https://github.com/user-attachments/assets/0491849e-02b1-4747-85d3-98308c0343a5)
![Screenshot 2024-09-28 223157](https://github.com/user-attachments/assets/223bbb1a-4965-4d4f-8c97-d66bde51f831)

- Build By Learning Through Jonas React Course Project 
