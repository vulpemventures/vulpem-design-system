# VULPEM DESIGN SYSTEM
---

  - Typography
  - Colors
  - Spacing

#### Typography

The main fonts choosed for the design system are:
  - Open Sans
  - Playfair Display

```sh
$primary-font-sans: 'Open Sans', sans-serif;

$secondary-font-serif: 'Playfair Display', serif;
```

We choosed to use also this values for sizes:

```sh
$rem-values: (
	1: 0.75,
	2: 0.875,
	3: 1,
	4: 1.125,
	5: 1.25,
	6: 1.5,
	7: 1.75,
	8: 2,
	9: 2.25,
	10: 2.625,
	11: 3,
	12: 3.375,
	13: 3.75
	14: 4.25,
	15: 4.75,
);
```

#### Colors

For now we decided to implement only few basic colors to mantain the system simple and clear, until we decide the main purpose of the Design System.

The colors choosed are:

```sh
// COLOR LOGO ---------- /
$color-logo-black: #000;
$color-logo-white: #fff;
$color-logo-grey: #ccc;

// COLOR STATUS ---------- /
$color-error: #C23934;
$color-success: #45B86D;
$color-warning: #F6BA5D;
```


#### Spacing

After some tests, accordingly to our design experience, we decide to use a 8pt grid spacing system in our Design System. This is the best choice to keep the UI consistent and clear for the user.

---


# Development 

## Requirements

* Node > 8 / NPM > 5
* Editor Style: `Spaces 2`

## Usage
### Clone

`git clone https://github.com/vulpemventures/vulpem-design-system`

### Build

Install dependencies in the cloned folder
```
npm i
```

Import each new file created in the index.scss file
```
@import "./lib/variables/spacing.scss";
```

Run the build script in the same folder
```
npm run build
```

The compiled css are in the `./build` folder



### Todos

 - Add and style components
 - Review & improve
