# Revealjs Slides for Java 2019


### Prerequisites

You need npm to build the project.

``` bash
brew install npm
```

### Clone and Prepare

Then

``` bash
git clone https://github.com/njuics/java-2019.git
cd java-2019
npm install
```

### Compose

Please create new slides in `src` folder. Use `demo.html` as the reference to compose good-looking pages. Please put the image files in `contents/images`.

### Build and run

To preview locally,

``` bash
npm run live-fa-svg
```

To deploy to github pages,

``` bash
npm run build-web
git add .
git commit -a -m "..."
npm run publish
```

Of course, don't forget to push the changes,

``` bash
git push origin master
```