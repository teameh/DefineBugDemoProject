DefineBugDemoProject
====================

Debug Error: "Unbalanced calls to begin/end appearance transitions for ... "

23-Oct-2012 11:31 PM Tieme VAN VEEN:
Summary:

Defining a word in UITextView gives an error in de debugger

Steps to Reproduce:

 - Create "Single View Application"
 - Add UITextView
 - Run it
 - Select a word in the text view
 - Choose Define 

Expected Results:

 - Word defined

Actual Results:

 - Debugger shows something like: Unbalanced calls to begin/end appearance transitions for <_UIFallbackPresentationViewController: 0x74c1660>