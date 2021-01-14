---
name: 📅 Release
about: Release checklist
labels: 'feature' 'documentation'
---
# 📝 Notes

TODO before creating this issue:
 - Fill in "Feature" section.
 - Remove irrelevant checkboxes.
 - Replace X.Y version in following sections.
 - Link relevant issues.
 - Remove the current (Notes) section.

# 🚀 Feature

Description of the new feature


# 📅 Checklist

## 🔶 Staging 

### Dev Tag
 - [ ] [supertokens-core:X.Y](https://github.com/supertokens/supertokens-core/tree/X.Y)
 - [ ] [supertokens-node:X.Y](https://github.com/supertokens/supertokens-node/tree/X.Y)
 - [ ] [supertokens-website:X.Y](https://github.com/supertokens/supertokens-website#X.Y)
 - [ ] [supertokens-auth-react:X.Y](https://github.com/supertokens/supertokens-auth-react/tree/X.Y)

### Others

 - [supertokens-demo-react:master](https://github.com/supertokens/supertokens-nextjs-demo/tree/master)
     - [ ] In progress
     - [ ] [PR]() Ready using supertokens/supertokens-auth-react#X.Y and supertokens/supertokens-node#X.Y github repositories in package.json

 - [supertokens-nextjs-demo:master](https://github.com/supertokens/supertokens-nextjs-demo/tree/master)
     - [ ] In progress
     - [ ] [PR]() Ready using supertokens/supertokens-auth-react#X.Y and supertokens/supertokens-node#X.Y github repositories in package.json

### 📚 Documentation

- [ ] EmailPassword main documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/emailpassword/introduction)

- [ ] NextJS main documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/emailpassword/nextjs/supertokens-with-nextjs)

- [ ] nodejs documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/nodejs/installation)

- [ ] auth-react documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/auth-react/introduction)


## 🔥 Production 

### 💻 NPM and core release

 - [ ] [supertokens-core:X.Y](https://github.com/supertokens/supertokens-core/tree/X.Y)
    - Docker update
       - [ ] MySQL
       - [ ] Postgres
       - [ ] MongoDB
    - [ ] try.supertokens.io
    - [ ] Update SaaS config
 - [ ] [supertokens-node:X.Y](https://github.com/supertokens/supertokens-node/tree/X.Y)
 - [ ] [supertokens-website:X.Y](https://github.com/supertokens/supertokens-website#X.Y)
   - [ ] Updated tests to use `supertokens-node` from registry.
 - [ ] [supertokens-auth-react:X.Y](https://github.com/supertokens/supertokens-auth-react/tree/X.Y)
   - [ ] Updated tests to use `supertokens-node` from npm registry
   - [ ] Updated `peerDependencies` to use `supertokens-website` from npm registry

### 🔀 Others

 - [supertokens-react-themes:X.Y](https://github.com/supertokens/supertokens-react-themes/tree/X.Y)
   - [ ] Updated [PR]() with `supertokens-auth-react` from npm registry
   - [ ] Release [theme demo app](https://supertokens-react-themes.surge.sh) on surge using `npm run surge`
   - [ ] Published to npm registry

- [supertokens-demo-react:master](https://github.com/supertokens/supertokens-nextjs-demo/tree/master)
   - [ ] Updated [PR]() using `supertokens-node` and `supertokens-auth-react` npm registry.
   - [ ] Deployed to [demo site](http://emailpassword.demo.supertokens.io/)

 - [supertokens-nextjs-demo:master](https://github.com/supertokens/supertokens-nextjs-demo/tree/master)
     - [ ] [PR]() updated using `supertokens-node` and `supertokens-auth-react` npm registry.
     - [ ] Merged to master

### 📚 Documentation

- EmailPassword main documentation update
   - [ ] Deployed on [production site](https://supertokens.io/docs/emailpassword/introduction)

- NextJS main documentation update
   - [ ] Deployed on [production site](https://test.supertokens.io/docs/emailpassword/nextjs/supertokens-with-nextjs)

- nodejs documentation update
   - [ ] Deployed on [production site](https://supertokens.io/docs/nodejs/installation)

- auth-react documentation update
   - [ ] Deployed on [production site](https://supertokens.io/docs/auth-react/installation)