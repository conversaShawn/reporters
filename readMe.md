# Mocha Reporters 

Since Cypress is built on top of Mocha, any [reporter option available via Mocha](https://mochajs.org/#reporters) can be used.

In each branch of this repo, I will test different commonly used plugins and provide resources I found helpful.

## Installation
```
## clone this repo to a local directory
git clone https://github.com/<your-username>/cypress-example-todomvc.git

## cd into the cloned repo
cd cypress-example-todomvc

## install the node_modules
npm install
```

## [Reporters](https://docs.cypress.io/guides/tooling/reporters) 
*No plugins were used for this branch.*
### Run command:
`npx cypress run --reporter {{reporter_option}}`
### Default directory:
> None

### Note:
For additional output, a custom reporter is recommended

### Final thoughts:
Pros:
- No installation necessary
- Can run multiple specs without needing additonal plugins or tools 

Cons:
- Output only rendered in terminal unless additional options are provided