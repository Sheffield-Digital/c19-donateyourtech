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
1. Home Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/index.html
   - [Source](./index.html)

## Equipment List
1. Equipment List Page (authenticated profile version)
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/equipment-list.html
   - [Source](./equipment-list.html)
2. Equipment List Page (single list version)
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/equipment-list-single.html
   - [Source](./equipment-list-single.html)


## Donate Equipment Journey
1. Donor Introduction Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/donor-intro.html
   - [Source](./donor-intro.html)
2. Donation Overview Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/donor-donation.html
   - [Source](./donor-donation.html)
3. Donation Add Equipment Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/donor-add-equipment.html
   - [Source](./donor-add-equipment.html)
4. Donation Check Email Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/donor-check-your-email.html
   - [Source](./donor-check-your-email.html)
5. Donation Confirm Email Page
6. Donation Token Failed Page
7. Donation Thank You Page

## Service Centre Journey
1. Service Centre Introduction Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/service-centre-intro.html
   - [Source](./service-centre-intro.html)
2. Service Centre Sign In Page
3. Service Centre Link Emailed Page
4. Service Centre Sign In Failed Page
3. Service Centre Registration Page
   - https://sheffield-digital.github.io/c19-donateyourtech/prototype/service-centre-sign-up.html
   - [Source](./service-centre-sign-up.html)
