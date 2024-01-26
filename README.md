# Rest-API

This is a simple Express.js application for managing products with basic CRUD operations.

#### Setup Instructions

1. **Clone Repository:**

   ```bash
   git clone https://github.com/miusarname/Rest-API.git
   cd Rest-API
   ```

2. **Install Dependencies:**

   Make sure you have Node.js and npm installed on your machine. Then, install the project dependencies:

   ```bash
   npm install
   ```

3. **Run the Application:**

   To start the server, run:

   ```bash
   node server.js
   ```

   The server will start at `http://localhost:3000`.

#### Endpoints

- **GET /products**

  Fetches all the products.

- **POST /products**

  Adds a new product. Expects a JSON object containing `name` and `price`.

- **PUT /products/:id**

  Updates an existing product by its ID. Expects a JSON object with updated `name` and/or `price`.

- **DELETE /products/:id**

  Deletes a product by its ID.

- **GET /products/:id**

  Fetches a product by its ID.

#### Example Usage

Assuming the server is running locally:

- To fetch all products:

  ```
  GET http://localhost:3000/products
  ```

- To add a new product:

  ```
  POST http://localhost:3000/products
  Body: { "name": "new product", "price": 200 }
  ```

- To update a product with ID 1:

  ```
  PUT http://localhost:3000/products/1
  Body: { "name": "updated product", "price": 300 }
  ```

- To delete a product with ID 1:

  ```
  DELETE http://localhost:3000/products/1
  ```

- To fetch a product with ID 1:

  ```
  GET http://localhost:3000/products/1
  ```

#### Dependencies

- **express:** Fast, unopinionated, minimalist web framework for Node.js.
- **morgan:** HTTP request logger middleware for Node.js.

### README（読み取り専用）

これは、基本的なCRUD操作を行うための、シンプルなExpress.jsアプリケーションです。

#### セットアップ手順

1. **リポジトリをクローンする:**

  ```bash
   git clone https://github.com/miusarname/Rest-API.git
   cd Rest-API
   ```

2. **依存関係をインストールする:**

   マシンにNode.jsとnpmがインストールされていることを確認してください。次に、プロジェクトの依存関係をインストールします:

   ```bash
   npm install
   ```

3. **アプリケーションを実行する:**

   サーバーを起動するには、次のコマンドを実行します:

   ```bash
   node server.js
   ```

   サーバーは `http://localhost:3000` で起動します。

#### エンドポイント

- **GET /products**

  すべての製品を取得します。

- **POST /products**

  新しい製品を追加します。`name` と `price` を含むJSONオブジェクトが必要です。

- **PUT /products/:id**

  IDで既存の製品を更新します。更新された `name` と/または `price` を含むJSONオブジェクトが必要です。

- **DELETE /products/:id**

  IDで製品を削除します。

- **GET /products/:id**

  IDで製品を取得します。

#### 使用例

サーバーがローカルで実行されていると仮定します:

- すべての製品を取得するには:

  ```
  GET http://localhost:3000/products
  ```

- 新しい製品を追加するには:

  ```
  POST http://localhost:3000/products
  ボディ: { "name": "新しい製品", "price": 200 }
  ```

- IDが1の製品を更新するには:

  ```
  PUT http://localhost:3000/products/1
  ボディ: { "name": "更新された製品", "price": 300 }
  ```

- IDが1の製品を削除するには:

  ```
  DELETE http://localhost:3000/products/1
  ```

- IDが1の製品を取得するには:

  ```
  GET http://localhost:3000/products/1
  ```

#### 依存関係

- **express:** Node.js向けの高速で意見のない、ミニマリストなWebフレームワーク。
- **morgan:** Node.js向けのHTTPリクエストロガーミドルウェア。

### README（阅读专用）

这是一个使用Express.js进行基本CRUD操作的简单应用程序。

#### 设置说明

1. **克隆存储库:**

   ```bash
   git clone https://github.com/miusarname/Rest-API.git
   cd Rest-API
   ```

2. **安装依赖项:**

   确保您的计算机上已安装Node.js和npm。然后，安装项目依赖项:

   ```bash
   npm install
   ```

3. **运行应用程序:**

   要启动服务器，请运行:

   ```bash
   node server.js
   ```

   服务器将在 `http://localhost:3000` 上启动。

#### 端点

- **GET /products**

  获取所有产品。

- **POST /products**

  添加新产品。需要包含 `name` 和 `price` 的JSON对象。

- **PUT /products/:id**

  通过ID更新现有产品。需要包含更新后的 `name` 和/或 `price` 的JSON对象。

- **DELETE /products/:id**

  通过ID删除产品。

- **GET /products/:id**

  通过ID获取产品。

#### 示例用法

假设服务器在本地运行:

- 获取所有产品:

  ```
  GET http://localhost:3000/products
  ```

- 添加新产品:

  ```
  POST http://localhost:3000/products
  Body: { "name": "新产品", "price": 200 }
  ```

- 通过ID为1的产品:

  ```
  PUT http://localhost:3000/products/1
  Body: { "name": "更新的产品", "price": 300 }
  ```

- 删除ID为1的产品:

  ```
  DELETE http://localhost:3000/products/1
  ```

- 通过ID为1的产品:

  ```
  GET http://localhost:3000/products/1
  ```

#### 依赖项

- **express:** 用于Node.js的快速、无见解、极简主义的Web框架。
- **morgan:** 用于Node.js的HTTP请求记录中间件。


