# Unicidad de productos
1. Tienen el mismo `doi`. El `doi` siempre tiene que estar normalizado: sin el url inicial genérico (https://doi.org) y en minúscula y sin espacios alrededor
2. Sí los títutulos (sin doi) tienen una similaridad alta, se deber verificar que al menos un autor coincida en algún nombre (o inicial) y el primer apellido.  Además, si ambos son productos scienti,  deben tener el mismo tipo scienti a nivel 0 (`level: 0`). Ver [issue](https://github.com/colav/impactu/issues/445)
