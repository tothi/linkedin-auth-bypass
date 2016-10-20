# linkedin-auth-bypass

this is a minimal [WebExtension](https://wiki.mozilla.org/WebExtensions)
for **browsing** [LinkedIn](https://www.linkedin.com/)
and [Facebook](https://www.facebook.com/)
**without authorizing as a logged in user**.

these sites introduced some protection (probably
around 2016Q3) which prevented browsing unauthorized users
without a registered account. at LinkedIn it is a login/register
popup which completely disabled viewing profiles, at Facebook
it was a popup which just covered the page partly.

technically, this simple extension does nothing special, just
parses the page to be displayed on the client side by
the appropriate javascript and patches/removes these annoying
HTML elements, so this way making the whole page browsable.

the extension should work on browsers which support the
WebExtension standard (e.g. Chrome and Firefox). the
javascripts work against LinkedIn and Facebook on the
release date (20/16/2016).

this is *just a quick hack* for people (like me) who do not
want to share personal information to these giant spying bots,
but interested in browsing information about people who
do not care about privacy for some reason.

in short: there is *no update planned* for future versions
of LinkedIn / Facebook.
