# COVID19 FIEC MOBILE APP

## Requirements

- Nodejs 8.10.0
- Ionic/CLI 3.9.2

## Set up

1. Clone this project and enter

`git clone https://github.com/xavierfigueroav/covid19-fiec`

`cd covid19-fiec/mobile`

2. Install app dependencies

`npm install`

3. Run the application in the browser

`ionic serve`

## Contribute

'dev' is the development and default branch. 'master' is the production branch.

### Suggested workflow

1. Create a new branch from 'dev'

`git checkout dev`

`git checkout -b quarantine-tab`

2. Code, add, commit and push. When you are done, merge your branch into 'dev'

`git add <files>`

`git commit -m "<message>"`

`git push origin quarantine-tab`

Repeat. Eventually...

`git checkout dev`

`git merge quarantine-tab`

`git push origin dev`

3. When 'dev' is production ready...

`git checkout master`

`git merge dev`

`git push origin master`

4. Keep this README up-to-date
