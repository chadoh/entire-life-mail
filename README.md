Entire.Life Email Templates
===========================

[Entire.Life] sends transactional email using [Postmark], and Postmark provides
a great place to store the markup for email templates.

So why this repository?

Because it's convenient to have [MJML] do the heavy lifting of generating all
that crazy email-compatible markup, and it's also convenient to have templates
in source control. Now the templates are more readable, and we can precisely
track how they change over time.

  [Entire.Life]: https://entire.life/
  [Postmark]: https://postmarkapp.com/
  [MJML]: https://mjml.io/


So how do I use this repository?
--------------------------------

1. Download/clone it
2. Install [`yarn`](https://yarnpkg.com/)
3. In your command line, `cd` into this directory
4. Run `yarn` to install all the dependencies
5. Run `yarn start`

This last command will do two things:

1. Run `mjml --watch` on all the files in the `templates` directory, and build
   them into the `build` directory
2. Run `http-server` to serve all the html files in the `build` directory

The output of `yarn start` (and specifically the `http-server` command) will
let you know that you can open `localhost:8080` in your browser to see your
built templates. Do that.

Now make changes to the templates in the `templates` directory (**Never** edit
the files in the `build` directory), and refresh the page in your browser to
see the changes.


Ok, it looks good, now what?
----------------------------

If it looks how you want it to, first you'll want to stop the `yarn start`
process. Do that by pressing <kbd>ctrl</kbd> <kbd>C</kbd>

Now copy the contents of one of the files in `build` and paste it into the
template editor on Postmark. Done!
