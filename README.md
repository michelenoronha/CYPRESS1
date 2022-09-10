# CYPRESS
 CYPRESS APRENDIZADOS
ref: refs/heads/main
## install all dependencies from the root directory
npm install
cd ./examples/testing-dom__drag-drop
# start local server
npm start &
# open Cypress App
npm run cypress:open
cd ./examples/testing-dom__drag-drop
# start local server
npm start &
# run Cypress tests headlessly
npm run cypress:run

### runs all example projects in specific browser
### similar to cypress run --browser <name>
npm run cypress:run -- --browser chrome

### sends test results, videos, screenshots
### to Cypress dashboard
npm run cypress:run -- --rec
