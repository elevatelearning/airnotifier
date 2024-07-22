# MongoDB

```sh
fly launch --name elevate-learning-mongodb --region jnb
fly volumes create mongodbdata --size 3
fly scale memory 512
fly deploy --local-only
```
