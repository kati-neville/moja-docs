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
		<>
			<Button>
				Text
				<Button.Icon></Button.Icon>
			</Button>
		</>
	);
}
```

## Button Display

Use the <mark style="background:lightBlue">display</mark> prop to specify the display of the button

Position: Compact | Fluid
Default: Compact

```js
<>
	<Button display="Fluid">
		<Button.Icon></Button.Icon>
	</Button>
</>
```

## Variant

Use the <mark style="background:lightBlue">variant</mark> prop to control the visual style of the button.

Variants: Primary | Secondary | OutlineGray | White | OutlineLight | Dark | Danger | DangerOutline | DangerBorderless

default: Primary

```js
<>
	<Button variant="Primary">
		<Button.Icon></Button.Icon>
	</Button>
</>
```

## Button Icon Position

Use the <mark style="background:lightBlue">postion</mark> prop to control the position of the icon either to the left or right

Position: Left | Right

Default: Left

```js
<>
	<Button>
		<Button.Icon position="Left"></Button.Icon>
	</Button>
</>
```
