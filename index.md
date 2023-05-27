# Fruit

### :material-fruit-cherries: Welcome to fruit.

A large and extensive hub for all designer and developer needs. Everything here is 100% free.  
You can help us by sending Pull Requests to add more services or by removing ones whose offerings have changed or been retired.  

> Please do note if you find an issue with any service listed here, report it to them, not us! (we didn't make it, we are only listing it!)  

> Fruit is still being updated. We are aware that all the categories are not filled.  
This project is inspired by [free-for.dev!](https://free-for.dev/#) Check them out!  

### :material-source-pull: Pull Request Notes & Guidelines

#### :material-book: Notes
The file where services are listed at is **docs.md** inside the `./docs` folder. That is the file you edit.  
The service should have a free tier that is safe to use and does not risk security.  
The service can be your own or from someone you own, and you may list it as long as it is **having a reasonable uptime.**

#### :material-git: When adding items to it, please keep these in mind:  
The service must be listed under the category where it fits most.  

It must list an icon, of the service. Use [this](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/) resource when finding one.  
If no icon is avaliable for it through there, keep a similar icon with it, for instance if Gmail's icon is not there, you can use:  
**Google (Material) `:material-google:`**  
**Google (Fontawesome) `:fontawesome-brands-google:`**  
**Google (Simple) `:simple-google:`**  

> The description for the service either has to be a small description of an official page of theirs or a small description.  
You also should signify what platforms the services are avalable in with the icons: :material-apple: :material-apple:+ :material-microsoft-windows: :material-android: :material-apple-ios: :material-web: :octicons-terminal-24:. 
:material-apple: Used if both Intel and M1 and above series of chips are supported.  
:material-apple:+ Used if only M1 and above series of chips are supported.  

When uploading it to :fontawesome-brands-github: GitHub as a Pull Request, please do not upload the built version, and instead just upload the modified **docs.md** file

#### :material-list-box: You must format it like how it is below:  
:material-fruit-cherries: [Fruit](https://hamhimdev.github.io/fruit/) - A large and extensive hub for all designer and developer needs. Everything here is 100% free. :material-web:  

### :material-language-python: How do I preview the page, build it or change functionality of the page?

> You will need :material-language-python: Python 3.4 or Higher which you can get [here](https://www.python.org/).  
Run `pip install mkdocs-material` (the mkdocs skin we use, should come with mkdocs as a presquity) and then check if mkdocs is installed with `mkdocs --version`. If not, run `pip install mkdocs`. You can also run `pip install -r requirements.txt` alternatively.  
Then clone this repository using `git clone https://github.com/hamhimdev/fruit`.  
You can now edit index.md in the `docs` folder as much as you want following the pull request guidelines before this topic.  
After you are done, you need to be in the parent folder of the `docs` folder, and if you have changed anything, such as the theme, or need additonal features, add it through mkdocs.yml. You can refer to [the mkdocs page](https://www.mkdocs.org) and [squidfunk's material theme for mkdocs](https://squidfunk.github.io/mkdocs-material/) if you need to.  
To preview it, run `mkdocs serve` and follow the URL (Likely `http://127.0.0.1:8000/`) shown in the output and open it in your browser. It should show you how it looks.  
When in the parent foler, run `mkdocs build` and it will build the (static) page of the markdown file.  
More details can be found at [the mkdocs page](https://www.mkdocs.org/) and [squidfunk's material theme for mkdocs](https://squidfunk.github.io/mkdocs-material/) with additional settings and features even we didn't use in fruit!  

This section is getting a rework, please follow the steps above.  

#### :material-microsoft-windows: Windows
To do this, please download :material-language-python: Python 3.4 or Higher [here](https://www.python.org/).  
