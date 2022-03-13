# Notes

These are quick notes that can be useful when developing in PyQt. A sort of cheatsheet.

### Slots

Slots are just methods of MainWindow:

```python
class MainWindow(QMainWindow):
    def mySlot(self):
        pass
```

### Access UI elements

UI elements are members of MainWindow as well, let's suppose you defined a label `my_label` and want its text:

```python
self.my_label.text()
```
