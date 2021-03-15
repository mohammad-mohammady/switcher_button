# switcher_button

Switcher button.
Flutter switch button with minimal design and material animation and highly
customizable.It can be use as switch button or toggle buttons.


<img src="https://user-images.githubusercontent.com/32927238/111130699-cead5300-8577-11eb-8759-7b07b2c4d28c.gif" width="32%">

| Property | Description |
| --- | --- |
| `size` | Size of widget, width of widget is equal size and height of widget is equal size / 2|
| `onColor` | onColor is color of widget when it's on |
| `offColor` | offColor is color of widget when it's off |
| `value` | initial value of widget if true widget switch on else widget switch off |
| `onChange` | When user tap on switch button and change state of widget onChange will call and pass current state of widget  |



Usage
-----

```dart
SwitcherButton(
    value: true,
    onChange: (value) {
      print(value);
    },
  )
```
thanks to https://dribbble.com/katelaguta for nice design.
