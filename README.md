# Fruit
---
### 🍒 Welcome to fruit.
- A large and extensive hub for all designer and developer needs. Everything here is 100% free.
- You can help us by sending Pull Requests to add more services or by removing ones whose offerings have changed or been retired.
- Please do note if you find an issue with any service listed here, report it to them, not us! (we didn't make it, we are only listing it!)
- This project is inspired by [free-for.dev!](https://free-for.dev/#) Check them out!

### 📚 What to do in Pull Requests.
- **PLEASE only upload either the html and markdown file or just the markdown file!**
- Please refer to [this page](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/) when adding icons.
- **If it is not available there, keep a similar icon with it, for example if Gmail's icon is not there, you can use:**
- Google (Material) `:material-google:`
- Google (Fontawesome) `:fontawesome-brands-google:`
- Google (Simple) `:simple-google:`
- **A short description about the service, preferrably the first thing you see when you load up said service's site should be there.**
- The service should also have a **free tier** that does not compromise security.
- The service can be a personal project of yours, as long as it has reasonable uptime.

### 🍒 How do I preview the page or change functionality of the page?
- You will need `Python 3.4` or Higher which you can get [here](https://www.python.org/).
- Run `pip install mkdocs-material` (the mkdocs skin we use, should come with mkdocs as a presquity) and then check if mkdocs is installed with `mkdocs --version`. If not, run `pip install mkdocs`. You can also run `pip install -r requirements.txt` alternatively.
- Then clone this repository using `git clone https://github.com/hamhimdev/fruit`.
- You can now edit index.md in the `docs` folder as much as you want following the pull request guidelines before this topic.
- After you are done, you need to be in the parent folder of the `docs` folder, and if you have changed anything, such as the theme, or need additonal features, add it through mkdocs.yml. You can refer to [the mkdocs page](https://www.mkdocs.org) and [squidfunk's material theme for mkdocs](https://squidfunk.github.io/mkdocs-material/) if you need to.
- To preview it, run `mkdocs serve` and follow the URL (Likely `http://127.0.0.1:8000/`) shown in the output and open it in your browser. It should show you how it looks.
- When in the parent foler, run `mkdocs build` and it will build the (static) page of the markdown file.
- More details can be found at [the mkdocs page](https://www.mkdocs.org/) and [squidfunk's material theme for mkdocs](https://squidfunk.github.io/mkdocs-material/) with additional settings and features even we didn't use in fruit!
