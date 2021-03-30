---
title: "BaseButton"
---

## Description

`BaseButton` is main button for ala, if you want to create a custom button then it should extend this.

## Usage

```dart title="main.dart"
// Import the package to use BaseButton Component
import "package:a-mobile-module/a-mobile-module.dart";

BaseButton(
    // Widget child, so you can free to choose
    child: Text("Base Button"),
    // Add onTap props to add ripple effect when clicked
    onTap: () {
        print("On Tap Pressed");
    }
)
```

## Constructors
**BaseButton**({ ***Key*** key , ***Widget*** child , ***double*** width , ***double*** height , ***EdgeInsetsGeometry*** padding , ***VoidCallback*** onTap });<br />
Construct Base Button

## Properties

**child** -> Widget<br />
Button content, can be anything because it's widget.<br />
*required*

**width** -> double<br />
Button width, if not specified then the button will take child size + padding for width.<br />
*required, non-nullable*

**width** -> double<br />
Button width, if not specified then the button will take child size + padding for width.<br />
*nullable*

**height** -> double<br />
Button height, if not specified then the button will take child size + padding for height.<br />
*nullable*

**padding** -> EdgeInsetsGeometry<br />
Padding for child.<br />
*nullable*

**onTap** -> VoidCallback<br />
Callback on button tap.<br />
*required, non-nullable*

<br />

#### Maintained By corecybernetics354@gmail.com

