# Product-Card-FJB

This is a test package for deployment on NPM

### Example

```
import { ProductCard } from "product-card-fjb";
```

```
  <ProductCard
    product={product}
    initialValues={{
        count: 5,
        maxCount: 10,
    }}
  >
    {
      ({ isMaxCountReached, count, reset, increaseBy }) => (
        <>
          <ProductCard.Image />
          <ProductCard.Title />
          <ProductCard.Buttons />
        </>
      )
    }
  </ProductCard>

```

### Facundo Javier Bettella