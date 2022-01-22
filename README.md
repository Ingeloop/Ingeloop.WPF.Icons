# Ingeloop.WPF.Icons
Icons library for WPF (Material Design Icons).

Based on Material Design Icons: https://materialdesignicons.com/

In accordance of: https://github.com/Templarian/MaterialDesign/blob/master/LICENSE

## Quick guide:

### 1) Namespace:

Add the namespace as follow:

```xaml
xmlns:icons="clr-namespace:Ingeloop.WPF.Icons;assembly=Ingeloop.WPF.Icons"
```


### 2) Resource:

Load the resource to your UI, as follow:

```xaml
<ResourceDictionary Source="pack://application:,,,/Ingeloop.WPF.Icons;component/Resources/Generic.xaml"/>
```

### 3) Usage:

Use Icons:

```xaml
<icons:PackIcon Kind="UserAdd" Size="32"/>
```

Kind property is used according to the tags of the icons of https://materialdesignicons.com/
