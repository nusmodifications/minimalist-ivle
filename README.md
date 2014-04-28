Minimalist-IVLE
===============

A stylesheet mod that turns IVLE into something usable by removing clutter.

This stylesheet should only be used by students because it may hide or modify
functionality that staff or lecturers might use.

##Installation Instructions

Inject the following stylesheet into your profile's welcome message:

    <link rel="stylesheet" href="https://www.qxcg.net/misc/ivlemin.css">

1. Go to "Profile > Profile".
2. Click on "Edit" at the bottom of the page.
3. Add the `<link>` tag above to your welcome message.

This causes the stylesheet to load on every page that the welcome message is
displayed. Most importantly, it loads on the landing page that displays all
your modules.

##Hosting Your Own Stylesheet

You can of course host your own stylesheet. Your server should also
support `https` to avoid cross-protocol warnings.

SoC students can host on `sunfire.comp.nus.edu.sg`.

1. Create `public_html` in your home directory.
2. `chmod -R 755 public_html`
3. Access via `{http, https}://sunfire.comp.nus.edu.sg/~user/`

##Contributing

Contributions welcome.

The overarching aim of this project is to turn IVLE into something usable.

Several things on the todo list:

1. Change the font.
2. Change the colour scheme.
3. Reactive!

##Disclaimer
This stylesheet might inadvertently hide important things on IVLE. Use at your
own risk.

Built during final exams Semester 2 AY13/14
