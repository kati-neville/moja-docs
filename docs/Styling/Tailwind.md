---
sidebar_position: 1
---

[Tailwind CSS](https://tailwindcss.com) is a utility-first CSS framework providing a flexible way to style your components.

## Styling with Tailwind CSS

To style a component or a part of a component, apply the utility classes directly to the components to the <mark>class</mark> or <mark>className</mark>

```js
<Button display="Fluid" className="px-4 bg-red-300/40">
	<Button.Icon className="w-3 h-3"></Button.Icon>
</Button>
```

To style a particular state of the component, you can make use of the data-state variable

```js
<Button display="Fluid" className="px-4 data-[state=focus]:bg-gray-100">
	<Button.Icon className="w-3 h-3"></Button.Icon>
</Button>
```
