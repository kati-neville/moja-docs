## Installation

To install the toast component, run the following command in the terminal:

```js
npm install @mojaui/toast
```

## Usage

```js
import { Toast } from "@mojaui/toast";

export function Index() {
	return (
		<>
			<Toast>
				<Toast.Icon></Toast.Icon>
				<Toast.Title></Toast.Title>
				<Toast.Description></Toast.Description>
				<Toast.Close></Toast.Close>
			</Toast>
		</>
	);
}
```

## Variant

Use the <mark>variant</mark> prop to control the visual style of the Callout.

Variants: Error | Success | Warning | Info

```js
<>
	<Toast variant="Success">
		<Toast.Icon></Toast.Icon>
		<Toast.Title></Toast.Title>
		<Toast.Description></Toast.Description>
		<Toast.Close></Toast.Close>
	</Toast>
</>
```
