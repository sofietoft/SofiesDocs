---
title: IDiscountRewardProvider
description: API reference for IDiscountRewardProvider in Umbraco Commerce
---
## IDiscountRewardProvider

```csharp
public interface IDiscountRewardProvider
```

**Namespace**
* [Umbraco.Commerce.Core.Discounts.Rewards](README.md)

### Properties

#### Alias

```csharp
public string Alias { get; }
```


---

#### Description

```csharp
public string Description { get; }
```


---

#### Icon

```csharp
public string Icon { get; }
```


---

#### LabelView

```csharp
public string LabelView { get; }
```


---

#### Name

```csharp
public string Name { get; }
```


---

#### SettingDefinitions

```csharp
public IEnumerable<DiscountRewardProviderSettingDefinition> SettingDefinitions { get; }
```


### Methods

#### CalculateReward

```csharp
public DiscountRewardCalculation CalculateReward(DiscountRewardContext context, 
    IReadOnlyDictionary<string, string> settings)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->