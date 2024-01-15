# express_demo

快速获得一个可以开发、部署的express模版

### 开发

    npm run install
    npm run start

### 部署

    docker build . -t my-express
    docker run -d --name my-express-container -p 3001:3000 my-express

    # 或者
    docker-compose up
