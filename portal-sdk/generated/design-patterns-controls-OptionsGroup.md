﻿# OptionsGroup

 
<a name="basics"></a>
### Basics


<!-- TODO get an IMAGE to embed here -->

<!-- TODO get an SAMPLE CODE to embed here -->

 
<a name="when-to-use"></a>
### When to use
To select a **single option** among existing values.  Choose the control best suited to your needs
* **CheckBox** - a choice to opt in to a single choice.  For example, use a CheckBox for "I agree" instead of a different control where the user chooses between "I agree" and "I don't agree".
* **TriStateCheckBox** - can be checked, not checked or partially checked to indicate the checked state of children items in a hierarchy.
* **DropDown** - a single choice between a large number of options.  The DropDown control is also used on a smaller set of options where the default option is recommended for most users.  The DropDown control can also be used to make multiple selections from a set of options.
* **OptionsGroup** - a single choice between 2-4 equally weighted options where the options names are short.  For example, if the choices are On/Off, Yes/No, or None/Basic/Advanced an option group will work well.  
* **RadioButtons** - a single choice between 2-7 equally weighted options where the option names are long.   



 
<a name="best-practices"></a>
### Best practices
OptionsGroup is a great visual control when the user is presented with 2-4 choices with short names.

<a name="best-practices-do"></a>
#### Do

* Use when there are 2-4 options and the option names are short.  
* Use on forms and wizard pages to make the alternatives clear, even if a CheckBox is otherwise acceptable.
* List the options in a logical order, such as most likely to be selected to least, simplest operation to most complex, or least risk to most. Alphabetical ordering is not recommended because it is language dependent and therefore not localizable.
* If none of the options is a valid choice, add another option to reflect this choice, such as "None" or "Does not apply".
* Select the safest (to prevent loss of data or system access) and most secure and private option as the default. If safety and security aren't factors, select the most likely or convenient option.

<a name="best-practices-don-t"></a>
#### Don&#39;t

* Don't use if there are more than 4 options, use RadioButtons or DropDown instead.
* Don't use when the options are numbers that have fixed steps, like 10, 20, 30. Use a Slider component instead.
* Don't nest with other RadioButtons, OptionsGroups or CheckBoxes. If possible, keep all the options at the same level.
* Don't use when the option names are long, use RadioButtons instead.




 
<a name="developer-tips-and-tricks"></a>
### Developer tips and tricks



<a name="developer-tips-and-tricks-interactive-control-and-sample-source-code"></a>
#### Interactive control and sample source code
Go to the playground site to use the latest control and get source code for your project.  [Learn more about playground](./top-extensions-controls-playground.md).

*  <a href="https://ms.portal.azure.com/?Microsoft_Azure_Playground=true#blade/Microsoft_Azure_Playground/ControlsIndexBlade/OptionsGroup_create_Playground" target="_blank">OptionsGroup in the interactive controls playground</a>

 


 
<a name="related-info"></a>
### Related info

* <a href="https://www.figma.com/file/Bwn8rmUOYtnPRwA3JoQTBn/Azure-Portal-Toolkit?node-id=3410%3A7652" target="_blank">OptionsGroup in Azure Portal Toolkit (Figma)</a>

* [Azure design guidance](http://aka.ms/portalfx/design)


