# ng-input-filter
Standard filter box with label, input text field and clearing button

Provides two key components:

Input Filter control
* Label
* Input text field to set a filter value
* button to clear the filter

Directive for Controller augmentation (might do this by inclusion of the control).
* Augment controller to listen for a "filter-changed" event and if received modify the model value of the controller to drive filtering
