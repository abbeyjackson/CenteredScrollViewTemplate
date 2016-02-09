# CenteredScrollViewTemplate
This is a template xib file that displays a scroll view which is horizontally centered on larger screens. It has a max width and a minimum width also. The same constraint pattern would apply if you the scrollview was shorter and you wanted it vertically centered. One of the items inside the scrollview has a 1:1 aspect ratio to demo variable constraints.

To use, download this file and then open in XCode. Click on each of the views to see the constraints in IB. To see in your project add this xib file to your project as well as a similarly named .swift file, set the owner of the file and then access as you would any other xib. For example:

let view = NSBundle.mainBundle().loadNibNamed(String(CenteredScrollViewTemplate), owner: nil, options: nil).first as! CenteredScrollViewTemplate
