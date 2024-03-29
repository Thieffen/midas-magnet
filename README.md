# Welcome to Remix!

- [Remix Docs](https://remix.run/docs)

## Netlify Setup

1. Install the [Netlify CLI](https://www.netlify.com/products/dev/):

```sh
npm i -g netlify-cli
```

If you have previously installed the Netlify CLI, you should update it to the latest version:

```sh
npm i -g netlify-cli@latest
```

2. Sign up and log in to Netlify:

```sh
netlify login
```

3. Create a new site:

```sh
netlify init
```

## Development

The Netlify CLI starts your app in development mode, rebuilding assets on file changes.

```sh
npm run dev
```

Open up [http://localhost:3000](http://localhost:3000), and you should be ready to go!

## Deployment

There are two ways to deploy your app to Netlify, you can either link your app to your git repo and have it auto deploy changes to Netlify, or you can deploy your app manually. If you've followed the setup instructions already, all you need to do is run this:

```sh
$ npm run build
# preview deployment
$ netlify deploy

# production deployment
$ netlify deploy --prod
```


## Infos

Admin URL:      https://app.netlify.com/sites/midas-magnet
URL:            https://midas-magnet.netlify.app
Site ID:        347523c3-58a3-42cb-87f0-0c5e39d54576
```git push```        Push to your git repository to trigger new site builds
```netlify open```    Open the Netlify admin URL of your site


## Tree
Overview
- Acronym
- Full Title
- Main purpose
- Summary
- Keywords
- Model categories (multiple choices list)

Ownership & licence
- Ownership (unique choice from list)
- Licence type (unique choice from list)
- Licence details (appear based on licence type choice)


## Workflow
- admin display list of surveys by status (created, incomplete, completed)
- admin creates a new survey (email, name, surname) and send the survey link by email
- admin can modify a survey email, name surname infos
- admin can resend survey link
- admin can display a survey
- admin can delete survey manually


- modeller recieves an unique survey link by email
- modeller is guided to complete the survey

- each survey link has an expiration date (2 weeks by default)


## Routes
/                                        index - just a logo

/survey/$survey-number/                  survey welcome screen
/survey/$survey-number/overview          survey overview section forms
/survey/$survey-number/licence           survey licence section forms
/survey/$survey-number/*                 etc..


/admin/                                  admin dashboard
/admin/login
/admin/




