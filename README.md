This component comes with no batteries included. 

## Props

| Property         | Type                     | Required? | Description                                              | Default               | 
| ---------------- | ------------------------ | -------- | -------------------------------------------------------- | --------------------- |
| items            | Object                   | &#10004; |                                                          |                       |
| selection        | Array                    |          |                                                          | []                    |
| allowDoubles     | Boolean                  |          |                                                          | false                 |
| onItemAdded      | Function                 |          | Called when an item is added to the cart.                | () => {}              |
| onItemRemoved    | Function                 |          | Called when an item is removed from the cart.            | () => {}              |
| onItemQtyChanged | Function                 |          | Called when an item's quantity changes.                  | () => {}              |
| onChange         | Function                 |          |                                                          | () => {}              |
| iterator         | Function                 |          |                                                          |                       |
| mainComponent    | React Component          |          | Optional custom container component.                     |                       |
| rowComponent     | React Component          |          | Optional custom row component.                           |                       |
| tableClassName   | String                   |          | The css class name to apply to the table element.        |                       |
| cartEmptyMessage | Node                     |          | The message shown when the cart is empty.                | 'The cart is empty. ' |

