Minimalist-IVLE
===============

A stylesheet mod that turns IVLE into something usable by removing clutter.

This stylesheet should only be used by students because it may hide or modify
functionality that staff or lecturers might use.

![Pretty Screenshot](https://raw.githubusercontent.com/cgcai/Minimalist-IVLE/master/screenshot.jpeg)

##Installation Instructions

Copy the following code into your profile's welcome message:

    NUSMods<link rel="stylesheet" href="https://www.qxcg.net/misc/ivlemin.css">

1. Go to "Profile > Profile".
2. Click on "Edit" at the bottom of the page.
3. Add the `<link>` tag above to your welcome message.

This causes the stylesheet to load on every page that the welcome message is
displayed. Most importantly, it loads on the landing page that displays all
your modules.

The mod can be uninstalled cleanly and leaves no side effects.

###Uninstalling

Go back to your profile page and remove the `<link>` tag in your welcome
message.

##Hosting Your Own Stylesheet

You can of course host your own stylesheet. Your server should also
support `https` to avoid cross-protocol warnings.

SoC students can host on `sunfire.comp.nus.edu.sg`.

1. Create `public_html` in your home directory.
2. `chmod -R 755 public_html`
3. Access via `{http, https}://sunfire.comp.nus.edu.sg/~user/`

##Contributions Welcome

3 easy steps:

1. Fork the repo.
2. Push a change to your own repo.
3. Send a Pull Request!

The overarching aim of this project is to turn IVLE into something usable. You
should open an issue before starting to work on something just in case someone
is already planning to do the same thing.

Several things on the todo list:

1. Test on TAs.
2. Test on lecturers.

##Disclaimer
This stylesheet might inadvertently hide important things on IVLE. Use at your
own risk.

Built during final exams Semester 2 AY13/14.
