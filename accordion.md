## Installation

To install the accordion component, run the following command in the terminal:

```js
npm install @mojaui/accordion
```

## Usage

```js
import { Accordion } from "@mojaui/accordion";

export function Index() {
	return (
		<Accordion.Root>
			<Accordion>
				<Accordion.Trigger>
					<Accordion.TriggerIcon></Accordion.TriggerIcon>
					<Accordion.SubText></Accordion.SubText>
				</Accordion.Trigger>
				<Accordion.Content></Accordion.Content>
				<Accordion.Badge></Accordion.Badge>
			</Accordion>
			<Accordion>
				<Accordion.Trigger>
					<Accordion.TriggerIcon></Accordion.TriggerIcon>
				</Accordion.Trigger>
				<Accordion.Content></Accordion.Content>
				<Accordion.Badge></Accordion.Badge>
			</Accordion>
		</Accordion.Root>
	);
}
```

## Variant

Use the <mark style="background:lightBlue">variant</mark> prop to control the visual style of the Alert.

Variants: flat | Basic

```js
<>
	<Accordion.Root variant="flat">
		<Accordion>
			<Accordion.Trigger>
				<Accordion.TriggerIcon></Accordion.TriggerIcon>
			</Accordion.Trigger>
			<Accordion.Content></Accordion.Content>
			<Accordion.Badge></Accordion.Badge>
		</Accordion>
		<Accordion>
			<Accordion.Trigger>
				<Accordion.TriggerIcon></Accordion.TriggerIcon>
			</Accordion.Trigger>
			<Accordion.Content></Accordion.Content>
			<Accordion.Badge></Accordion.Badge>
		</Accordion>
	</Accordion.Root>
</>
```
