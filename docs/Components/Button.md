---
sidebar_position: 3
---

## Installation

To install the button component, run the following command in the terminal:

```js
npm install @mojaui/button
```

## Usage

```js
import { Button } from "@mojaui/button";

export function Index() {
	return (
		<Button>
			Text
			<Button.Icon></Button.Icon>
		</Button>
	);
}
```

## Button Display

Use the <mark>display</mark> prop to specify the display of the button

Position: Compact | Fluid
Default: Compact

```js
<Button display="Fluid">
	<Button.Icon></Button.Icon>
</Button>
```

## Variant

Use the <mark >variant</mark> prop to control the visual style of the button.

Variants: Primary | Secondary | OutlineGray | White | OutlineLight | Dark | Danger | DangerOutline | DangerBorderless

Default: Primary

```js
<Button variant="Primary">
	<Button.Icon></Button.Icon>
</Button>
```

## Button Icon Position

Use the <mark >postion</mark> prop to control the position of the icon either to the left or right

Position: Left | Right

Default: Left

```js
<Button>
	<Button.Icon position="Left"></Button.Icon>
</Button>
```

## States

There are several states associated with this component which can all be styled differently by using the data-state avariable

Position: default | hover | focus | focusActive | disabled
