# DonateYourTech Prototype

The prototype is built using HTML/JS/CSS and Bootstrap. To contribute to the
prototype:

1. Clone the repository
2. Navigate to the home page using a file reference in a web browser

    ```sh
    # Clone the repo
    git clone git@github.com:Sheffield-Digital/c19-donateyourtech.git

    # Open the prototype in a web browser
    firefox file:///path/to/the/repository/prototype/index.html # Linux
    open file:///path/to/the/repository/prototype/index.html # MacOS
    ```

3. Pick a page from the wire frames in the Miro board
4. Create the wire frame using HTML/JS/CSS and Bootstrap
5. Push the changes

    ```sh
    # Hack, hack, hack...

    # Push the changes
    git add . && git commit && git push
    ```

6. Merge the changes into the GitHub pages branch to publish

    ```sh
    # Merge the changes
    git br --track gh-pages origin/gh-pages
    git co gh-pages
    git merge origin/master
    git push
    ```

# Journeys

## Home
1. Homepage: ./prototype/index.html

## Donate Equipment
1. ./prototype/donor-intro.html
2. ./prototype/donor-donation.html
3. ./prototype/donor-add-equipment.html
4. ./prototype/donor-check-your-email.html
5. ./prototype/donor-confirm-your-email.html
6. ./prototype/donor-token-failed.html
7. ./prototype/donor-thank-you.html

## Service Centre
