# AWS Containers / Serverless Workshop

This repo is powering this site: https://containersworkshop.com/

#### Install Hugo:
On a mac:

```shell
brew install hugo
```

#### Install NodeJS packages:
```shell
npm install
```

#### Run Hugo locally:
```shell
npm run server
```

#### Build
```shell
npm run build
```

#### Run Docker locally

You can also skip all the above and run this within a container.

  ```shell
  # build the container
  docker build -t lab .

  # run the container
  docker run -p 8080:8080 lab
  ```

#### View built site locally:

Visit http://localhost:8080/ to see the site.
