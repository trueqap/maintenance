# Maintenance Page

This project contains a simple yet stylish maintenance page that informs visitors about ongoing scheduled maintenance.

## Features

- Responsive design that works well on both desktop and mobile devices
- Multilingual message: Hungarian, English, German, and Italian
- Modern, clean appearance
- Customizable SVG logo
- SEO-friendly: instructs search engines not to index the page

## Files

- `index.html`: The main HTML file for the maintenance page
- `img/robots.svg`: The SVG logo displayed on the page (not included in this repo)

## Usage

1. Clone this repo or download the files.
2. Place the `index.html` file in the root directory of your web server.
3. Add your own `robots.svg` logo to the `img` folder, or modify the logo path in the `index.html` file.
4. Customize the text and styles in the `index.html` file as needed.

## Customization

- To modify colors, look for the appropriate CSS variables in the `<style>` section.
- To change the text, simply edit the content of the corresponding `<p>` elements.
- To adjust the logo size, modify the `width` property of the `.logo` class.
- To add or remove languages, duplicate or remove the `.language` div blocks as needed.

## SEO

The page includes a `<meta name="robots" content="noindex">` tag, which instructs search engines not to index the page. This is useful during the maintenance period, but remember to remove or modify this tag when restoring your normal website.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contributing

If you have any suggestions or ideas for improvement, please open an issue or submit a pull request.
