# Code Sample

Some of code sample written by me

### HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Fizz Buzz</title>

    <script>
      function fizzbuzz() {
        var display = document.getElementById("display");
        var displayHTML = "";
        for (i = 0; i < 100; i++) {
          displayHTML += "<p>" + i + "</p>";
        }
        display.innerHTML = displayHTML;
      }
    </script>
  </head>
  <body onload="fizzbuzz()">
    <div id="display"></div>
  </body>
</html>
```

### Python code

```#Amar's Super Cool Hello World Program
print('Hello world!')
```

[return to home page](./README.md)
