# Development
## python code
```.py
from kivymd.app import MDApp
class quiz039(MDApp):
    def __init__(self, **kwargs):
        super().__init__(**kwargs)
        self.count = 0
    def build(self):
        return
    def add(self):
        self.count += 1
        self.root.ids.counter_label.text = f"Count = {self.count}"

quiz39 = quiz039()
quiz39.run()
```
## kivy code
```.py
Screen:
    size: 500,350
    MDBoxLayout:
        id: main_box
        orientation: 'horizontal'
        size_hint:.7,.7
        pos_hint: {'center_x':0.5, 'center_y':0.5}
        md_bg_color: "#FFFFFF"

        MDLabel:
            id : counter_label
            font_size: '34'
            size_hint:.4,1
            text: 'Ready!'
        MDRaisedButton:
            id: up
            text: 'Count +1'
            font_size: '34'
            size_hint:.4,1
            on_press: app.add()
```


# Solution overview
[]!
