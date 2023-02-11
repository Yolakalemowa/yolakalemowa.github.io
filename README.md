# Links template

This is a template for Astro based on the design of [omg.lol](https://omg.lol) pages.

## Usage
1.  Click on the "Use this template" button and create a new repository named `USERNAME.github.io` (replace USERNAME with your GitHub username). Then, in the repository, go into `Settings > Pages > Build and deployment` and change the Source to GitHub Actions.
2.  Update your details in the `src/config.json` file. The location is optional, and if you don't want to use it you can simply delete the line (don't leave it blank, though). 

    The titles under links need to be **exactly** how you want them to appear. This means that if you want the link to appear as "gOoGle" then you need to type:
    ```json
    "gOoGle": "https://www.google.com"
    ```
    Also keep in mind that you need to include `https://` for the link to work. 
3.  Add your image to the `public/icon/` folder, and delete the `favicon.svg` file currently present.
4.  (Optional) You can change the background and text colors by editing the values in `src/styles/colors.scss`.
5. Commit your changes, and go to https://USERNAME.github.io, and you should see your site. Enjoy!

## Build instructions (for advanced users only)
1.  ```sh
    git clone https://github.com/noClaps/links-template-astro.git && cd links-template-astro
    ```
2.  ```sh
    npm install
    npm run dev
    ```
    Run this in the root directory (`links-template-astro/` if you followed the instructions above), and open `localhost:3000` in your desired browser to see the preview. Make sure to keep this repository and your dependencies up-to-date, especially if you plan to contribute.
3.  ```sh
    npm run build
    ```
    This builds the site and places the files in the `dist/` directory.

## Licenses
The licenses of all npm dependencies are in their respective folders in `node_modules/` when you install them with `npm install`.

[Astro](https://astro.build), the static site generator used to generate this template, is licensed under the [MIT license](https://github.com/withastro/astro/blob/main/LICENSE).

The icons come from [Octicons](https://primer.style/octicons) and are licensed under the [MIT License](https://github.com/primer/octicons/blob/main/LICENSE).

The [Inter](https://rsms.me/inter) and [Patua One](https://fonts.google.com/specimen/Patua+One) fonts are licensed under the [OFL-1.1 License](https://github.com/rsms/inter/blob/master/LICENSE.txt).

All of the remaining content in this repository is licensed under the [BSD Zero Clause license](LICENSE).
