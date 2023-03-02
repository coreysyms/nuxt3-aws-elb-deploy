# nuxt3-aws-elb-deploy
Key missing settings to deploy Nuxt 3 SSR for AWS Elastic Beanstalk (ELB)

The following 2 files need to be updated to deploy an SSR Nuxt 3 build to AWS Elastic Beanstalk. If you are running into 502 errors or `Error: Cannot find module '/var/app/current/server.js` in eb logs then this is the place to look.

See the above updates to package.json and nuxt.config.ts
