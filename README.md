## Reference
- https://aws.amazon.com/getting-started/tutorials/deploy-react-app-cicd-amplify/

- https://www.linkedin.com/learning/aws-for-developers-aws-amplify/aws-amplify-cli-installation?u=2099546




## Setup
```
  npm install -g @aws-amplify/cli
  amplify cofigure   # selece region, access kay, secret access kay
```
Create react project
```
  npx create-react-app mywebapp
```

```
  amplify init

  npm i -S aws-amplify
  npm i -S aws-amplify-react
```

Add feature
```
  amplify add analytics
  amplify push
```

Create environments
```
  amplify add hosting
  amplify push
```

Create auth
```
  amplify add auth
  amplify auth update
  amplify push
```
