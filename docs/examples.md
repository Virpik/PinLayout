<p align="center">
	<img src="pinlayout-logo-small.png" alt="PinLayout Performance" width=100/>
</p>

<h1 align="center" style="color: #376C9D; font-family: Arial Black, Gadget, sans-serif; font-size: 1.5em">PinLayout Examples</h1>

The PinLayout's Example App exposes some usage example of PinLayout in real situations.

The Example App is available in the [`Example` folder](https://github.com/mirego/PinLayout/tree/master/Example). You must do a `pod install` before running the project.

</br>


## Intro Example
This is the PinLayout introduction example.  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/Intro/IntroView.swift)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/Intro/IntroView.swift"><img src="pinlayout_exampleapp_intro.png" alt="PinLayout example" width=120/></a>
  

## An RTL enabled version of the Intro example

This example uses PinLayout's right-to-left (RTL) language support. Similar to the Intro example.  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/IntroRTL/IntroRTLView.swift)


## UITableView with variable size cells.
This example show how PinLayout can be used to layout UITableView cells that have variables sizes.  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/TableViewExample)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/TableViewExample/TableViewExampleView.swift"><img src="pinlayout_exampleapp_tableview.png" alt="PinLayout example" width=120/></a>


## Adjust the layout based on the available size 
This example show how easy PinLayout can adjust the layout based on the available size.

* If the container's width is larger than 500 pixels, the UISegmentedControl is at the top-right corner and the label takes the remaining horizontal space.
* If the container's width is smaller than 500 pixels, the UISegmentedControl is placed below the label.

[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/AdjustToContainer/Subviews/ChoiceSelectorView.swift)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/AdjustToContainer/Subviews/ChoiceSelectorView.swift"><img src="pinlayout_example_adjust_to_container-portrait.png" alt="PinLayout example" width=120/></a>


## Form Example
This show a Form using PinLayout.  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/Form/FormView.swift)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/Form/FormView.swift"><img src="pinlayout_example_form.gif" alt="PinLayout example" width=120/></a>


## Adjust to container's size
This example show how PinLayout can be used to adjust items sizes based on their container's size.  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/AutoAdjustingSize/AutoAdjustingSizeView.swift)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/AutoAdjustingSize/AutoAdjustingSizeView.swift"><img src="pinlayout_exampleapp_auto_adjusting_size.png" alt="PinLayout example" width=120/></a>


## PinLayout's relative positionning
This example show the usage of PinLayout's relative positionning methods (above(of: ), below(of: ...), ...)  
[Source code](https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/RelativeView/RelativeView.swift)

<a href="https://github.com/mirego/PinLayout/blob/master/Example/PinLayoutSample/UI/Examples/RelativeView/RelativeView.swift"><img src="pinlayout_exampleapp_relative_position.png" alt="PinLayout example" width=120/></a> 


## Position a view relative to multiple views
This example show how to use relative positionning method relative to many other views. In this example the centered view is positionner between two other views.  
[Source code](https://github.com/mirego/PinLayout/tree/master/Example/PinLayoutSample/UI/Examples/MultiRelativeView)

<a href="https://github.com/mirego/PinLayout/tree/master/Example/PinLayoutSample/UI/Examples/MultiRelativeView"><img src="pinlayout_exampleapp_multi_relative_position.png" alt="PinLayout example" width=120/></a>