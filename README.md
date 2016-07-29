bootstrap-dropdown-select-extension
===================================

Extension to the Bootstrap Dropdown Javascript plugin. Add SELECT capability


Usage
======
 - Add `data-select="true"` to .dropdown-menu
 - (Optional) Add `data-select-text=".selected-container"` to .dropdown-menu
 - After the item is selected, it will has the class `selected`, the menu will be updated
  with the selected value
 - `selected.bs.dropdown` event will be triggered after selection is made

Article
=======
Please refer to this article on [My Blog](http://trinhtrunganh.com/extends-twitter-bootstrap-dropdown-to-act-like-a-selectbox/)

Example
=======
  ```html Dropdown with separated buttons
    <div class="btn-group dropup">
      <button type="button" class="btn btn-default">Where value should be updated</button>
      <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
        <span class="caret"></span>
        <span class="sr-only">Toggle Dropdown</span>
      </button>
      <ul class="dropdown-menu" role="menu" data-select="true">
        <!-- Dropdown menu links -->
      </ul>
    </div>
  ```
  
  ```html Dropdown with single button
    <div class="btn-group dropup">
      <button type="button" class="btn btn-default">
        <span class="selected-container">Where value should be updated</span>
        <span class="caret"></span>
        <span class="sr-only">Toggle Dropdown</span>
      </button>
      <ul class="dropdown-menu" role="menu" data-select="true" data-select-text=".selected-container">
        <!-- Dropdown menu links -->
      </ul>
    </div>
  ```
DEMO
=======
//TODO
