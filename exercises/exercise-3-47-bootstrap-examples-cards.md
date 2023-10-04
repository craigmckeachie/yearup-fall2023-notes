# Exercise 3-47

In this exercise, you will add a set of cards to the `bootstrap-examples` project.

A Bootstrap card is a container that includes options for headers, content, and footers, as well as contextual background colors and other display options.

## Bootstrap Cards

1.  **Open** the folder named `bootstrap-examples`
    in Visual Studio Code.
1.  Create the page and link to it.

    Begin by adding a new page to your project named cards.html. Then, on the home page, add a new link to this page.

1.  Test the link.
1.  Design the page.

    Your Bootstrap cards will show information about 4 different animals (think about something like a zoo or pet info card).

    You will need to find four small images of your animals, download them to your images folder, and make them the same size.

    To learn more about Bootstrap cards, go to the [documentation for cards](https://getbootstrap.com/docs/5.2/components/card/).

    Again, when we use Bootstrap components like this, we don't try to write them from scratch. Instead, we COPY the HTML example from getbootstrap.com or some other examples website and "tweak it" to work with our example.

    Find the example on `getbootstrap.com` titled "Images". It should resemble:

    ```html
    <div class="card" style="width: 18rem;">
      <img src="..." class="card-img-top" alt="..." />
      <div class="card-body">
        <p class="card-text">
          Some quick example text to build on the card title and make up the bulk of the card's content.
        </p>
      </div>
    </div>
    ```

    Do you see where you would add your image attributes? What about where you would add your textual description?
    Use this style of Bootstrap card to display pictures and information about two of your four animals. Test your page.
    Now find the example on getbootstrap.com titled "Horizontal". It should resemble:

    ```html
    <div class="card mb-3" style="max-width: 540px;">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="..." class="img-fluid rounded-start" alt="..." />
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              This is a wider card with supporting text below as a natural lead-in to additional content. This content
              is a little bit longer.
            </p>
            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
          </div>
        </div>
      </div>
    </div>
    ```

    Note the card sets a max width of 540px. (This might have been better done using a CSS class.)

    The card's image takes up the first 1/3 of the row and the card's body takes up the last 2/3 of the row on medium (md) devices and higher.

    Do you see where you would add your image attributes? What about where you would add a title and textual description?

    Use this style of Bootstrap card to display information about your other two animals.

1.  Test your page.
