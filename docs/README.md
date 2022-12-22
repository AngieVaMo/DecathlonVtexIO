# Decathlon VTEX io clone

This is a clone of [Decathlon](https://www.decathlon.com.co/) website based on the VTEX minimum Boilerplate Theme, which is a basic store front model based on the VTEX IO Store Framework.

- Desktop view <br>
![home, desktop view](/assets/img/documentacion/desktop-view1.JPG)
![home, desktop view](/assets/img/documentacion/desktop-view2.JPG)
![home, desktop view](/assets/img/documentacion/desktop-view3.JPG)
![home, desktop view](/assets/img/documentacion/desktop-view4.JPG)
![home, desktop view](/assets/img/documentacion/desktop-view5.JPG)

- Mobile view <br>
![home, mobile view](/assets/img/documentacion/mobile-view1.JPG)
![home, mobile view](/assets/img/documentacion/mobile-view2.JPG)
![home, mobile view](/assets/img/documentacion/mobile-view3.JPG)
![home, mobile view](/assets/img/documentacion/mobile-view4.JPG)


## Configuration

### Install necessary tools:

* Code editor
* NodeJS
* Yarn (recomended)
* Git

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.


## Dependencies:
1."vtex.store": "2.x"

2."vtex.store-header": "2.x"

3."vtex.product-summary": "2.x"

4."vtex.store-footer": "2.x"

5."vtex.store-components": "3.x"

6."vtex.styleguide": "9.x"

7."vtex.slider": "0.x"

8."vtex.carousel": "2.x"

9."vtex.shelf": "1.x"

10."vtex.menu": "2.x"

11."vtex.minicart": "2.x"

12."vtex.product-details": "1.x"

13."vtex.product-kit": "1.x"

14."vtex.search-result": "3.x"

15."vtex.login": "2.x"

16."vtex.my-account": "1.x"

17."vtex.flex-layout": "0.x"

18."vtex.rich-text": "0.x"

19."vtex.store-drawer": "0.x"

20."vtex.locale-switcher": "0.x"

21."vtex.product-quantity": "1.x"

22."vtex.product-identifier": "0.x"

23."vtex.product-specification-badges": "0.x"

24."vtex.product-review-interfaces": "1.x"

25."vtex.telemarketing": "2.x"

26."vtex.order-placed": "2.x"

27."vtex.stack-layout": "0.x"

28."vtex.tab-layout": "0.x"

29."vtex.responsive-layout": "0.x"

30."vtex.slider-layout": "0.x"

31."vtex.iframe": "0.x"

32."vtex.breadcrumb": "1.x"

33."vtex.sticky-layout": "0.x"

34."vtex.add-to-cart-button": "0.x"

35."vtex.modal-layout": "0.x"

36."vtex.store-icons": "0.x"

37."vtex.disclosure-layout": "1.x"

38."vtex.product-list": "0.x"

39."vtex.store-link": "0.x"


## Custom Apps installed:
1."itgloberspartnercl.help-button": "0.x",

2."itgloberspartnercl.bullets-diagramation": "0.x"


## Peer Dependencies:
1."vtex.wish-list": "1.x"

2."vtex.reviews-and-ratings": "3.x"

3."vtex.questions-and-answers": "0.x"

4."vtex.mega-menu": "2.x"


## Contributors
***Angie Vanessa Moreno Palacios***