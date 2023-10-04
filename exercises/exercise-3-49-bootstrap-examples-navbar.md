# Exercise 3-49

In this exercise, you will add a Bootstrap navbar to your bootstrap-examples project. A Bootstrap navbar is a responsive menu that appears full-width in larger devices and collapses into a "hamburger" icon and dropdown on smaller devices.

## Bootstrap Navbar

1.  **Open** the folder named `bootstrap-examples`
    in Visual Studio Code.
1.  Replace navigation with a Bootstrap navbar

    To learn more about Bootstrap navbars, visit the [documentation for the navbar component](https://getbootstrap.com/docs/5.2/components/navbar/).

    Again, when we use Bootstrap components like this, we don't try to write them from scratch. Instead, we COPY the HTML example from `getbootstrap.com` or some other examples website and "tweak it" to work with our example.

    The following is some code extracted from that website and what it looks like before it collapses.

    ```html
    <nav class="navbar navbar-expand-lg bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled">Disabled</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    ```

    Do you see where you would change the wording for your "brand" (in the example it is the word "Navbar" in an anchor? What about where you would add your specific links to other pages?

    Replace the links on your index.html page with a Bootstrap navbar.

1. Test your page.
