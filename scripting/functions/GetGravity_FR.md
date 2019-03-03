# GetGravity_FR

## Description

Permets d'obtenir la valeur de la gravité.

| Name | Description |
| ---- | ----------- |


## Examples

```c
#if !defined GetGravity
    native Float:GetGravity();
#endif

printf("Gravité actuelle: %f", GetGravity());
```

## Notes

::: warning

Cette fonction n'est pas définie par défaut. Ajouté 'native GetGravity();' juste en dessous de l'include a_samp.inc pour pouvoir l'utiliser.

:::

## Related Functions