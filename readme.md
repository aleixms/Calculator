# Minimal Calculator

This is a simple HTML code for a minimal calculator interface. The calculator interface consists of buttons representing numbers, operators, and control functions. The interface allows users to perform basic arithmetic operations.

## Usage

To use the calculator interface, open the HTML file in a web browser. The interface will be displayed, and you can interact with the buttons to perform calculations.


### HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Minimal Calculator</title>
</head>

<body>
    <h1>Calculator Interface</h1>
    <div>
      <p>0.</p>
      <button>7</button>
      <button>8</button>
      <button>9</button>
      <button>x</button>
      <button>4</button>
      <button>5</button>
      <button>6</button>
      <button>/</button>
      <button>1</button>
      <button>2</button>
      <button>3</button>
      <button>+</button>
      <button>.</button>
      <button>0</button>
      <button>%</button>
      <button>_</button>
      <button class="clear">AC</button>
      <button class="submit">=</button>
    </div>
</body>
</html>

## CSS Styling

The following CSS code in the style.css file is used to style the calculator interface:

div {
  border: 2px solid gray;
  font-size: 0;
}

button {
  width: 25%;
  height: 35px;
}

.clear {
  width: 50%;
  background-color: orange;
}

.submit {
  width: 50%;
  background-color: lightgreen;
}

p {
  text-align: right;
  font-size: 15px;
}

The CSS styling defines the appearance of the calculator interface, including the border, button sizes, colors, and alignment of text.

## Notes

This is a minimal calculator interface and does not contain any actual functionality for performing calculations. It serves as a starting point for further development or customization.