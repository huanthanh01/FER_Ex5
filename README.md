# Exercise 5 - Bootstrap 5 (Exercises 1, 2, 3)

## Code index.html (Bài 1, 2, 3)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Bootstrap 5 Grid</title>
    <!-- Bootstrap CSS -->
    <link
      rel="stylesheet"
      href="node_modules/bootstrap/dist/css/bootstrap.min.css"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <div class="container border mt-4 p-0">
      <div class="bg-secondary text-white p-4">
        <h2>Let's test the grid!</h2>
      </div>

      <div class="p-4">
        <ul class="nav mb-4">
          <li class="nav-item">
            <a class="nav-link active" href="#">Active</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Disabled</a>
          </li>
        </ul>

        <div class="row mt-4">
          <div class="col-8">First col</div>
          <div class="col-4">Second col</div>
        </div>

        <div class="row mt-3">
          <div class="col">col</div>
          <div class="col">col</div>
          <div class="col">col</div>
        </div>

        <div class="row mt-3">
          <div class="col">col</div>
          <div class="col">col</div>
          <div class="col">col</div>
          <div class="col">col</div>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col text-center py-2 footer-bar">
          <h4 class="mb-0">Created by ABC!</h4>
        </div>
      </div>
    </div>

    <!-- Exercise 2 -->
    <div class="container bg-dark text-white mt-4 p-4 text-center">
      <h2 class="mb-4">My First Bootstrap Page</h2>
      <div class="row justify-content-center">
        <div class="col-auto">
          <img src="images/html5.png" alt="HTML5" class="logo-img" />
        </div>
        <div class="col-auto">
          <img src="images/css3.png" alt="CSS3" class="logo-img" />
        </div>
        <div class="col-auto">
          <img src="images/bootstrap.png" alt="Bootstrap" class="logo-img" />
        </div>
      </div>
    </div>

    <!-- jQuery -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <!-- Popper.js -->
    <script src="node_modules/@popperjs/core/dist/umd/popper.min.js"></script>
    <!-- Bootstrap JS -->
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
  </body>
</html>
```
