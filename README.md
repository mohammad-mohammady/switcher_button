# switcher_button

Switcher button.
Flutter switch button with minimal design and material animation and highly
customizable.It can be use as switch button or toggle buttons.

<img src="https://user-images.githubusercontent.com/32927238/110198529-7e394580-7e53-11eb-8239-7e3a8cce4d5f.gif" width="32%">

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
thanks to https://dribbble.com/Volorf for nice design.
