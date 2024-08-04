<p align="center">
  <a href="https://getbootstrap.com/" target="_blank">
    <img src="https://i.imgur.com/UURHBWT.png" width="400" height="200">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/downloads-+500M-5555ff" alt="Total Downloads">
  <img src="https://img.shields.io/badge/version-v5-green" alt="TLatest Stable Version">
  <img src="https://img.shields.io/badge/license-MIT-yellow" alt="License">
</p>

# Bootstrap Documentation 🌐

### How to use it in the project?

It's easy, the 3 most popular ways to use it are:

a) Importing the **URL** inside of the head tag: 
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```

b) Adding the **script** under the body tag:
```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```

c) Or can be **installed** with Node.js in a framework like Angular, React or Vue, for example:
```
npm install bootstrap@5.3.3
```
# What are the principal funcionalities? 💎

Give us the posibility of use a simplify code and save working hours because every item contains a basic design and help us to make a responsive code for any device.

Here you can find examples of Boostrap buttons, lists, dropdowns, etc. => https://getbootstrap.com/docs/5.3/examples/

# How can I get started? ⬇️

Once verified that Boostrap is working in our project, we can start using it in the following way:
```
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Type of input -->
    <div class="input-group mb-3">
      <span class="input-group-text" id="basic-addon1">@</span>
      <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
    </div>

    <!-- Alerts -->
    <div class="alert alert-primary" role="alert">
      A simple primary alert—check it out!
    </div>

    <!-- Dropdowns -->
    <div class="dropdown">
      <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
        Dropdown button
      </button>
      <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Action</a></li>
        <li><a class="dropdown-item" href="#">Another action</a></li>
        <li><a class="dropdown-item" href="#">Something else here</a></li>
      </ul>
    </div>

    <!-- Progress Bar -->
    <div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100">
      <div class="progress-bar" style="width: 0%"></div>
    </div>
  </body>
</html>
```
As you can see, it's easy to make an element without using CSS, only with the magic of HTML and Boostrap.

And you can also include Popper and our JS separately. If you don’t plan to use dropdowns, popovers, or tooltips, save some kilobytes by not including Popper.
```
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>
```
