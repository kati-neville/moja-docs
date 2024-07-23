---
sidebar_position: 2
---

## Installation

To install the toast component, run the following command in the terminal:

```js
npm install @mojaui/alert
```

## Usage

```js
import { Alert } from "@mojaui/alert";

export function Index() {
	return (
		<Alert>
			<Alert.Icon></Alert.Icon>
			<Alert.Content></Alert.Content>
			<Alert.Button></Alert.Button>
			<Alert.Close></Alert.Close>
		</Alert>
	);
}
```

## Variant

Use the <mark>variant</mark> prop to control the visual style of the Alert.

Variants: Primary | "

```js
<Alert variant="Success">
	<Alert.Icon></Alert.Icon>
	<Alert.Content></Alert.Content>
	<Alert.Button></Alert.Button>
	<Alert.Close></Alert.Close>
</Alert>
```
