# EA-Product-Card v0.0.1

This is a NPM deployment test package

### Elis Antonio Perez

## Example:

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'ea-product-card';
<ProductCard
    product={ product }
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```
