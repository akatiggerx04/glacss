# Glacss

Glacss is a lightweight and easy-to-use CSS mini framework that allows you to add glass effect to any HTML element. Whether you are a beginner or an experienced developer, Glacss is designed to simplify the process of creating glassy elements, without requiring any complex CSS or JavaScript code.

## Getting Started

To get started with Glacss, simply download the [glacss.min.css](https://github.com/akatiggerx04/glacss/blob/main/glacss.min.css) file and include it in your HTML file:

```html
<head>
  <link rel="stylesheet" href="path/to/glacss.min.css">
</head>
```

Alternatively, you can include Glacss via a CDN:

```html
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/akatiggerx04/glacss/glacss.min.css">
</head>
```

## Usage

To add the glass effect to an HTML element, simply add the `.glass` class to it:

```html
<div class="glass">This is a glassy element.</div>
```

Glacss offers additional classes that enable you to further customize the effect.

|**Classname**|**Effect**|
|--|--|
|`glass-dark`|A Dark Glass Effect|
|**Border Radius Classname**|Default value: **15px**|
|`glass-rounded-none`|0|
|`glass-rounded-sm`|0.125rem|
|`glass-rounded-md`|0.375rem|
|`glass-rounded-lg`|0.5rem|
|`glass-rounded-xl`|0.75rem|
|`glass-rounded-2xl`|1rem|
|`glass-rounded-3xl`|1.5rem|
|`glass-rounded-full`|50%|

You can also customize the appearance of the glass effect by overriding the default CSS variables. Here are the available CSS variables:

```css
/** These are the default values. **/
:root {
    --glacss-bg: rgba(255, 255, 255, 0.2);
    --glacss-bg-dark: rgba(0, 0, 0, 0.2);
    --glacss-blur: 4px;
    --glacss-outline: 1px;
    --glacss-outline-color: rgba(255, 255, 255, 0.3);
    --glacss-outline-color-dark: rgba(50, 50, 50, 0.1);
    --glacss-border-radius: 15px;
}
```

## Examples

Here are some examples of how you can use **glacss** to add glass effect to your HTML elements:

### Glassified `div`

```html
<div class="glass">
    <p>This is a glassified div.</p>
</div>
```

![example](https://i.ibb.co/sVYs7Vx/Screenshot-from-2023-02-26-19-06-32.png)

### Glassified `button`

```html
<button class="glass glass-rounded-lg">This is a glassy button</button>
```

![example](https://i.ibb.co/7rngY0f/1.png)

### Glassified Dark `div`

```html
<div class="glass-dark">
    <p>This is a glassified div.</p>
</div>
```

![example](https://i.ibb.co/5RhmbYv/2.png)

*Please note that margin and padding has been applied to some of these examples.*

## Contributing

If you'd like to contribute to **glacss**, feel free to submit a pull request or open an issue on our [GitHub repository](https://github.com/akatiggerx04/glacss). We welcome any feedback, suggestions, or bug reports!

## License

Glacss is licensed under the [Affero General Public License (AGPL)](https://www.gnu.org/licenses/agpl-3.0.en.html). This means that anyone who uses, modifies, or distributes Glacss must make the full source code available under the same AGPL license.

You are free to use, modify, and distribute Glacss as long as you comply with the terms of the AGPL. However, if you plan to use Glacss in a commercial product, please note that the AGPL may require you to make the full source code of your product available to your users.

For more information on the AGPL, please see the [GNU website](https://www.gnu.org/licenses/why-affero-gpl.en.html).