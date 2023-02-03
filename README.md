# Product-Card-FJB

Este es un paquete de pruebas de despliegue en NPM


### Facundo Javier Bettella


### Ejemplo

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