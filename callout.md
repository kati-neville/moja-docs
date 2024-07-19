## Installation

To install the callout component, run the following command in the terminal:

```js
npm install @mojaui/callout
```

## Usage

```js
import { Callout } from "@mojaui/callout";

export function Index() {
	return (
		<>
			<Callout>
				<Callout.Icon></Callout.Icon>
				<Callout.Content></Callout.Content>
				<Callout.Close></Callout.Close>
			</Callout>
		</>
	);
}
```

## Variant

Use the <mark style="background:lightBlue">variant</mark> prop to control the visual style of the Callout.

Variants: Error | Success | Warning | Info

```js
<>
	<Callout variant="Success">
		<Callout.Icon></Callout.Icon>
		<Callout.Content></Callout.Content>
		<Callout.Close></Callout.Close>
	</Callout>
</>
```
