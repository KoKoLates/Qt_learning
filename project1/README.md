# Ordering System
A Basic ordering system that that give the user several selections of meal, beverage and payment method. It calculates the total money with discount and show on the window automatically. Mainyly learning about Qt creater and how to use the slot of object in Qt designer.
## Involed
```cpp
this->setWindowTitle("Ordering System");
```
To set the useful name for the main application window.
### CheckBox and RadioButton
The mainly defference between them is that CheckBox could check more then one item, and the other could just have only one be choosen. The defluat of radioButton is exclusive, so that ones could revise that deflaut if needed.
```cpp
ui->radiobutton->setAutoExclusive(bool); 
```
