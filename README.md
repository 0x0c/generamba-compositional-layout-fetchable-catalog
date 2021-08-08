# generamba-compositional-layout-fetchable-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

```yaml:Rambafile
### Templates
catalogs:
- 'https://github.com/0x0c/generamba-compositional-layout-fetchable-catalog'
templates:
- {name: 0x0c_viper_fetchable_compositional_layout}
```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [compositional-layout](https://raw.githubusercontent.com/0x0c/generamba-compositional-layout-fetchable-catalog/main/0x0c_viper_compositional_layout/0x0c_viper_fetchable_compositional_layout.rambaspec)

# Dependencies

- [CompositionalLayoutViewController](https://github.com/oneinc-jp/CompositionalLayoutViewController)
- [CompositionalLayoutViewControllerViperExtension](https://github.com/0x0c/CompositionalLayoutViewControllerViperExtension)
