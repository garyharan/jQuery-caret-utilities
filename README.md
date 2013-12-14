# jQuery.caret.js

## What is it for?

Allows you to insert text anywhere within a text field.  You can also determine where the caret is and what text is selected.

**jQuery.insertAtCaret(text)**

  Insert `text` wherever the caret is in your input field.

**jQuery.setCaretPosition(start, [end])**

  Sets the caret position to the given values.  If `end` is present the text will be selected.

**jQuery.getCaretPosition()**

  Returns the starting position of your caret.

**jQuery.getSelectedText()**

  Returns the text within the selected portion of the item.  It is a very good workaround for the way window.getSelection() does not give you selected text inside form elements in Firefox.


----

Credits:

- Mike (aka oste on github) provided a fix for a textarea bug.
- lipanski provided a fix for editable containers
- schulzch made certain conditionals more robust
- Alexandre Kirillov (marexandre) fixing tests

---

Licensed under the incredibly permissive MIT License. Copyright © 2010-13
