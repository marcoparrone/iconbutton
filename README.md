# iconbutton

 A Material React component implemeting a button with an icon.

## Installation

```sh
npm install @marcoparrone/iconbutton
```

## Usage

The IconButton React component accepts there properties:

 * label: a short description of the purpose of the button
 * icon: the Material icon name, see https://material.io/resources/icons/ for the full collection
 * callback: the function to call when the button is pressed


```js
import IconButton from '@marcoparrone/iconbutton';

// ...

<IconButton label="Add a bookmark" icon='add' callback={event => this.props.addNode(this.props.id)} />

```
