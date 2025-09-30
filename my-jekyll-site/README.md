# My Jekyll Site

This is a Jekyll project set up for GitHub Pages. Below are the details and instructions for setting up and running the site.

## Project Structure

```
my-jekyll-site
├── _posts          # Directory for blog posts
├── _layouts        # Directory for layout templates
├── _includes       # Directory for reusable components
├── _config.yml     # Jekyll configuration file
├── Gemfile         # Ruby dependencies
├── index.md       # Homepage of the site
└── README.md      # Project documentation
```

## Getting Started

To set up this Jekyll site locally, follow these steps:

1. **Install Ruby**: Ensure you have Ruby installed on your machine. You can check this by running `ruby -v` in your terminal.

2. **Install Bundler**: If you don't have Bundler installed, you can install it by running:
   ```
   gem install bundler
   ```

3. **Install Dependencies**: Navigate to the project directory and run:
   ```
   bundle install
   ```

4. **Run the Jekyll Server**: Start the Jekyll server with the following command:
   ```
   bundle exec jekyll serve
   ```
   Your site will be available at `http://localhost:4000`.

## Creating Blog Posts

To create a new blog post, add a Markdown file in the `_posts` directory following the naming convention `YYYY-MM-DD-title.md`. Each post should include front matter for metadata such as title, date, and tags.

## Customizing the Site

You can customize the site by editing the `_config.yml` file. This file contains various settings, including the site title, description, and base URL.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. 

## License

This project is open source and available under the [MIT License](LICENSE).