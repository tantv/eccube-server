
## Create your database

1 . Clone this repo to anywhere on your computer.

```bash
git clone https://github.com/tantv/eccube-server.git
```

2 . Change `db.json` to **your own content** according to the [`json-server example`](https://github.com/typicode/json-server#example) and then `commit` your changes to git.

_this example will create `/products` route , each resource will have `id`, `name` and `category`.
```json
{
  "products":[
    {
      "id" : 1,
      "name": "Product Name 1",
      "category" : "Category 1"
    },
    {
      "id" : 2,
      "name": "Product Name 2",
      "category" : "Category 2"
    }
  ]
}
```

Go to [`json-server`](https://github.com/typicode/json-server) for more details.
