<h1>
  <span class="headline">JavaScript Array Iterator Methods Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Navigate to [GitHub](https://github.com/) and create a new repository named **javascript-array-iterator-methods-lab**.

- Make sure the repo is set to `public`
- You do not need a `README.md`
- You do not need a `.gitignore`

Using the `Quick Setup` option, clone your newly created repo into your `~/code/ga/labs` directory with the `git clone` command:

```bash
git clone https://github.com/<your-username>/javascript-array-iterator-methods-lab.git
```

> Note: In the link above, where it says `<your-username>`, you should see the username from your GitHub account.

Next, `cd` into your new cloned directory, `javascript-array-iterator-methods-lab`:

```bash
cd javascript-array-iterator-methods-lab
```

Then, create an **`app.js`** and an **`index.html`** file. These files will hold your work for this lab:

```bash
touch app.js index.html
```

With the files created, open the contents of the directory in VS Code:

```bash
code .
```

Open the **`index.html`** file and add HTML boilerplate. Then link the **`app.js`** file by adding this line inside the `<head>` tag:

```html
<script defer src="./app.js"></script>
```

With this setup complete, we'll have two methods at our disposal for executing the code we write in **`app.js`**:

- Open the **`index.html`** file in your browser and access the console output in your browser's dev tools.
- Use `node` to execute the **`app.js`** file directly by using this command in your terminal:

```bash
node app.js
```

While either method is acceptable, you should use the same method as your instructor for simplicity.
